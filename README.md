# monday.com for Claude Cowork

The official monday.com plugin for Claude Cowork. Manage your monday.com work directly from Cowork conversations - boards, items, docs, and forms - across work management, CRM, dev, service, and campaigns.

**What you can do:**

- Create, update, assign, and comment on items across any board, with the right column formatting handled automatically
- Generate project status reports that surface overdue items, blockers, and workload distribution
- Set up new boards with the right column types, groups, and templates for your use case
- Read, draft, and update monday docs with live board embeds and user mentions
- Build WorkForms for intake workflows linked directly to a target board

Connection is OAuth-based - no API tokens or manual configuration.

## How to use

Install the plugin, connect your monday.com account, then just tell Cowork what you want. The right skill activates automatically based on your request.

**Example prompts:**

- *"What's overdue on my sprint board - show a status breakdown and flag any blockers"*
- *"Create a project tracker for Q3 with groups for Backlog, In Progress, Review, and Done"*
- *"Add a high-priority bug to the tracker, assign it to me, and move it to In Progress"*
- *"Make a meeting notes doc for today's sync and embed the live status of our top 3 open items"*
- *"Build a bug intake form connected to my Bug Tracker - title, severity, steps to reproduce"*

## Skills

Five skills ship with this plugin. They auto-activate based on what you ask.

| Skill | What it does |
|---|---|
| `task-management` | Create, update, assign, and comment on items across any board |
| `project-status-report` | Generate status reports: overdue items, blockers, workload, recent activity |
| `board-setup` | Create boards with the right column types, groups, and templates |
| `docs-collaborator` | Read, draft, and update monday docs with live embeds and mentions |
| `forms-builder` | Build WorkForms for intake workflows linked to a target board |

## Setup

Connect via OAuth - no tokens or environment variables needed.

1. Install the plugin in Cowork.
2. Trigger any monday.com skill (e.g. "show me a status report for my project board").
3. Sign in to monday.com when prompted and approve the access scope.
4. Skills work across any board, workspace, or doc you have access to.

## Plan tiers

The plugin works on every monday.com plan. Some features vary by tier:

| Skill | Free / Basic | Standard | Pro+ |
|---|---|---|---|
| task-management | Full | Full | Full |
| project-status-report | Single board | Multi-board | Multi-board |
| board-setup | Standard columns | Standard columns | + formula columns |
| docs-collaborator | 3 docs cap | Unlimited | Unlimited |
| forms-builder | Full (with branding) | Limited customization | + branding removal |

The plugin will warn you when a request hits a plan-tier ceiling and suggest alternatives.

## Privacy and security

- All access is via OAuth 2.0. The plugin never sees or stores your monday.com credentials.
- The plugin connects only to `https://mcp.monday.com/mcp` (HTTPS, TLS 1.2+).
- Permissions are enforced at the MCP layer based on your monday.com role.
- No data leaves the monday.com ↔ Claude path you have already authorized.

## License

MIT. See `LICENSE` for details.

## Feedback and contributions

This plugin is open source. Issues and PRs welcome at [github.com/mondaycom/monday-claude-cowork-plugin](https://github.com/mondaycom/monday-claude-cowork-plugin).

For monday.com platform questions, see [developer.monday.com](https://developer.monday.com).

# monday.com for Claude Cowork

![monday.com](./assets/icon.png)

The official monday.com plugin for Claude Cowork. Manage your monday.com work directly from Cowork conversations - boards, items, docs, and forms - across work management, CRM, dev, service, and campaigns.

**What you can do:**

- Get started on monday.com with a board tailored to your work, starter items, and an automation
- Create, update, assign, and comment on items across any board, with the right column formatting handled automatically
- Generate project status reports that surface overdue items, blockers, and workload distribution
- Set up new boards with the right column types, groups, and templates for your use case
- Read, draft, and update monday docs with live board embeds and user mentions
- Build WorkForms for intake workflows linked directly to a target board

Connection is OAuth-based. Sign in when Claude asks.

## How to use

Install the plugin, connect your monday.com account, then just tell Cowork what you want. The right skill activates automatically based on your request.

**Example prompts:**

- *"Get me started with monday.com"*
- *"What's overdue on my sprint board - show a status breakdown and flag any blockers"*
- *"Create a project tracker for Q3 with groups for Backlog, In Progress, Review, and Done"*
- *"Add a high-priority bug to the tracker, assign it to me, and move it to In Progress"*
- *"Make a meeting notes doc for today's sync and embed the live status of our top 3 open items"*
- *"Build a bug intake form connected to my Bug Tracker - title, severity, steps to reproduce"*

## Skills

Six skills ship with this plugin. They auto-activate based on what you ask.

| Skill | What it does |
|---|---|
| `task-management` | Create, update, assign, and comment on items across any board, with correct column-value formatting |
| `project-status-report` | Generate status reports: overdue items, blockers, workload, recent activity |
| `board-setup` | Create and configure boards with the right groups, column types, and templates |
| `onboard-to-monday` | First-run onboarding: a board tailored to your work, with starter items, an automation, and an interactive table |
| `docs-collaborator` | Read, draft, and update monday docs with live board embeds and user mentions |
| `forms-builder` | Build WorkForms for intake workflows that capture responses as items on a backing board |

## Setup

Connect via OAuth. Sign in to monday.com when Claude prompts you.

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
| onboard-to-monday | Board and starter items | + starter automation | + starter automation |
| docs-collaborator | 3 docs cap | Unlimited | Unlimited |
| forms-builder | Full (with branding) | Limited customization | + branding removal |

The plugin will warn you when a request hits a plan-tier ceiling and suggest alternatives.

## Privacy and security

- Sign-in is OAuth 2.0 through the monday.com connector.
- The plugin connects only to `https://mcp.monday.com/mcp` (HTTPS, TLS 1.2+).
- Permissions are enforced at the MCP layer based on your monday.com role.
- Data stays on the monday.com connection you approved at sign-in.
- [Privacy](https://monday.com/privacy)

## License

MIT. See `LICENSE` for details.

## Feedback and contributions

This plugin is open source. Issues and PRs welcome at [github.com/mondaycom/monday-claude-cowork-plugin](https://github.com/mondaycom/monday-claude-cowork-plugin).

For monday.com platform questions, see [developer.monday.com](https://developer.monday.com).

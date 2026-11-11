# Chris Sanborn

Product engineer. I've been building for the web since 1999, and I'm strongest on the front end: TypeScript, React, Svelte, and the small details that make an interface feel fast and clear.

These days I ship mostly by directing AI coding agents. I write the spec, split the work into pieces that can run in parallel, hand them to agents (Claude Code, Codex, Cursor), and review what comes back against tests. The projects below were built that way. Each one has its spec, tests and CI in the repo.

## Recent projects

- [couch-picks](https://github.com/csanborn/couch-picks): a TV-style React app you drive with arrow keys. A hand-written spatial focus engine, plus the Claude API turning a mood into rows of picks. Runs offline in demo mode.
- [member-lab](https://github.com/csanborn/member-lab): a React and TanStack Query membership flow with A/B variants rendered in the browser, exposures logged only on real render, and a results page with confidence intervals, a trend chart and a sample ratio mismatch warning. Optimistic cancel, a bundle budget and Web Vitals, over a deliberately small GraphQL API.
- [spec-trace-mcp](https://github.com/csanborn/spec-trace-mcp): an MCP server that lets coding agents check which acceptance criteria in a spec have tests, and which do not.
- [agent-guardrails](https://github.com/csanborn/agent-guardrails): a Claude Code plugin with hooks and skills that stop agents from skipping linters, skipping tests or force pushing.
- [spec-to-code](https://github.com/csanborn/spec-to-code): a planner, implementer and reviewer agent loop that turns a short spec into a tested TypeScript module. The reviewer runs the real tests instead of trusting the model.

## Toolbox

- **AI:** Claude Code, Codex, Cursor, MCP, custom skills and agent rules, Anthropic and OpenAI APIs
- **Front end:** TypeScript, React, Redux, Next.js, Svelte, Tailwind
- **Back end:** Node, GraphQL, Postgres, Supabase, AWS
- **Testing:** Vitest, Jest, Testing Library, Playwright

Older repos from 2015 to 2021 are kept for history.

# Agent integrations

Foreman's assistant-neutral hook protocol lives in the core project. Installable assistant plugin
packages and publisher catalogs live in
[`thruwire/marketplace`](https://github.com/thruwire/marketplace), where their manifests and assets
are available to marketplace discovery before installation.

- The [Foreman Codex plugin](https://github.com/thruwire/marketplace/tree/main/plugins/foreman)
  invokes the core `foreman hook --client codex` protocol.
- [`claude/`](claude/) reserves the future Claude Code integration location. It is not currently an
  installable plugin.

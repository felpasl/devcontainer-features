# devcontainer-features

## claude-auth

Shares the Claude Code login from WSL with dev containers by bind-mounting
`${localEnv:HOME}/.claude` (host home) to `/opt/claude-config` and setting `CLAUDE_CONFIG_DIR`.

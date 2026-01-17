# focus-commands

Claude Code plugin providing project setup commands for Focus.AI projects.

## Installation

### Via Focus Marketplace (Recommended)

```bash
# Add the Focus marketplace (if not already added)
/plugin marketplace add The-Focus-AI/claude-marketplace

# Install the plugin
/plugin install focus-commands@focus-marketplace
```

Then restart Claude Code.

### Direct Install

```bash
/plugin install https://github.com/The-Focus-AI/focus-commands
```

## Available Commands

### /setup-beads

Initialize the Beads (bd) issue tracking system for the current project.

This command will:
1. Install required tools (Node.js, Claude Code, Beads) using mise
2. Initialize the beads database (`bd init`)
3. Configure Beads for Claude Code integration (`bd setup claude --project`)
4. Add onboarding reminder to CLAUDE.md

**Usage:**
```
/setup-beads
```

After running this command, you can use `bd` commands to manage issues in your project.

## About

This plugin is maintained by The Focus AI to streamline project setup workflows for Claude Code projects.

## License

MIT

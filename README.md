# Emil's Claude Code Plugins

Personal collection of Claude Code plugins.

## Installation

```bash
# Add this marketplace to Claude Code
/plugin marketplace add emilliepost/claude-plugins

# Browse available plugins
/plugin

# Install a specific plugin
/plugin install react-native-dev
```

## Available Plugins

| Plugin | Description |
|--------|-------------|
| `react-native-dev` | Expert React Native development assistant |

## Adding New Plugins

1. Create folder: `plugins/<plugin-name>/`
2. Add `.claude-plugin/plugin.json` with metadata
3. Add `commands/` folder for slash commands (`.md` files)
4. Add `agents/` folder for subagents (`.md` files)
5. Update `.claude-plugin/marketplace.json` with the new plugin entry

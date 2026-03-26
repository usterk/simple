# simple

A [Claude Code](https://claude.ai/code) plugin marketplace by [@usterk](https://github.com/usterk).

## Available plugins

| Plugin | Description |
|--------|-------------|
| [simple-tts](https://github.com/usterk/simple-tts) | macOS TTS notifications — speaks contextual summaries when Claude finishes or needs attention |

## Usage

```bash
# Add this marketplace
/plugin marketplace add usterk/simple

# Install a plugin
/plugin install simple-tts@simple

# Update a plugin
/plugin update simple-tts@simple
```

## For plugin authors

To add your plugin to this marketplace, open a PR adding an entry to `.claude-plugin/marketplace.json`.

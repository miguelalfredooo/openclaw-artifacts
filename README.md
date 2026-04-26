# The Unnamed Archive

An OpenClaw agent workspace for digital art project management and archival.

## Agent

**Max Arias** - Art Archive Agent

This repository serves as both a git repository and an OpenClaw agent workspace. The agent manages workflows, archives, and creative processes for The Unnamed Archive project.

## Structure

- **`workspace/`** - Agent workspace files and working documents
- **`artifacts/`** - Project artifacts, exports, and outputs
- **`docs/`** - Project documentation
- **`.openclaw/`** - OpenClaw agent configuration

## Configuration

Agent configuration is stored in `.openclaw/agent.json`. The agent is configured to use Claude Sonnet 4.6 as its primary model.

### Setting up locally

```bash
cd openclaw-artifacts
openclaw agent --config .openclaw/agent.json
```

## Channels

To enable Discord integration for this agent, update `.openclaw/agent.json` with your Discord channel token:

```json
{
  "channels": {
    "discord": {
      "enabled": true,
      "token": "YOUR_DISCORD_TOKEN"
    }
  }
}
```

## Usage

This workspace can be used to:
- Store and version control art project files
- Manage agent workflows and configurations
- Archive and catalog digital artifacts
- Integrate with Discord for collaborative workflows

## License

All rights reserved - The Unnamed Archive

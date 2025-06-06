# MindSwarm Core

> Orchestrating Collective AI Intelligence

MindSwarm Core is the open-source backend engine for orchestrating multiple AI agents in asynchronous swarms. It provides the full power of collaborative AI without artificial limitations.

## Features

- **Async Agent System**: Multiple AI agents running in parallel with independent loops
- **Full Tool Suite**: Complete access to all tools and capabilities
- **MCP Integration**: Model Context Protocol support for extensibility
- **WebSocket API**: Real-time communication for agent orchestration
- **No Limits**: Full agent capabilities in the open-source version

## Installation

```bash
pip install mindswarm-core
```

## Quick Start

```python
from mindswarm import SwarmOrchestrator

# Create a swarm
swarm = SwarmOrchestrator()

# Add agents
swarm.add_agent("Alice", role="coordinator")
swarm.add_agent("Debbie", role="developer")

# Start the swarm
await swarm.start()
```

## Documentation

Full documentation available at [docs.ltngt.ai](https://docs.ltngt.ai)

## License

MIT License - see LICENSE file for details.
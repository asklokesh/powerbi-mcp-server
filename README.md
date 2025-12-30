# Power BI MCP Server

<!-- mcp-name: io.github.asklokesh/powerbi-mcp-server -->

<div align="center">

# Powerbi Mcp Server

[![GitHub stars](https://img.shields.io/github/stars/LokiMCPUniverse/powerbi-mcp-server?style=social)](https://github.com/LokiMCPUniverse/powerbi-mcp-server/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/LokiMCPUniverse/powerbi-mcp-server?style=social)](https://github.com/LokiMCPUniverse/powerbi-mcp-server/network)
[![GitHub watchers](https://img.shields.io/github/watchers/LokiMCPUniverse/powerbi-mcp-server?style=social)](https://github.com/LokiMCPUniverse/powerbi-mcp-server/watchers)

[![License](https://img.shields.io/github/license/LokiMCPUniverse/powerbi-mcp-server?style=for-the-badge)](https://github.com/LokiMCPUniverse/powerbi-mcp-server/blob/main/LICENSE)
[![Issues](https://img.shields.io/github/issues/LokiMCPUniverse/powerbi-mcp-server?style=for-the-badge)](https://github.com/LokiMCPUniverse/powerbi-mcp-server/issues)
[![Pull Requests](https://img.shields.io/github/issues-pr/LokiMCPUniverse/powerbi-mcp-server?style=for-the-badge)](https://github.com/LokiMCPUniverse/powerbi-mcp-server/pulls)
[![Last Commit](https://img.shields.io/github/last-commit/LokiMCPUniverse/powerbi-mcp-server?style=for-the-badge)](https://github.com/LokiMCPUniverse/powerbi-mcp-server/commits)

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![MCP](https://img.shields.io/badge/Model_Context_Protocol-DC143C?style=for-the-badge)](https://modelcontextprotocol.io)

[![Commit Activity](https://img.shields.io/github/commit-activity/m/LokiMCPUniverse/powerbi-mcp-server?style=flat-square)](https://github.com/LokiMCPUniverse/powerbi-mcp-server/pulse)
[![Code Size](https://img.shields.io/github/languages/code-size/LokiMCPUniverse/powerbi-mcp-server?style=flat-square)](https://github.com/LokiMCPUniverse/powerbi-mcp-server)
[![Contributors](https://img.shields.io/github/contributors/LokiMCPUniverse/powerbi-mcp-server?style=flat-square)](https://github.com/LokiMCPUniverse/powerbi-mcp-server/graphs/contributors)

</div>

A Model Context Protocol (MCP) server for integrating Power BI with GenAI applications.

## Overview

Business analytics and data visualization

## Features

- Comprehensive Power BI API coverage
- Multiple authentication methods
- Enterprise-ready with rate limiting
- Full error handling and retry logic
- Async support for better performance

## Installation

```bash
pip install powerbi-mcp-server
```

Or install from source:

```bash
git clone https://github.com/asklokesh/powerbi-mcp-server.git
cd powerbi-mcp-server
pip install -e .
```

## Configuration

Create a `.env` file or set environment variables according to Power BI API requirements.

## Quick Start

```python
from powerbi_mcp import PowerBiMCPServer

# Initialize the server
server = PowerBiMCPServer()

# Start the server
server.start()
```

## License

MIT License - see LICENSE file for details

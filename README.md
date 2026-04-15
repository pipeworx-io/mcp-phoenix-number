# mcp-phoenix-number

phoenix-number MCP — wraps StupidAPIs (requires X-API-Key)

Part of the [Pipeworx](https://pipeworx.io) open MCP gateway.

## Tools

| Tool | Description |
|------|-------------|
| `phoenix_number_generate` | Returns the current temperature in Phoenix, Arizona. As a random number. This is not a weather API. |

## Quick Start

Add to your MCP client config:

```json
{
  "mcpServers": {
    "phoenix-number": {
      "url": "https://gateway.pipeworx.io/phoenix-number/mcp"
    }
  }
}
```

Or use the CLI:

```bash
npx pipeworx use phoenix-number
```

## License

MIT

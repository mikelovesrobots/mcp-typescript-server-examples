# mcp-typescript-server-examples
Just messing around in typescript learning @modelcontextprotocol/sdk

## Installation

* Get the right version of nodejs (optional): `asdf install`
* Install packages: `npm install`

## Running it

`npm run start`

## Inspecting it

`npx @modelcontextprotocol/inspector`
connect to the streamable HTTP URL http://localhost:3000/mcp

## Adding it to cursor

1. Go to settings
2. Select "Tools & MCP" in sidebar
3. Select "New MCP Server"
4. In mcp.json (which opens) do something like this:

```
{
  "mcpServers": {
    "dice": {
      "url": "http://localhost:3000/mcp",
      "headers": {}
    }
  }
}
```

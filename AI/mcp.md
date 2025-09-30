{
  "mcpServers": {
    "browser": {
      "command": "npx",
      "args": [
        "@agent-infra/mcp-server-browser@latest"
      ]
    },
    "chrome-mcp-server": {
      "type": "streamableHttp",
      "url": "http://127.0.0.1:12306/mcp"
    },
    "blender": {
      "command": "cmd",
      "args": [
          "/c",
          "uvx",
          "blender-mcp"
      ]
  }
  }
}


# MemOS-MCP
{
  "mcpServers": {
    "memos-api-mcp": {
      "timeout": 60,
      "type": "stdio",
      "command": "npx",
      "args": [
        "-y",
        "@memtensor/memos-api-mcp@latest"
      ],
      "env": {
        "MEMOS_API_KEY": "mpg-VJuNeBp+SoporoR3kUr2L0TSe4a67uF5NZ/jJIax",
        "MEMOS_USER_ID": "cherrystudio",
        "MEMOS_CHANNEL": "MODELSCOPE"
      }
    }
  }
}

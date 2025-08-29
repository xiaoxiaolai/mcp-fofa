## FOFA MCP
基于 Model Context Protocol (MCP) 的fofa数据查询。


## 工具列表
| name | description |
| ----------- | ----------- |
| auth  | fofa搜索之前所必须的key验证 |
| search | ofa搜索 |

## MCP 服务器配置
```
{
  "mcpServers": {
    "mcp_fofa": {
      "isActive": true,
      "name": "calculator",
      "type": "stdio",
      "command": "uv",
      "args": [
        "--directory",
        "/Users/xiezi/explore/mcp-fofa/src",  # 替换为自己的路径
        "run",
        "-m",
        "mcp_fofa"
      ]
      }
  }
}

{
  "mcpServers": {
    "mcp_fofa": {
        "command": "uvx",
        "args": [
          "mcp_fofa@latest"
        ]
      }
  }
}
```


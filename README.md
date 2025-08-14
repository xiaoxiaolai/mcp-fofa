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
    "mcp-fofa": {
        "command": "uv",
        "args": [
            "run",
            "python",
            "main.py"
        ]
      }
  }
}
```


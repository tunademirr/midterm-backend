
On the terminal

pip install fastmcp requests

Starting server on the terminal

python mcp_server.py

 Changing JSON on claude_desktop_config.json

{
  "mcpServers": {
    "grade-predictor": {
      "command": "python",
      "args": [
        "REAL_PATH/mcp_server.py"
      ]
    }
  }
}
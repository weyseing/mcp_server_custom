# Reference
- https://www.youtube.com/watch?v=-8k9lGpGQ6g
- https://github.com/techwithtim/PythonMCPServer

# Setup MCP Server 
- Install `uv`
    - For Linux/macOS: `curl -LsSf https://astral.sh/uv/install.sh | sh`
    - For Windows (PowerShell): `iwr -useb https://astral.sh/uv/install.ps1 | iex`
- Register script as MCP-server for local MCP-client
    - `uv run mcp install .\main.py` 
    - **[Claude Desktop]** Need to restart to reflect changes
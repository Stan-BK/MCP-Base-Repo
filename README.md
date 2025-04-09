# MCP-Based-Repo

Provide a simple MCP server integration in `VSCode` and `Cursor`.

## In VSCode

### Setup
- First need to enable agent mode in setting (**!! Important**)

    ![alt text](./example_assets/image.png)

- Then u can straight to choose needed MCP server for enhance ur agent mode copilot!

    ![alt text](./example_assets/image-1.png)

- Other MCP server integration can be added in `.vscode/mcp.json` then `VSCode` will identify them.

### Example
I try to get my github account based info which the way github-mcp-server had exposed for me. So copilot integrate with `VSCode` (Here as a MCP Client) can related the server's capability and get use of it.

![alt text](./example_assets/image-2.png)

After I permit that bevahior, finally I can get the response from github-mcp-server.

![alt text](./example_assets/image-3.png)

## In Cursor

### Setup
- MCP server in `Cursor` is configure in `.cursor/mcp.json`, then `Cursor` will identifies and integrates them automatically.

  ![alt text](./example_assets/image-4.png)

- Then u can straight to ask for help and enjoy the seemless experience like before, that means `Cursor` will implicity integrate the needed MCP server for u.

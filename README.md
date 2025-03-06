❯ mkdir mc
❯ cd mc
❯ uv init
Adding `mc` as member of workspace `/home/rag/python`Initialized project `mc`
❯ ls pyproject.toml README.md󱧼 src
❯ uv add "mcp[cli]

"Resolved 67 packages in 60ms  Built mc @ file:///home/rag/python/mcPrepared 1 package in 228ms████████████████████ [1/1] mc==0.1.0 (from file:///home/rag/python/mc)                                               Installed 1 package in 0.70ms+ mc==0.1.0 (from file:///home/rag/python/mc)
❯ ls pyproject.toml README.md󱧼 src
❯ uv run src/mc/__init__.py
❯ cd src/mc
❯ ls __init__.py
❯ nv server.py
❯ uv run server.py
❯ mcp dev server.py

Starting MCP inspector...Proxy server listening on port 3000

🔍 MCP Inspector is up and running at http://localhost:5173 🚀

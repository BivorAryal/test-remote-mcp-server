1. Create new folder
2. Open folder in VS code
3. uv init . 
    - .venv\Scripts\activate
4. uv add fastmcp
    - uv run fastmcp --version
5. create simple server
    RUN SERVER: 
        fastmcp run main.py
    TEST SERVER:     
        uv run fastmcp dev inspector main.py
    ADD server to Claude: 
        uv run fastmcp install claude-desktop main.py

1. create github repo
2. git init, 
    git add ., 
    git commit -m "first commit", 
    git remote add origin https://github.com/BivorAryal/test-remote-mcp-server.git, 
    git branch -M main,
    g, 

        - if you rerun it 
            - git status
            - git add .
            - git commit -m "Updated code"
            - git push origin main
3. Create FASTMCP cloud account
    "https://horizon.prefect.io/practive/servers/frightened-red-tiglon/deployments"
4. Depoly on FASTMCP cloud

1. USing Claude Desktop
    - Add using Costum Connector.


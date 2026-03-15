1. Create new folder
2. Open folder in VS code
3. uv init . - .venv\Scripts\activate
4. uv add fast mcp
5. create simple server
6. run server :     fastmcp run main.py --transport http --host 0.0.0.0 --port 8000
7. test server:     uv run fastmcp dev inspector main.py
8. create github repo
9. git init, 
    git add ., 
    git commit -m "first commit", 
    git remote add origin https://github.com/BivorAryal/test-remote-mcp-server.git, 
    git branch -M main,
    git push -u origin main, 

        - if you rerun it 
            - git status
            - git add .
            - git commit -m "Updated code"
            - git push origin main
10. Create FASTMCP cloud account
    "https://horizon.prefect.io/practive/servers/frightened-red-tiglon/deployments"
11. Depoly on FASTMCP cloud


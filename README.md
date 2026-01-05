# powershell-cheat-sheet
PowerShell cheat sheet

### What are the **Ghost Server** ?

“Ghost servers” = processes still running after the terminal/tab is closed.

For listening all the servers.

```bash
# For all ghost servers
netstat -ano

# Specific server
netstat -ano | findstr :3000
```

Killing ongoing task

```bash
taskkill /PID 12345 /F
```
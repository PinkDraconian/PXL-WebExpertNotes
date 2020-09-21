---
title: Common errors
created: '2020-09-21T12:26:11.863Z'
modified: '2020-09-21T12:29:02.364Z'
---

# Common errors
- `Path\To\npm\ng.ps1 cannot be loaded because running scripts is disabled on this system. <MORE...>`
Occurs because in PowerShell, we need to enable the running of scripts by executing: `Set-ExecutionPolicy Unrestricted -Scope CurrentUser -Force`
 

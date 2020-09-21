---
title: Common errors
created: '2020-09-21T12:26:11.863Z'
modified: '2020-09-21T13:26:14.702Z'
---

# Common errors
- `Path\To\npm\ng.ps1 cannot be loaded because running scripts is disabled on this system. <MORE...>`
  - Occurs because in PowerShell, we need to enable the running of scripts by executing: `Set-ExecutionPolicy Unrestricted -Scope CurrentUser -Force`
- `An unhandled exception occurred: Cannot find module '@angular-devkit/build-angular/package.json'`
  - Occurs whilst running `ng serve -o` when the `node_modules` folder is missing. Run `npm install` to fix this error. 
 

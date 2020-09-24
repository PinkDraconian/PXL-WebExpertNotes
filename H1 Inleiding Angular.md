---
title: H1 Inleiding Angular
created: '2020-09-24T17:46:27.979Z'
modified: '2020-09-24T18:35:35.042Z'
---

# H1 Inleiding Angular
## Wat is Angular
- Framework voor het programmeren van complexe web apps
- Concepten die het mogelijk maken om code en structuur van elkaar te scheiden, modulair programmeren en testbare applicaties maken

## Angular opbouw
- Modules
  - Declareren en laden van gebruikte elementen
  - Bootstrappen van de app
- Components
  - View (HTML/CSS met Angular directives)
  - Controller (Typescript klasse met logica)
- Databinding
- Services

## App structure
- node_modules
  - Bevat modules en 3rd party libraries / dependencies
- src
  - index.html
    - Eerste pagine die geladen wordt
    - Hierin wordt de component \<app-root\> geplaatst. Deze is gelinkt aan de app.component.ts
  - app
    - app.module.ts
      - Bevate alle declarations, imports en providers die gebruikt worden binnen het project
    - app.component.ts
      - De default component die geladen wordt
- package.json

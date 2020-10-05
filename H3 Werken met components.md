---
title: H3 Werken met components
created: '2020-09-25T08:38:32.325Z'
modified: '2020-09-25T09:19:42.519Z'
---

# H3 Werken met components
## Opbouw component
- Imports
- Annotatie @Component
  - Metadata in JSON format
- Component klasse
  - Export keyword (Can be imported by other components)

## @Component
- selector
- template
- styles
- templateUrl
- styleUrl
- input
- output
- providers

## Component aanmaken
`ng generate component <PATH/TO/COMPONENT>`

## Lifecycle hooks
Uitvoeren van code op bepaalde tijdstippen
- ngOnInit()
  - Na het uitvoeren van de constructor van een component
  - Importeren: `import { OnInit } from '@angular/core'`
  - Implement: `export class nameComponent implements OnInit { ngOnInit() { ... }}`
- ngOnChanges()
  - Na het aanpassen van een data-gebonden input veld
- ngOnDestroy()
  - Bij het vernietigen van het component

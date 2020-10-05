---
title: H5 Attribute directives & Property bindings
created: '2020-10-05T18:43:01.542Z'
modified: '2020-10-05T18:55:46.788Z'
---

# H5 Attribute directives & Property bindings
## Wat zijn directives
Stukken HTML code met Angular logic
## Soorten directives
- Component (`<app-login></app-login>`)
- Attribute directives (ngClass, ngStyle)
- Structural directives (ngIf, ngFor)

## ngClass
Dynamisch toevoegen van CSS klasse aan een element
`<div [ngClass]='{active: IsActive, bordered: hasBorder}' />`

## ngStyle
CSS stijlen direct toevoegen
`<div [ngStyle]='styles' />` 
`styles: Object = { color: 'black'}`


## Element properties
Eender welke DOM property van element kan aangesproken worden
`[prop_name] = 'variable | expression'`

## Structurele directives
Passen de DOM aan
- `*ngIf`
- `*ngFor`
  - `index`, `first`, `last`, `even`, `odd`
  - `*ngFor='let i of array; let i = index'`
- `*ngSwitch`
  - `*ngSwtichCase`, `*ngSwitchDefault`

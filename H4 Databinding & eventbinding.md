---
title: H4 Databinding & eventbinding
created: '2020-10-05T18:28:45.970Z'
modified: '2020-10-05T18:37:47.238Z'
---

# H4 Databinding & eventbinding
| Type | Syntax |
| --- | --- |
| 1-way (Controller to view) | `{{ var }}` |
| 2-way | `[(ngModel)='var')]` |
| 1-way (View to controller) (event) | `(click)='method()'` |
| 1-way (View to controller) (property) | `[disabled]='var'` |

## Data from parent to child component
Child: `@Input() var: type;`
Parent: `<child [var]='var' />` 

## Data from child to parent component
Child: `@Output() var = new EventEmitter()`
Parent: `<child (var)="method($event)" />`


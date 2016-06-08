# Wtf-select
---
It's a simple select component based in angular2-material [input component](https://github.com/angular/material2/tree/master/src/components/input).

Version: 1.0.0
### Installation
---
Run following command:
```sh
$ npm install wtf-select
```
### Usage
---
Now, u can make simple forms by using of material select tags.

```html
...
<md-select placeholder="MyPlaceholder" [(ngModel)]="TARGET_SELECTED_ITEM">
    <!-- u can use *ngFor too -->
    <md-option [value]="UR_VALUE" [label]="UR_LABEL"></md-option> 
</md-select>
...
```
### Notes
---
The md-option label ~~*cannot*~~ be used between `<md-option>` tags. It should be like as shown above.
```html
<!-- It's still does not work :( -->
<md-option [value]="UR_VALUE">UR_LABEL</md-option>
```
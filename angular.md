# Angular

## installing angular

`npm install -g @angular/cli`<br>
this will install Angular CLI

## First project

to create a new project use:<br>
`ng new ng6-proj --style=scss --routing`

ng is how we call the Angular CLI

new is obvious 

ng6-proj is our name for the project
CLI will create a new directory

with --style= scss we're creating a project, where Sass is enabled<br>
( without --style it is by default it is css)

with --routing add diffrente page URL's

`ng serve -o`<br>
this command launches the project in your browser

## create new Components

`ng generate component "name"`<br>
this will create a new component for you. You can use the short cut version
``ng g c "name"``<br>
to create a new service use:
``ng generate service "name"``

## Code Stuff

you can use `*ngFor` for a for-loop e.g.<br> `<li *ngFor ="let "name" of "name object"$ >`

## creating dist-folder
```ng build```
or <br>
``ng build -prod`` for smaller size of the projects<br>
if you run into problems create a ``<div *ngIf="objectname$"``
around the troubleshooter

## Animations

difficulty stuff<br>
use ``trigger("name",[definitions])`` to create a trigger for an animation<br>
```transition('stateChangeExpression',[Steps] )``` stateChangeExpression tells when the animation should start<br>
``query('selector',[animation],(stagger),)`` The selector tells when de animation is used, animation tells the style of the animation and the staggering. 


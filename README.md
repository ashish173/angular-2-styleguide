# angular-2-styleguide
Angular2 Style Guide: A starting point for Angular2 development teams to provide consistency through good practices.

## Caution ##
This guide is incomplete and it will change at a very fast pace so in case you are picking something from here please understand things will change as Angular2 itself is evolving at the moment.


## Modules ##

We always had a problem with module loaders. What should I use? Maybe the classic way of endless script tags? Require.js? Browserify / webpack?… Angular 2 uses the standard System.js which is a universal module loader that loads ES6 modules, AMD, Common JS…

Now inside our main file, we just need to:

```
import {bootstrap} from 'angular2/angular2';
import {App} from 'app';

bootstrap(App);
```

Thanks to our module loader, we now see where this bootstrap and App comes from and also, we don’t need to create a \<script\> tag for every javascript file in our application. Ah, this also means, no more ng-app.


## Components ##

Components are the center most important piece of Angular2 so one should really understand what components are.


## Directives ##


## Properties  ##


## Events ##


## References ##


## Services ##


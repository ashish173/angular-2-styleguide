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

Components are the basic building blocks which build an application, these blocks have views, and class.

So someone coming from angular1.x will agrue aren't components similar to directives they too have controllers(class here) and then a custom view, well to say that won't be wrong.

In fact Angular2 components are more or less the directives of Angular1.x, whick makes sense as directives bring the real power of DOM manipulation. They are the real heroes of this war!!!

In fact components extend from from angular2's directives, 

Here is a full comparision of Directives in Angular1.x to Components in Angular2.0.alpha



## Directives ##


## Properties  ##


## Events ##


## References ##


## Services ##



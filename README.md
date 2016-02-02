# FlareTail.js

A JavaScript library for Firefox application development, consisting of WAI-ARIA-driven accessible widgets, a lightweight app framework, and convenient utility functions.

This is the core of [BzDeck](https://github.com/bzdeck/bzdeck) and not intended for general use at this time.

* **helpers**: Convenient utility functions handling a variety of stuff for an application, including a [Microdata](http://www.w3.org/TR/microdata/)-based HTML5 template engine, keybinding support and date formatter.
* **widgets**: A collection of [WAI-ARIA](http://www.w3.org/TR/wai-aria/)-driven accessible widgets. This will use [Custom Elements](https://developer.mozilla.org/en-US/docs/Web/Web_Components/Custom_Elements) once the feature is implemented by Firefox.
* **app**: App framework featuring a multithreaded, MVC-extended pattern.

# CyProAssist UI

## HTML5

### Pros

- easily customizable
- widely standardized
- good modularity

### Cons

- requires a web browser
- HTML components may not be supported by all devices (like watches)

### Existing tools

#### [JQuery](https://jquery.com/)

The swiss army knife for DOM traverals and manipulation.
Has a wide range of methods and many extensions are already available.

#### [Bootstrap](http://getbootstrap.com/)

The CSS framework from Twitter. Has a fluid grid system and good support for responsive web sites (or hybrid apps).
Many components (forms, alerts etc.) are already available.

### [RequireJS](http://requirejs.org/)

A widely used module loader for Javascript. The defacto standard for modularizing client-side Javascript applications.

### [FlightJS](https://github.com/flightjs/flight)

Ultra lightweight framework for UI components based on JQuery and RequireJS. 
Forces developers to create independet components by disallowing direct bi-directional access to properties - communication is
only possible through DOM events.
Not under active development at the moment but fully functional.

### [React](https://facebook.github.io/react/)

A complete framework for the development of HTML UI components with its own proprietary syntax for mixed Javascript/HTML files (JSX).

### [Polymer](https://www.polymer-project.org/)

A web components based framework for the development of HTML UIs. Uses features like shadow dom that are not natively supported by most current browsers.




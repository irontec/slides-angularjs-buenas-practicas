
### Una única responsabilidad
#### Código ravioli vs. código espagueti

app.js
```JavaScript
angular
    .module('app', ['ui.router'])
    .controller('SomeController', SomeController)
    .factory('SomeFactory', SomeFactory);

function SomeController() { ... }

function SomeFactory() { ... }
```

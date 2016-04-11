
### Una única responsabilidad
#### Código ravioli vs. código espagueti

app.js
```JavaScript
angular
    .module('app', ['ui.router'])
```

someController.js
```JavaScript
angular
    .module('app')
    .controller('SomeController', SomeController);

function SomeController() { ... }
```

someFactory.js
```JavaScript
angular
    .module('app')
    .factory('SomeFactory', SomeFactory);

function SomeFactory() { ... }
```

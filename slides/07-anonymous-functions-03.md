### Funciones anónimas vs declaradas

Buena práctica

```JavaScript
angular
    .module('app')
    .controller('DashboardController', DashboardController);

function DashboardController() { ... }
```

```JavaScript
angular
    .module('app')
    .factory('logger', logger);

function logger() { ... }
```

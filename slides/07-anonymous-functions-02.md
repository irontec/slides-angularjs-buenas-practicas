### Funciones anónimas vs declaradas

Mala práctica

```JavaScript
angular
    .module('app')
    .controller('DashboardController', function() { ... })
    .factory('logger', function() { ... });
```

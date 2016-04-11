### Controller as vm

Mala práctica

```JavaScript
function Customer() {

    $scope.name = 'Mikel';

    $scope.sendMessage = function() { ... };
}
```

```html
<input ng-model="name"/>
```

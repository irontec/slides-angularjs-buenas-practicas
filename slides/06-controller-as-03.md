### Controller as vm

Buena práctica

```JavaScript
function Customer() {

    var vm = this;

    vm.name = 'Mikel';

    vm.sendMessage = function() {};
}
```

```html
<input ng-model="vm.name"/>
```

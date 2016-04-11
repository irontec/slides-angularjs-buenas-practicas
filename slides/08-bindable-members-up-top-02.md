### Asociaciones en la parte superior

Mala práctica

```JavaScript
function Sessions() {

    var vm = this;
    vm.gotoSession = function() {
        /* ... */
    };

    vm.sessions = [];

    vm.title = 'Sessions';
}
```

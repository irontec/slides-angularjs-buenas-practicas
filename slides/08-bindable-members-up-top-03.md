### Asociaciones en la parte superior

Buena práctica

```JavaScript
function Sessions() {

    var vm = this;

    // Variables
    vm.sessions = [];
    vm.title = 'Sessions';

    // Funciones
    vm.gotoSession = gotoSession;

    ////////////////////////////////////

    function gotoSession() {
        /* ... */
    }
}
```

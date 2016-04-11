### Delegar la lógica

Buena práctica

```JavaScript
function OrderController($http, $q, config, userInfo) {
    var vm = this;
    // variables
    vm.isCreditOk;
    vm.total = 0;
    // funciones
    vm.checkCredit = checkCredit;
    /////////////////

    function checkCredit() {
        var settings = {/* ... */};

        return $http.get(settings)
            .then(requestCompleted)
            .catch(requestFailed);

        function requestCompleted(isOk) {
            vm.isCreditOk = isOk;
        }

        function requestFailed() {
            // Gestionar el error
        }
    };
}
```

### Delegar la lógica

Mala práctica

```JavaScript
function OrderController($http, $q, config, userInfo) {
    var vm = this;

    vm.isCreditOk;
    vm.total = 0;

    vm.checkCredit = checkCredit;
    /////////////////

    function checkCredit() {
        var settings = {/* ... */};

        return $http.get(settings)
            .then(function(data) {
                // obtener maxRemainingAmount del objeto data
                vm.isCreditOk = vm.total <= maxRemainingAmount
            })
            .catch(function(error) {
                // Mostrar el error
            });
    };
}
```

### Funciones anónimas vs declaradas

Mala práctica

```JavaScript
$http(req).then(function(data) {
    $scope.idLaboratorio = data.data[0].id_laboratorio;
}, function(response) {
    // alert('Error with status code:' +
    // response.status);
    // _mostrarError(response.status);
});
```

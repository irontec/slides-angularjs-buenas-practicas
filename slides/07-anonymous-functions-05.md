### Funciones anónimas vs declaradas

Buena práctica

```JavaScript
$http(req)
    .then(requestCompleted)
    .catch(requestFailed);

function requestCompleted(response) {
    $scope.idLaboratorio = response.data[0].id_laboratorio;
}

function requestFailed(response) {
    // alert('Error with status code:' +
    // response.status);
    // _mostrarError(response.status);
}

```

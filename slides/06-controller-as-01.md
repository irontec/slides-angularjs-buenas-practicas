### Controller as vm

- Utilizaremos la sintaxis **controller as** en vez del clásico controller con **$scope**.

- Capturaremos el **this** en una variable llamada **vm** (ViewModel).

- Ayuda a prevenir el uso excesivo del **$scope**.

- En la medida de lo posible, hay que **delegar** la lógica de los controladores a servicios.

- El **$scope** se debe utilizar únicamente cuando es necesario; **$emit**, **$broadcast** o **$on**.

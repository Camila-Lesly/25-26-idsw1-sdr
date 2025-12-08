# Casos de Uso

<div align=center>

|||||
|-|-|-|-|
|[Inicio](/README.md)|[Modelo del dominio](/documentos/00-modeloDeDominio/README.md)|**Casos de uso**|[Análisis]()|

</div>

## Actores y casos de uso identificados

<div align=center>

|||
|:-:|:-:|
|![Actores y Casos de Uso](/documentos/01-casoDeUso/1-CasoDeUso/Administrador/administradorCasoDeUso.svg)|![Actores y Casos de Uso](/documentos/01-casoDeUso/1-CasoDeUso/Visitante/visitanteCasosDeUso.svg)|!
|Código fuente:[ administrador.puml](/documentos/01-casoDeUso/1-CasoDeUso/Administrador/adminCasosDeUso.puml)|Código fuente: [visitante.puml](/documentos/01-casoDeUso/1-CasoDeUso/Visitante/visitanteCasosDeUso.puml)

</div>

## Diagrama de contexto

<div align=center>

|||
|:-:|:-:|
|![Administrador](/documentos/01-casoDeUso/2-DiagramaDeContexto/diagramaDeContextoAdministrador.svg)|![Visitante](/documentos/01-casoDeUso/2-DiagramaDeContexto/diagramaDeContextoVisitante.svg)|!
|Código fuente:[ administrador.puml](/documentos/01-casoDeUso/1-CasoDeUso/Administrador/adminCasosDeUso.puml)|Código fuente: [visitante.puml](/documentos/01-casoDeUso/1-CasoDeUso/Visitante/visitanteCasosDeUso.puml)

</div>

## Detalle de los casos de uso

### Diagramas detallados (Administrador)

|Gestión de espacios|Gestión de recorridos|
|-|-|
|[verEspacios()](../4-Prototipo/0-Administrador/verEspacios/)|[verRecorridos()](../4-Prototipo/0-Administrador/verRecorridos/)|
|[crearEspacio()](../4-Prototipo/0-Administrador/crearEspacio/)|[crearRecorrido()](../4-Prototipo/0-Administrador/crearRecorrido/)|
|[actualizarEspacio()](../4-Prototipo/0-Administrador/actualizarEspacio/)|[actualizarRecorrido()](../4-Prototipo/0-Administrador/actualizarRecorrido/)|
|[eliminarEspacio()](../4-Prototipo/0-Administrador/eliminarEspacio/)|[eliminarRecorrido()](../4-Prototipo/0-Administrador/eliminarRecorrido/)|

### Diagramas detallados (Visitante) 

|Recorridos y ubicación|Exploración de espacios|
|-|-|
|[buscarEspacio()](../4-Prototipo/1-Visitante/buscarEspacio/)|[verDetalles()](../4-Prototipo/1-Visitante/verDetalles/)|
|[cambiarDeEspacio()](../4-Prototipo/1-Visitante/cambiarDeEspacio/)|[verEspaciosCercanos()](../4-Prototipo/1-Visitante/verEspaciosCercanos/)|
|[verUbicacionActual()](../4-Prototipo/1-Visitante/verUbicacionActual/)|[verEspaciosPlanta()](../4-Prototipo/1-Visitante/verEspaciosPlanta/)|
|[verRecorridosDisponibles()](../4-Prototipo/1-Visitante/verRecorridosDisponibles/)| |
|[seleccionarRecorrido()](../4-Prototipo/1-Visitante/seleccionarRecorrido/)| |
|[salirRecorrido()](../4-Prototipo/1-Visitante/salirRecorrido/)| |

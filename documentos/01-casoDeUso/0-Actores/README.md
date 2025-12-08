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
|[verEspacios()](../3-DetallarCasosDeUso/0-Administrador/verEspacios/verEspacio.svg)|[verRecorridos()](../3-DetallarCasosDeUso/0-Administrador/verRecorridos/verRecorridos.svg)|
|[crearEspacio()](../3-DetallarCasosDeUso/0-Administrador/crearEspacio/crearEspacio.svg)|[crearRecorrido()](../3-DetallarCasosDeUso/0-Administrador/crearRecorrido/crearRecorrido.svg)|
|[actualizarEspacio()](../3-DetallarCasosDeUso/0-Administrador/actualizarEspacio/actualizarEspacio.svg)|[actualizarRecorrido()](../3-DetallarCasosDeUso/0-Administrador/actualizarRecorrido/actualizarRecorrido.svg)|
|[eliminarEspacio()](../3-DetallarCasosDeUso/0-Administrador/eliminarEspacio/eliminarEspacio.svg)|[eliminarRecorrido()](../3-DetallarCasosDeUso/0-Administrador/eliminarRecorrido/eliminarRecorrido.svg)|

### Diagramas detallados (Visitante) 

|Recorridos y ubicación|Exploración de espacios|
|-|-|
|[buscarEspacio()](../3-DetallarCasosDeUso/1-Visitante/buscarUbicacion/buscarUbicacion.svg)|[verDetalles()](../3-DetallarCasosDeUso/1-Visitante/verDetalles/verDetalles.svg)|
|[cambiarDeEspacio()](../3-DetallarCasosDeUso/1-Visitante/cambiarUbicacion/cambiarUbicacion.svg)|[verEspaciosCercanos()](../3-DetallarCasosDeUso/1-Visitante/verEspaciosCercanos/verEspaciosCercanos.svg)|
|[verUbicacionActual()](../3-DetallarCasosDeUso/1-Visitante/verUbicacionActual/verUbicacionActual.svg)|[verEspaciosPlanta()](../3-DetallarCasosDeUso/1-Visitante/verEspaciosPlanta/verEspaciosPlanta.svg)|
|[verRecorridosDisponibles()](../3-DetallarCasosDeUso/1-Visitante/verRecorridosDisponibles/verRecorridosDisponibles.svg)| |
|[seleccionarRecorrido()](../3-DetallarCasosDeUso/1-Visitante/seleccionarRecorrido/seleccionarRecorrido.svg)| |
|[salirRecorrido()](../3-DetallarCasosDeUso/1-Visitante/salirRecorrido/salirRecorrido.svg)| |

# Casos de Uso

<div align=center>

|                      |                                                                |                  |     |
| -------------------- | -------------------------------------------------------------- | ---------------- | --- |
| [Inicio](/README.md) | [Modelo del dominio](/documentos/00-modeloDeDominio/README.md) | **Casos de uso** |

</div>

## Actores y casos de uso identificados

<div align=center>

|                                                                                                              |                                                                                                          |
| :----------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------: |
|   ![Actores y Casos de Uso](/documentos/01-casoDeUso/1-CasoDeUso/Administrador/adminCasosDeUso.svg)   |    ![Actores y Casos de Uso](/documentos/01-casoDeUso/1-CasoDeUso/Visitante/visitanteCasosDeUso.svg)     | ! |
| Código fuente:[ administrador.puml](/documentos/01-casoDeUso/1-CasoDeUso/Administrador/adminCasosDeUso.puml) | Código fuente: [visitante.puml](/documentos/01-casoDeUso/1-CasoDeUso/Visitante/visitanteCasosDeUso.puml) |

</div>

## Diagrama de contexto

<div align=center>

|                                                                                                              |                                                                                                          |
| :----------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------: |
|     ![Administrador](/documentos/01-casoDeUso/2-DiagramaDeContexto/diagramaDeContextoAdministrador.svg)      |       ![Visitante](/documentos/01-casoDeUso/2-DiagramaDeContexto/diagramaDeContextoVisitante.svg)        | ! |
| Código fuente:[ administrador.puml](/documentos/01-casoDeUso/1-CasoDeUso/Administrador/adminCasosDeUso.puml) | Código fuente: [visitante.puml](/documentos/01-casoDeUso/1-CasoDeUso/Visitante/visitanteCasosDeUso.puml) |

</div>

## Detalle de los casos de uso

### Diagramas detallados (Administrador)

| Gestión de espacios                                                                          | Gestión de recorridos                                                                              |
| -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| [abrirEspacios()](../4-Prototipo/0-Administrador/abrirEspacios/abrirEspacios.md)                   | [abrirRecorridos()](../4-Prototipo/0-Administrador/abrirRecorridos/abrirRecorridos.md)                   |
| [crearEspacio()](../4-Prototipo/0-Administrador/crearEspacio/crearEspacio.md)                | [crearRecorrido()](../4-Prototipo/0-Administrador/crearRecorrido/crearRecorrido.md)                |
| [editarEspacio()](../4-Prototipo/0-Administrador/editarEspacio/editarEspacio.md) | [editarRecorrido()](../4-Prototipo/0-Administrador/editarRecorrido/editarRecorrido.md) |
| [eliminarEspacio()](../4-Prototipo/0-Administrador/eliminarEspacio/eliminarEspacio.md)       | [eliminarRecorrido()](../4-Prototipo/0-Administrador/eliminarRecorrido/eliminarRecorrido.md)       |

### Diagramas detallados (Visitante) 

| Recorridos y ubicación                                                                                        | Exploración de espacios                                                                        |
| ------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- |
| [buscarEspacio()](../4-Prototipo/1-Visitante/buscarEspacio/buscarEspacio.md)                                  | [verDetalles()](../4-Prototipo/1-Visitante/verDetalles/verDetalles.md)                         |
| [cambiarDeEspacio()](../4-Prototipo/1-Visitante/cambiarDeEspacio/cambiarDeEspacio.md)                         | [verEspaciosCercanos()](../4-Prototipo/1-Visitante/verEspaciosCercanos/verEspaciosCercanos.md) |
| [verEspacio()](../4-Prototipo/1-Visitante/verEspacio/verEspacio.md)                         | [verEspaciosPlanta()](../4-Prototipo/1-Visitante/verEspaciosPlanta/verEspaciosPlanta.md)       |
| [listarRecorridos()](../4-Prototipo/1-Visitante/listarRecorridos/listarRecorridos.md) |                                                                                                |
| [seleccionarRecorrido()](../4-Prototipo/1-Visitante/seleccionarRecorrido/seleccionarRecorrido.md)             |                                                                                                |                                                                                              |

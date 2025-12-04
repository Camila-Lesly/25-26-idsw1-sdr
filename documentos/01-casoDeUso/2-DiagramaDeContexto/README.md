<div align=right>

| [![](https://img.shields.io/badge/-Inicio-FFF?style=flat&logo=Emlakjet&logoColor=black)](/README.md) [![](https://img.shields.io/badge/-commitlint-282c34?style=flat&logo=commitlint&logoColor=white)](/documentos/commits/commit-instructions.md)  [![](https://img.shields.io/badge/-Modelo_de_Dominio-FFA500?style=flat&logo=LiveChat&logoColor=white)](/documentos/00-modeloDeDominio/README.md) [![](https://img.shields.io/badge/-Actores-FFF?style=flat&logo=openstreetmap&logoColor=black)](/docs/casosDeUso/actores/README.md/) [![](https://img.shields.io/badge/-Casos_De_Uso-FFF?style=flat&logo=openstreetmap&logoColor=black)](/documentos/01-casoDeUso/1-CasoDeUso/README.md) [![](https://img.shields.io/badge/-Detallado_Casos_De_Uso-FFF?style=flat&logo=openstreetmap&logoColor=black)](/docs/casosDeUso/detalladoCasosDeUso/README.md) [![](https://img.shields.io/badge/-Diagrama_De_Contexto-FFF?style=flat&logo=openstreetmap&logoColor=black)](/documentos/01-casoDeUso/2-DiagramaDeContexto/) [![](https://img.shields.io/badge/-Prototipos-FFF?style=flat&logo=openstreetmap&logoColor=black)](/docs/casosDeUso/prototipos/README.md) [![](https://img.shields.io/badge/-Sesiones_de_Requisitado-FFF?style=flat&logo=Proton&logoColor=black)](./documentos/sesiones/)
|:-:|

</div>

# myUniverse > Requisitos > Diagrama de contexto

## Información del artefacto

- **Proyecto**: myUniverse - Mapa 3D interactivo del campus
- **Fase RUP**: Inception (Inicio)
- **Versión**: 1.0
- **Autor**: Equipo myUniverse

## Introducción

Este documento agrupa los diagramas de contexto para los actores principales de `myUniverse` (Visitante y Administrador). Los diagramas muestran los límites del sistema, actores externos y las interacciones principales, así como una visión simplificada de estados y transiciones relevantes para el diseño de la interfaz y las APIs.

## Propósito

- Mostrar el entorno y dependencias externas del sistema para cada actor
- Facilitar la identificación de entradas/salidas del sistema (API, sincronizaciones, datos de terceros)
- Servir de referencia para el diseño de pantallas y flujos de navegación
- Detectar integraciones necesarias y posibles puntos de fallo

## Diagramas de contexto

<div align="center">

|![Diagrama de Contexto - Administrador](/documentos/01-casoDeUso/2-DiagramaDeContexto/diagramaDeContextoAdministrador.png) | ![Diagrama de Contexto - Visitante](/documentos/01-casoDeUso/2-DiagramaDeContexto/diagramDeContextoVisitante.png) |
|:-:|:-:|
|Código fuente: [diagramaDeContextoAdministrador.puml](diagramaDeContextoAdministrador.puml) | Código fuente: [diagramaDeContextoVisitante.puml](diagramaDeContextoVisitante.puml) |

</div>

> Nota: si los enlaces a las imágenes no se renderizan en tu entorno, abre los archivos directamente desde `documentos/01-casoDeUso/2-DiagramaDeContexto/`.


## Referencias

- [Modelo del dominio](../00-modeloDeDominio/README.md) - Entidades y atributos principales
- [Actores y casos de uso](../0-Actores/README.md) - Listado de actores y sus responsabilidades
- Diagramas fuente en `documentos/01-casoDeUso/2-DiagramaDeContexto/`


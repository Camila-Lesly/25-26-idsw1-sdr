# Modelo de dominio

<div align=right>

| [![](https://img.shields.io/badge/-Inicio-FFF?style=flat&logo=Emlakjet&logoColor=black)](/README.md) [![](https://img.shields.io/badge/-commitlint-282c34?style=flat&logo=commitlint&logoColor=white)](/documentos/commits/commit-instructions.md)  [![](https://img.shields.io/badge/-Modelo_de_Dominio-FFA500?style=flat&logo=LiveChat&logoColor=white)](/documentos/00-modeloDeDominio/README.md) [![](https://img.shields.io/badge/-Actores-FFF?style=flat&logo=openstreetmap&logoColor=black)](/docs/casosDeUso/actores/README.md/) [![](https://img.shields.io/badge/-Casos_De_Uso-FFF?style=flat&logo=openstreetmap&logoColor=black)](/documentos/01-casoDeUso/1-CasoDeUso/README.md) [![](https://img.shields.io/badge/-Detallado_Casos_De_Uso-FFF?style=flat&logo=openstreetmap&logoColor=black)](/docs/casosDeUso/detalladoCasosDeUso/README.md) [![](https://img.shields.io/badge/-Diagrama_De_Contexto-FFF?style=flat&logo=openstreetmap&logoColor=black)](/documentos/01-casoDeUso/2-DiagramaDeContexto/) [![](https://img.shields.io/badge/-Prototipos-FFF?style=flat&logo=openstreetmap&logoColor=black)](/docs/casosDeUso/prototipos/README.md) [![](https://img.shields.io/badge/-Sesiones_de_Requisitado-FFF?style=flat&logo=Proton&logoColor=black)](./documentos/sesiones/)
|:-:|

</div>

## Información del artefacto

- **Proyecto**: myUniverse - Aplicación móvil con mapa 3D interactivo del campus
- **Fase RUP**: Inception (Inicio)
- **Versión**: 1.0
- **Fecha**: 2025-11-23
- **Autor**: Equipo myUniverse

## Introducción

Este documento describe el modelo conceptual del dominio para `myUniverse`. Define el vocabulario común y las relaciones entre las entidades que componen la aplicación: campus, edificios, aulas, servicios y puntos de interés. Está pensado para guiar el diseño de la API, la estructura de datos y los casos de uso de la aplicación móvil.

## Propósito

- Establecer un vocabulario compartido para el proyecto `myUniverse`
- Definir las entidades principales del dominio espacial y de servicios del campus
- Documentar las relaciones conceptuales entre entidades
- Servir como base para casos de uso, prototipos y la implementación del mapa 3D

## Problema que resuelve

La aplicación busca ayudar a estudiantes y visitantes a orientarse y acceder a la información del campus mediante:

1. **Localización precisa** - Mostrar posición y rutas en un mapa 3D del campus
2. **Información de espacios** - Acceder a datos de aulas, servicios y recursos disponibles
3. **Disponibilidad y eventos** - Mostrar horarios, disponibilidad y eventos en instalaciones

## Consideraciones de Diseño

### Simplicidad conceptual

- El modelo prioriza conceptos claros y reutilizables: `Edificio`, `Aula`, `Espacio`, `Planta`
- Evita detalles técnicos de renderizado 3D; define contratos y datos necesarios para la vista (coordenadas, capas, metadatos)

## Diagrama de Clases

<div align="center">

| [![Diagrama de clases](./DiagramaDeClases/diagramaDeClases.png)](./DiagramaDeClases/diagramaDeClases.png) |
|:-:|
| [Código fuente](./DiagramaDeClases/diagramaDeClases.puml) |

</div>

## Diagrama de Estados

<div align="center">

### Espacio

| [![Diagrama de estados de espacio](./DiagramaDeEstados/DdEEspacio/diagramaDeEstados.png)](./DiagramaDeEstados/DdEEspacio/diagramaDeEstados.png) |
|:-:|
| [Código fuente](./DiagramaDeEstados/DdEEspacio/diagramaDeEstados.puml) |

### Visitante

| [![Diagrama de estados de visitante](./DiagramaDeEstados/DdEVisitante/diagramaDeEstados.png)](./DiagramaDeEstados/DdEVisitante/diagramaDeEstados.png) |
|:-:|
| [Código fuente](./DiagramaDeEstados/DdEVisitante/diagramaDeEstados.puml) |

### Recorrido

| [![Diagrama de estados de recorrido](./DiagramaDeEstados/DdEspacioRecorrido/diagramaDeEstado.png)](./DiagramaDeEstados/DdEspacioRecorrido/diagramaDeEstado.png) |
|:-:|
| [Código fuente](./DiagramaDeEstados/DdEspacioRecorrido/diagramaDeEstado.uml) |

</div>

## Diagrama de Objetos

<div align="center">

| [![Diagrama de objetos](./DiagramaDeObjetos/diagramaDeObjetos.png)](./DiagramaDeObjetos/diagramaDeObjetos.png) |
|:-:|
| [Código fuente](./DiagramaDeObjetos/diagramaDeObjetos.uml) |

</div>
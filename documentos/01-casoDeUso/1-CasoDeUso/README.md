<div align=right>

| [![](https://img.shields.io/badge/-Inicio-FFF?style=flat&logo=Emlakjet&logoColor=black)](/README.md) [![](https://img.shields.io/badge/-commitlint-282c34?style=flat&logo=commitlint&logoColor=white)](/documentos/commits/commit-instructions.md)  [![](https://img.shields.io/badge/-Modelo_de_Dominio-FFA500?style=flat&logo=LiveChat&logoColor=white)](/documentos/00-modeloDeDominio/README.md) [![](https://img.shields.io/badge/-Actores-FFF?style=flat&logo=openstreetmap&logoColor=black)](/docs/casosDeUso/actores/README.md/) [![](https://img.shields.io/badge/-Casos_De_Uso-FFF?style=flat&logo=openstreetmap&logoColor=black)](/documentos/01-casoDeUso/1-CasoDeUso/README.md) [![](https://img.shields.io/badge/-Detallado_Casos_De_Uso-FFF?style=flat&logo=openstreetmap&logoColor=black)](/docs/casosDeUso/detalladoCasosDeUso/README.md) [![](https://img.shields.io/badge/-Diagrama_De_Contexto-FFF?style=flat&logo=openstreetmap&logoColor=black)](/documentos/01-casoDeUso/2-DiagramaDeContexto/) [![](https://img.shields.io/badge/-Prototipos-FFF?style=flat&logo=openstreetmap&logoColor=black)](/docs/casosDeUso/prototipos/README.md) [![](https://img.shields.io/badge/-Sesiones_de_Requisitado-FFF?style=flat&logo=Proton&logoColor=black)](./documentos/sesiones/)
|:-:|

</div>

# myUniverse - Actores y casos de uso

## Información del artefacto

- **Proyecto**: myUniverse - Aplicación móvil con mapa 3D interactivo del campus
- **Fase RUP**: Inception (Inicio)
- **Versión**: 1.0
- **Fecha**: 2025-11-28
- **Autor**: Equipo myUniverse

## Introducción

Este documento identifica los actores del sistema y sus casos de uso para `myUniverse`. Está alineado con el modelo del dominio y describe las interacciones principales entre usuarios y la aplicación móvil de mapa 3D del campus.

## Propósito

- Identificar actores que interactúan con `myUniverse`
- Definir casos de uso primarios y sus responsabilidades
- Servir de base para especificar requisitos funcionales y pruebas
- Facilitar el diseño de pantallas y la API del mapa 3D

## Diagrama

<div align=center>

|Actores y casos de uso
|:-:|
|![Actores y Casos de Uso](/documentos/01-casoDeUso/1-CasoDeUso/administradorCasoDeUso.png)
|Código fuente:[actores-casos-uso-001.puml](/documentos/01-casoDeUso/1-CasoDeUso/adminCasosDeUso.puml)
|![Actores y Casos de Uso](/documentos/01-casoDeUso/1-CasoDeUso/visitanteCasosDeUso.png)
|Código fuente: [actores-casos-uso-002.puml](/documentos/01-casoDeUso/1-CasoDeUso/visitanteCasosDeUso.puml)

</div>

## Actores identificados

|Actor|Descripción|Responsabilidades principales|
|-|-|-|
|**Visitante**|Usuario casual que explora el campus sin sesión|Buscar lugares, ver mapa, obtener rutas y ver información básica de puntos de interés|
|**Administrador**|Usuario con permisos para gestionar datos del campus|Crear/editar edificios, aulas, eventos, recursos y revisar reportes de incidencias|


## Referencias

-- [Modelo del dominio](../00-modeloDeDominio/README.md) - Base conceptual para identificación de casos de uso
-- Documentos de sesiones y decisiones del equipo (`/documentos/sesiones/`)
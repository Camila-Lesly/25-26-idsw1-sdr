# Apuntes de la sesión con Lucía Terán

**Nombre del proyecto:** `myUniverse`

## Sesión: Presentación y Aprobación del Modelo de Dominio

### Proceso de la reunión
1. **Presentamos 2 modelos de dominio distintos** al cliente:
   - **Modelo 1:** Enfoque plano (Universidad → Espacios directos)
   - **Modelo 2:** Jerarquía física completa (Universidad → Region → Planta → Espacio)

2. **Lucía evaluó ambas propuestas** detalladamente considerando:
   - Representación fiel de la **estructura física real**
   - Inclusión explícita de **pistas deportivas** y áreas externas
   - Estructura correcta para **POI vinculados a Planta**
   - Escalabilidad para **recorridos complejos futuros**

3. **APROBADO el Modelo 2** por Lucía Terán:

   |![Diagrama de Clases Aprobado](/documentos/00-modeloDeDominio/DiagramaDeClases/diagramaDeDominio.svg)|

   **Ventajas del modelo elegido:**
   - Jerarquía física real: `Universidad → Region → Planta → Espacio`
   - Flujo funcional: `Visitante → Recorrido → Espacio(N)`
   - Soporta todas las correcciones solicitadas por Lucía
   - Escalable para nuevas funcionalidades


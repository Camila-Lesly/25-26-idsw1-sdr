# Apuntes de la sesión con Lucía Terán

**Nombre del proyecto:** `myUniverse`

## Correcciones solicitadas por Lucía (cliente)

### 1. Cambio de nombre general
- El elemento principal debería llamarse **“Campus”** en lugar de “Mapa”, ya que debe englobar tanto los edificios como las áreas deportivas.

### 2. Inclusión de las pistas deportivas
- Actualmente no se representan explícitamente las **pistas deportivas**, por lo que deben añadirse al modelo.
- Podrían formar parte de la entidad `ÁreaDeportiva` o ser una entidad separada si se requiere más detalle.

### 3. Puntos de interés
- Los puntos de interés deben estar **relacionados con las aulas**:
  - Algunos pueden ser aulas que además son puntos de interés (como el **salón de actos**).  
  - Otros pueden ser espacios independientes, como la **cafetería**.
- Además, los puntos de interés deben **vincularse a la planta**, ya que forman parte de su estructura física, **no directamente al Campus**.

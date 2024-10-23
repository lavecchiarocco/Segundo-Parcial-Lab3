# Tablero de Tareas Pendientes (To-Do List)

**Descripción:**
Crea un tablero de tareas pendientes (To-Do List) utilizando solo HTML y CSS. El objetivo es diseñar una interfaz de usuario donde se puedan visualizar diferentes tareas organizadas por categorías o prioridad, con un diseño simple y claro. Aunque no tendrá funcionalidad JavaScript, el enfoque estará en la organización visual de las tareas y la creación de un layout atractivo y fácil de entender.

---

## Características del Proyecto:

### 1. Encabezado:

- Diseña un encabezado que incluya el título "Lista de Tareas" o "To-Do List", junto con un pequeño menú de navegación **opcional** (enlaces a otras secciones como "Tareas Completadas", "Nueva Tarea", "Configuraciones").
- Incluye un logotipo o ícono que refuerce el tema de la lista de tareas.

### 2. Sección de Tareas Pendientes:

- Crea una sección principal donde se mostrarán las tareas pendientes. Cada tarea debe estar dentro de una tarjeta o bloque que incluya:
  - El nombre de la tarea.
  - Un pequeño espacio para describir la tarea.
  - La fecha de vencimiento o límite de la tarea (opcional).
  - Un ícono o checkbox estilizado para marcar la tarea como pendiente (aunque no será funcional).
- Organiza las tareas en una lista vertical o en columnas (usando CSS Grid, Flexbox u otra alternativa).

### 3. Sección de Categorías o Prioridades:

- Añade una opción visual para categorizar las tareas, como:
  - **Prioridad alta**: Tareas más urgentes.
  - **Prioridad media**: Tareas importantes, pero no urgentes.
  - **Prioridad baja**: Tareas que pueden esperar.
- Puedes usar diferentes colores o estilos de borde para destacar la prioridad de cada tarea (por ejemplo, borde rojo para tareas urgentes, amarillo para media prioridad, verde para baja prioridad).

### 4. Diseño de Columnas o Tablero:

- Usa un layout de tablero con columnas para organizar las tareas de forma más clara. Cada columna puede representar un estado de la tarea (por ejemplo, "Por hacer", "En progreso", "Completadas"). Aunque no habrá funcionalidad para mover tareas entre columnas, el diseño debe permitir visualizar estos estados de manera clara.
- Utiliza CSS Grid o Flexbox para organizar las columnas y asegurarte de que el diseño sea flexible y adaptativo a diferentes tamaños de pantalla.

### 5. Sección de Tareas Completadas (Opcional):

- Añade una sección al final de la página donde se puedan listar las tareas que ya están completadas. Las tareas completadas pueden tener un diseño diferente (por ejemplo, texto tachado o con un fondo más claro) para diferenciarlas de las tareas pendientes.

### 6. Pie de Página (Opcional):

- Incluye un pie de página con enlaces a opciones adicionales, como "Ajustes", "Ayuda", o "Contacto". Puedes usar íconos o enlaces estilizados para darle un toque visual interesante.

---

## Detalles Técnicos y Recomendaciones:

### CSS Grid o Flexbox:

- Usa CSS Grid o Flexbox para organizar las tarjetas de tareas en un layout fluido y adaptativo. Esto te permitirá crear un diseño que se ajuste a diferentes tamaños de pantalla.

### Estilo de las Tareas:

- Juega con diferentes estilos de tarjeta para las tareas. Puedes agregar sombras, bordes redondeados, o efectos de hover para hacer que las tarjetas sean visualmente atractivas.
- Considera usar íconos que refuercen la acción de cada tarea (como un ícono de lápiz para editar, aunque no sea funcional).

### Colores y Tipografía:

- Elige un esquema de colores que sea agradable y fácil de leer. Puedes utilizar un esquema basado en la productividad, como colores brillantes para priorizar tareas urgentes, y colores suaves para tareas menos importantes.
- Usa tipografías legibles y asegúrate de que haya suficiente espacio entre las tareas para una lectura fácil.

### Diseño Responsivo:

- Asegúrate de que la lista de tareas se vea bien en pantallas pequeñas (Mínimo 280px). Usa media queries para reorganizar las columnas o cambiar el layout de las tareas según el tamaño de la pantalla (por ejemplo, de columnas a una lista vertical en pantallas móviles).

---

## Opciones de Personalización (Extras):

### Diseño Temático (Opcional):

- Puedes agregar diferentes temas de colores (claro, oscuro, colores pastel) que los usuarios puedan seleccionar visualmente (sin funcionalidad).

### Vista de Lista vs Vista de Tarjetas:

- Proporciona un diseño que permita mostrar las tareas en formato de lista o en formato de tarjetas más grandes, para que los usuarios puedan elegir su preferencia visual.

### Diseño de Animaciones (Opcional):

- Añade pequeñas animaciones al hacer hover sobre las tarjetas o cuando se visualicen las tareas (por ejemplo, un efecto de desvanecimiento o desplazamiento de las tarjetas en el tablero).

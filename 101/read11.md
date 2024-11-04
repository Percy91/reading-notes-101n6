### 1. ¿Qué es el DOM?

El **DOM** es una representación estructurada de un documento HTML o XML en forma de árbol de nodos, que permite a JavaScript manipular el contenido, la estructura y el estilo de una página web.

### 2. Describe brevemente la relación entre el DOM y JavaScript

JavaScript usa el DOM para acceder y modificar elementos HTML en tiempo real, permitiendo actualizaciones dinámicas en la interfaz de usuario sin recargar la página.

### 3. ¿Qué método usarías para seleccionar un elemento del DOM por su ID y cómo se utiliza?

Usa `document.getElementById("miId")` para seleccionar un elemento con un ID específico:

```javascript
const elemento = document.getElementById("miId");
```

### 4. ¿Qué método utilizarías para cambiar el color de fondo de un elemento en el DOM y cómo se implementaría?

Usaría la propiedad `style.backgroundColor` para cambiar el color de fondo:

```javascript
elemento.style.backgroundColor = "blue";
```

### 1. ¿Qué es el DOM?

El **DOM** (Document Object Model) es una interfaz de programación para documentos HTML y XML. Representa la estructura del documento como un árbol de nodos donde cada elemento del documento (etiquetas, atributos, texto) es un nodo en el árbol. Este modelo permite que los lenguajes de programación, como JavaScript, interactúen y modifiquen dinámicamente el contenido, la estructura y el estilo de la página web.

### 2. Describe brevemente la relación entre el DOM y JavaScript

JavaScript utiliza el DOM para interactuar con el contenido de una página web. A través del DOM, JavaScript puede acceder y manipular elementos HTML, sus atributos y el contenido, permitiendo actualizaciones dinámicas en la interfaz de usuario sin recargar la página. De esta manera, el DOM sirve como un puente que permite a JavaScript modificar el HTML y CSS de una página en tiempo real.

### 3. ¿Qué método usarías para seleccionar un elemento del DOM por su ID y cómo se utiliza?

Para seleccionar un elemento del DOM por su ID, se usa el método `document.getElementById()`. Este método toma como argumento el valor del atributo `id` del elemento HTML que queremos seleccionar. A continuación, un ejemplo:

```javascript
// Selecciona un elemento con el ID "miElemento" en el DOM
const elemento = document.getElementById("miElemento");
```

### 4. ¿Qué método utilizarías para cambiar el color de fondo de un elemento en el DOM y cómo se implementaría?

Para cambiar el color de fondo de un elemento en el DOM, puedes usar la propiedad `style.backgroundColor` del elemento seleccionado. Primero seleccionamos el elemento, y luego aplicamos el cambio de color de la siguiente manera:

```javascript
// Selecciona el elemento con el ID "miElemento"
const elemento = document.getElementById("miElemento");

// Cambia el color de fondo del elemento a azul
elemento.style.backgroundColor = "blue";
// Selecciona el elemento con el ID "miElemento"
const elemento = document.getElementById("miElemento");

// Cambia el color de fondo del elemento a azul
elemento.style.backgroundColor = "blue";
```

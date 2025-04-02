
## READ11 ##

**¿Qué es el DOM?**

El DOM (Document Object Model) es una interfaz que representa la estructura de un documento HTML o XML como un conjunto de objetos jerárquicos. Permite a JavaScript interactuar con el contenido, estructura y estilo de una página web, modificándola dinámicamente. Por ejemplo, puedes cambiar el texto de un elemento HTML con document.getElementById("miTitulo").innerHTML = "Nuevo título";.

**Describe brevemente la relación entre el DOM y JavaScript.**

El DOM y JavaScript están estrechamente relacionados, ya que el DOM representa la estructura de un documento HTML o XML, y JavaScript se usa para interactuar y manipular esa estructura. JavaScript puede acceder al DOM para modificar el contenido, añadir o eliminar elementos, y cambiar estilos dinámicamente, lo que permite crear páginas web interactivas y dinámicas.

**¿Qué método usarías para seleccionar un elemento del DOM por su ID y cómo se utiliza?**

Para seleccionar un elemento del DOM por su ID, se utiliza el método getElementById(). Este método devuelve el primer elemento que coincida con el ID especificado.

```javascript
let miElemento = document.getElementById("miTitulo");
miElemento.innerHTML = "Nuevo Título"; // Cambia el contenido del elemento con id "miTitulo"
```

**¿Qué método utilizarías para cambiar el color de fondo de un elemento en el DOM y cómo se implementaría?**

Para cambiar el color de fondo de un elemento en el DOM, puedes usar el método style junto con la propiedad backgroundColor. Esto permite modificar directamente el estilo en línea del elemento.


```javascript
let miElemento = document.getElementById("miDiv");
miElemento.style.backgroundColor = "lightblue"; // Cambia el fondo a color azul claro

```


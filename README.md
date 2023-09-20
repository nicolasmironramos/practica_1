# Ejercicio 1

1.- Realizar en el siguiente HTML 5 declaraciones de estilo CSS para realizar la página tal y como se muestra en la imagen utilizando display GRID.

# Ejercicio 2

EJERCICIO 1.2.1

En el archivo facilitado al alumno "la primera página Web con imagen", emplear estilos CSS para cambiar el color del fondo de la página, el color de la fuente, la familia tipográfica y el tamaño.

EJERCICIO 1.2.2.

Realiza un esquema sencillo de este documento HTML a su estructura tipo árbol, que resuma brevemente las relaciones directas entre elementos de la página, clarificando la jerarquía del árbol.

EJERCICIO 1.2.3

Construir una página HTML titulada: Secciones y líneas generales de un documento HTML5.
Deben emplearse las marcas básicas de HTML y estilos según los contenidos del módulo 1 de este curso.
Utilice el texto que aparece a continuación:
------------------------------------------------------------
Secciones y líneas generales de un documento HTML5
La especificación HTML5 trae muchos nuevos elementos a los desarrolladores web, permitiéndoles describir la estructura de un documento web con semántica estandarizada. Este documento describe estos elementos y cómo usarlos para definir el perfil de cualquier documento.
Problemas resueltos por HTML5
La definición de la estructura de un documento en HTML 4 y su algoritmo de perfilado es muy tosco y genera numerosos problemas:
1. HTML5 quita la necesidad de elementos <div> para definir secciones semánticas sin definir valores específicos para los atributos class, introduciendo un nuevo elemento, <section>, el elemento de sección HTML.
2. Mezclar varios documentos es difícil: la inclusión de un sub-documento en un documento principal. Esto se resuelve en HTML5 con los elementos de seccionado (<article>, <section>, <nav> y <aside>) son siempre subsecciones de su sección ancestra más cercana.
3. HTML5 introduce el elemento <hgroup> que oculta todos los elementos de cabecera excepto el primero de más alto rango (por ejemplo, <hgroup><h1>Justine</h1><h2>Les Malheurs de la Vertu</h2></hgroup> crea el perfil 1. Justine).
4. Un documento puede tener secciones especiales conteniendo información relacionado que no es parte del flujo principal. HTML5 introduce el elemento <aside> permitiendo a dichas secciones no ser parte del perfil principal.
5. Hay información relacionada no al documento, pero si al sitio entero, como logos, menús, tablas de contenidos, o información de derechos de autor y notas legales. Para ese propósito, HTML5 introduce tres elementos de sección específicos: <nav> para colecciones de enlaces, como una tabla de contenidos, <footer> y <header> información relacionada con el sitio.
De manera más general, HTML5 trae precisión a las características de seccionado y cabecera, permitiendo a los perfiles de documento ser predecibles y usados por el navegador para mejorar la experiencia de usuario.
El algoritmo de perfilado de HTML5
Definiendo secciones en HTML5
Todo el contenido incluido dentro del elemento <body> es parte de una sección. Las secciones en HTML5 pueden ser anidadas. Además de la sección principal, definida por el elemento <body>, los límites de la sección son definidos explícita o implícitamente. Las secciones definidas explícitamente son el contenido definido en las etiquetas <body>, <section>, <article>, <aside>, <footer>, <header>, y <nav>. Nota: Cada sección puede tener su propia jerarquía de cabeceras. Por lo tanto, incluso una sección anidada puede tener un elemento <h1>. Consulte también Definiendo cabeceras en HTML5.

1. **Crea un fichero SCSS que utilice dos variables:** una para definir un color y otra para una fuente, que se aplicarán a un párrafo. Compila y comprueba el resultado.

2. **Crea un partial que defina cuatro variables:** un color de fondo, un tamaño de fuente, un tamaño de fuente para `h1` y un color de `h1`, con valores por defecto. Importa el partial en otro archivo para que aplique las dos primeras variables a una etiqueta `body` y las dos siguientes a una etiqueta `h1`.

3. **Define una variable de nombre `ancho` y asígnale un valor**, por ejemplo `1200px`. Crea tres clases (`.mitad`, `.cuarto`, `.octavo`) que definan una anchura que sea la mitad, un cuarto y un octavo de la variable `ancho`, respectivamente. Comprueba su efecto sobre etiquetas `<div>`.

4. **Mediante el mecanismo de anidación de Sass, aplica diferentes colores y tamaños de fuente** a la lista del archivo `lista_menu.html`. Los colores debes definirlos en una lista de Sass y los tamaños de fuente en un mapa de Sass.

5. **Aplica colores a los elementos `<h1>` del `header`, al `<h2>` del `main` y al `<h4>` y `<a>` del `footer`** del archivo `ejercicio5.html` de forma anidada según Sass. Al pasar el ratón por encima del elemento `<a>`, no se subrayará.

6. **Crea una clase `.contenedor`**, en el que se defina un ancho mediante una variable. Mediante la extensión de selectores de Sass (`@extend`), crea una clase `.contenedor-con-altura`, que además de la anchura anterior, establezca una altura mediante otra variable.

7. **Crea una función en Sass llamada `partir`**. Recibirá dos parámetros (`tamaño` y `número de partes`) y devolverá un valor de anchura resultante de dividir el tamaño entre el número de partes. Para probar la función, aplícala a la propiedad `width` de una clase llamada `.décimo`.

8. **Crea un bucle con Sass para generar 10 clases**, donde cada una aplicará un color de fondo en hexadecimal dentro de una misma escala. Por ejemplo: `.color1 -> #000000`, `.color2 -> #100000`, `.color3 -> #200000`, ..., `.color10 -> #900000`.

9. **Crea un mixin `crear-grid`** que, mediante parámetros, le indiquemos el número de filas, el número de columnas y el `gap` (con valor por defecto de `20px`) que tendrá una cuadrícula grid. El tamaño de las filas y de las columnas será de `1fr`.

10. **Mediante un bucle `while`, crea 5 clases** que definan la anchura de una columna con diferentes porcentajes de la forma: `100/2%`, `100/4%`, `100/6%`, ..., Los nombres de las clases seguirán el patrón: `.ancho-col-1`, `.ancho-col-2`, `.ancho-col-3`, ...

11. **Crea tres ficheros SCSS para importarlos en el archivo `ejercicio11.scss`:**
    - `_reset.scss`: Sirve para reseteo de propiedades, aplicando `margin: 0` y `padding: 0` a `html` y `body`.
    - `_colores.scss`: Define dos colores para las variables `bodycolor` y `footercolor`.
    - `_general.scss`: Define las variables `bodyfont` y `bodysize` con los valores que quieras.

12. **Con `@extend`, crea un juego de botones.** Parte de un botón base (`.btn`) y crea variantes: `.success`, `.error`, `.warning`.

13. **Crea en Sass, mediante anidación, las siguientes clases siguiendo la metodología BEM** con los estilos que quieras:
    - `.card`
    - `.card--grid`
    - `.card__title`
    - `.card__button`
    - `.card__button--tomato`


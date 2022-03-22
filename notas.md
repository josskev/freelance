## Etiquetas más comunes en HTML

####`<link>`
Nos sirve para poder enlazar nuestro documento HTML con otro documento, como podria ser una hoja de estilos, para asi poder reutilizar esta misma hoja de estilos en diferentes páginas.

`<link rel="stylesheet" href="ubicacion-fichero-CSS">`
: Nos sirve para poder enlazar una hoja de estilos a la página html.

`<link rel="preload" href="ubicación-fichero" as="style">`
: NOs sirve para indicarle al navegador que antes de cargar cualquier otro componente nos cargue el componente que le indicamos, usualmente se usa para hacer que se cargue el CSS de manera anticipada y asi nuestro sitio web se muestra de manera correcta.

---

## Formularios

#### `<form> </form>`

Para colocar un formulario lo hacemos con la etiqueta `<form></form>`, el cual se podra dividir en diferentes secciones dentro de este segun lo que requiramos, esto lo ahrémos con la etiqueta `<fieldset></fieldset>`.

Asi mismo, existe la etiqueta `<legend></legend>`, la cual nos servira para darle un titulo a la sección del formulario correspondiente.

---

#### Etiquetas para formularios

`<label></label>`
: Se usa para introducir texto en el formulario.

`<input>`
: Se usan para obtener información de parte del usuario, hay diferentes tipos de input segun el dato que deseamos recibir, esto se hace usando el atributo `<type>` e indicando el tipo de dato:

    - **text:** Para recibir datos de tipo cadena [string]
    - **tel:** Recibe unicamente caracteres numericos [number]
    - **email:** Recibe una cadena de texto pero facilita la escritura de un correo elecrónico [string]

> Podemos colocar un texto dentro del `<input>` para indicar al usuario lo que debe colocar, el cual una vez que el usuario empieza a escribir este se borra, dicho texto se puede colocar usando el atributo: `placeholder="..."`

`<textarea></textarea>`
: Se usa para poder introducir una cantidad grande de texto.

---

## CSS
> Cascade Style Sheet (Hoja de estilo en cascada)

#### Rol de CSS
>Colores, tamaños, animaciones, espacios, margenes, adaptar diseños en diferentes dispositivios...

permite darle a tu codigo HTML un diseño único y especial en pocas lineas

#### Sintáxis de CSS

```css
p {
    atributo: valor;
}
```

#### Selectores en CSS

Se puede seleccionar solo uno o multiples elementos.

Selector de elemento
: Selecciona un elemento en base a su etiqueta, de esta forma seleccionaremos **todos** los elementos del tipo indicado.
```css
h1 {
    color: black;
}
```

Selector de clase
: Una clase es reutilizar y se puede crear multiples veces, estas inician con un punto [.]
```css
.cliente {
    color: blue;
}
```

Selector de ID
: 
# Sintaxis de markdown

Esta es la presentación de cómo hacer un MarkDown.

Sirve para las siguientes funciones:

- Que en GitHub aparezca el readme de una forma visual atractiva y sencilla de interpretar.
- Como instrucciones para que otras personas puedan ver la información vital de configuración de mi proyecto.

## ¿Qué sintaxis utiliza?

A continuación teneís una zona de código donde se podrá ver la sintáxis.:

```bash
# H1
## h2
### h3

1. Númeraciones

- listas

``` bash
```php
```js

```

### Ejemplos de zona de código en el .md

### Uno de html

```html
<h1 class="miencabezado">Hola Mundo</h1>
```

### Uno de CSS

Cómo instanciar o instalar una fuente.
1. Se debe descargar el archivo .ttf de google fonts
https://fonts.google.com/

2. Guardamos en archivo en una carpeta "fonts"

3. En el scss de config, que es el css que se usará en todas las vistas de la web, añadimos los @font-face.

```scss
@font-face {
  font-family:"roboto" ;
  src: url("../fonts/Roboto-VariableFont_wdth\,wght.ttf");
}
@font-face {
  font-family:"staatliches" ;
  src: url("../fonts/Staatliches-Regular.ttf");
}

```

## Inclusión de imágenes en el README.md

![alt text](/readme/image.png)

## Una lista

1. Hacer un archivo README.md en la raiz del proyecto

2. Hacer una carpeta para las imágenes que usemos en el readme

3. Si pego una imagen en el readme, luego cambiar la dirección de la misma teniendo en cuenta que está en una carpeta.








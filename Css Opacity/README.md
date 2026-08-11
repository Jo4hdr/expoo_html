# CSS Opacity

## ¿Qué es opacity?

`opacity` es una propiedad de CSS que sirve para cambiar el nivel de transparencia de un elemento de una página web.

El valor de `opacity` va desde `0` hasta `1`.

* `0` significa que el elemento es completamente transparente.
* `0.5` significa que tiene un nivel de transparencia intermedio.
* `1` significa que el elemento se ve completamente normal.

Por ejemplo:

```css
img {
    opacity: 0.5;
}
```

En este caso la imagen se verá más transparente.

## Ejemplo de código

Hice un ejemplo donde una imagen empieza con `opacity: 0.5` y cuando se pasa el mouse por encima cambia a `opacity: 1`.

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>CSS Opacity</title>

    <style>
        body {
            font-family: Arial;
            text-align: center;
        }

        img {
            width: 400px;
            opacity: 0.5;
        }

        img:hover {
            opacity: 1;
        }
    </style>
</head>

<body>

    <h1>Ejemplo de CSS Opacity</h1>

    <p>
        Pasa el mouse sobre la imagen para cambiar su opacidad.
    </p>

    <img src="https://www.w3schools.com/css/img_forest.jpg" alt="Bosque">

</body>
</html>
```

## ¿Qué pasa en el código?

La parte:

```css
opacity: 0.5;
```

hace que la imagen se vea transparente.

Después tenemos:

```css
img:hover {
    opacity: 1;
}
```

`hover` hace que el cambio ocurra cuando colocamos el mouse sobre la imagen. Al cambiar a `1`, la imagen vuelve a verse completamente.

## Valores de opacity

Los valores más fáciles de recordar son:

```css
opacity: 0;
```

El elemento queda completamente transparente.

```css
opacity: 0.5;
```

El elemento queda parcialmente transparente.

```css
opacity: 1;
```

El elemento queda completamente visible.

## Conclusión

`opacity` es una propiedad sencilla de CSS que permite controlar la transparencia de los elementos. También se puede combinar con `:hover` para crear efectos cuando el usuario pasa el mouse sobre un elemento.

## Fuente

W3Schools - CSS Image Transparency:

https://www.w3schools.com/css/css_image_transparency.asp

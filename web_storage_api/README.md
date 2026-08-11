# Web Storage API

## ¿Qué es?

La Web Storage API permite almacenar información directamente en el navegador mediante pares de clave y valor. A diferencia de las cookies, ofrece una forma más sencilla y con mayor capacidad para guardar datos.

## Tipos de almacenamiento

### localStorage

Guarda la información de forma permanente, incluso después de cerrar el navegador.

### sessionStorage

Guarda la información únicamente mientras la pestaña del navegador permanece abierta. Al cerrarla, los datos se eliminan.

## Métodos principales

- `setItem()` → Guarda un dato.
- `getItem()` → Obtiene un dato guardado.
- `removeItem()` → Elimina un dato.
- `clear()` → Borra todos los datos almacenados.

## ¿Para qué se utiliza?

- Guardar preferencias del usuario.
- Recordar configuraciones.
- Almacenar datos temporalmente sin utilizar cookies.

## Ejemplo

El ejemplo de esta carpeta guarda un contador utilizando **localStorage**. Cada vez que se presiona el botón, el contador aumenta y permanece guardado incluso si se recarga la página.

## Fuente

https://www.w3schools.com/html/html5_webstorage.asp
# Web Workers API

## ¿Qué es?

La Web Workers API permite ejecutar código JavaScript en segundo plano, separado de la página principal.

Esto permite que una página continúe funcionando mientras se realiza una tarea que puede requerir tiempo o procesamiento.

## ¿Para qué sirve?

Los Web Workers pueden utilizarse cuando necesitamos realizar tareas sin bloquear la interacción del usuario con la página.

Por ejemplo:

- Realizar cálculos.
- Procesar información.
- Ejecutar tareas en segundo plano.

## ¿Cómo funciona?

Un Web Worker se crea mediante JavaScript utilizando:

```javascript
new Worker("demo_workers.js")
```

El archivo JavaScript del trabajador contiene las instrucciones que se ejecutarán en segundo plano.

La comunicación entre la página y el Web Worker se realiza mediante `postMessage()` y `onmessage`.

## Ejemplo

En este ejercicio se crea un Web Worker que realiza un conteo en segundo plano. La página principal puede iniciar y detener el trabajador mediante botones.

## Fuente

https://www.w3schools.com/html/html5_webworkers.asp
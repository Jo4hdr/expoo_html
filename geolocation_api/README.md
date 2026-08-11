# Geolocation API

## ¿Qué es?

La Geolocation API permite obtener la ubicación geográfica del usuario mediante el navegador. Para proteger la privacidad, el navegador siempre solicita permiso antes de compartir la ubicación.

## ¿Cómo funciona?

La API utiliza el objeto `navigator.geolocation` para acceder a la ubicación del usuario.

El método más utilizado es:

```javascript
navigator.geolocation.getCurrentPosition()
```

Este método obtiene la posición actual del usuario y devuelve datos como:

- Latitud.
- Longitud.

## ¿Para qué se utiliza?

- Aplicaciones de mapas.
- Servicios de transporte.
- Pronóstico del clima.
- Búsqueda de lugares cercanos.

## Recomendaciones

- Verificar que el navegador sea compatible.
- Solicitar permiso al usuario.
- Implementar manejo de errores cuando la ubicación no pueda obtenerse.

## Fuente

https://www.w3schools.com/html/html5_geolocation.asp
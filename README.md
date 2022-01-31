# Curso de PWA con Recat en Platzi

Basado en el repo:
https://github.com/Aerolab/platzi-pwa

## Flujo para probar cambios en un service worker

Los services workers solo deberían testearse en producción. Esto debido al cacheo que realizan.

    npm run build && npm start

Siempre que se trabaja con services workers no olvidarse de borrar el cache del navegador en Application > Clear Storage > Clear Site Data para evitar bugs.

Hacer una recarga extra para garantizar que se hizo cache de los elementos.

Algunas veces puede requerir cerrar el navegador, borrar el cache y recargar la pagina de nuevo

Para probar que se tiene un service worker se debe probar que la pagina funcione offline. Esto En Network > Offline y hagamos una recarga.

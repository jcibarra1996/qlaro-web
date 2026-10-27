# Veredo · sitio web

Sitio de Veredo: plataformas con IA para áreas legales. Es HTML, CSS y JavaScript estático, sin dependencias ni paso de compilación.

## Estructura

- `index.html`: la página completa (estilos y script incluidos).
- `img/`: capturas reales de la plataforma, con datos de demostración.
- `video/`: video de la demo de gestión de contratos (`qlaro.mp4`) y su portada.
- `favicon.svg`: el símbolo q.

## Verlo en local

Abre `index.html` en el navegador, o sirve la carpeta:

```
npx serve .
```

## Publicarlo

Cualquier hosting estático sirve (Vercel, Netlify, GitHub Pages). En Vercel: importa el repositorio y deja la configuración por defecto, sin comando de compilación.

## Pendientes antes de publicar

- Confirmar que `contacto@veredo.com.mx` existe y recibe correo.
- El formulario arma el mensaje y abre el correo del visitante; no guarda datos. Para recibir solicitudes directamente hace falta un servicio de formularios o una función propia.

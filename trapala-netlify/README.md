# Trapala - New Sessions Man Landing Page

## Estructura del proyecto

```
trapala-netlify/
├── index.html          (Archivo principal)
├── images/             (Carpeta con imágenes en base64)
│   ├── imagen-principal.base64
│   ├── SessionsA-1.base64
│   ├── SessionsA-2.base64
│   ├── SessionsA-3.base64
│   ├── SessionsA-4.base64
│   ├── SessionsA-modal.base64
│   ├── SessionsB-1.base64
│   ├── SessionsB-2.base64
│   ├── SessionsB-3.base64
│   ├── SessionsB-modal.base64
│   ├── SessionsC-1.base64
│   ├── SessionsC-2.base64
│   ├── SessionsC-3.base64
│   ├── SessionsC-4.base64
│   └── SessionsC-modal.base64
└── README.md           (Este archivo)
```

## Cómo desplegar en Netlify

1. **Descarga esta carpeta completa** (trapala-netlify)
2. Ve a https://app.netlify.com
3. Arrastra y suelta la carpeta completa en Netlify
4. ¡Listo! Obtendrás una URL pública automática

## Características

- ✅ Landing page minimalista y elegante
- ✅ Carrusel de imágenes interactivo
- ✅ Modales de productos con información detallada
- ✅ Newsletter con modal de bienvenida
- ✅ Responsive para móviles y desktop
- ✅ Todas las imágenes incrustadas en base64

## Personalización

### Cambiar el video
En `index.html`, busca la sección `.video-section` y reemplaza el placeholder con tu video (YouTube, Vimeo, etc.)

### Actualizar enlaces de productos
En el script al final del HTML, modifica el objeto `productUrls`:
```javascript
const productUrls = {
    'a': 'tu-url-producto-a',
    'b': 'tu-url-producto-b',
    'c': 'tu-url-producto-c'
};
```

## Soporte
Para cambios o actualizaciones, contacta al equipo de desarrollo.

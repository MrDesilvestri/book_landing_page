# Landing de Eduardo Padilla

Sitio estático con React y Vite. El HTML original se conserva como página autocontenida en `public/legacy.html`, con sus imágenes extraídas a `public/assets/` para evitar duplicarlas como cadenas base64. La app React sirve esa página de forma estática.

## Desarrollo y build

```bash
npm install
npm run dev
npm run build
```

Sube el contenido de `dist/` a la raíz pública del hosting.

## Notas de revisión

El sitio original incluye catálogo, búsqueda/filtros, carrito, instrucciones de pago y contacto por WhatsApp. El modo de edición y las reseñas modifican solo el estado en memoria del navegador; no se guardan al recargar. El formulario de contacto original muestra una confirmación local sin enviar datos. El contenido y los importes se conservaron.

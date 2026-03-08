# Azalea Novias - Tema Shopify

Tema personalizado para Azalea Novias, especialistas en vestidos de novia, madrina y fiesta desde hace 36 años.

## Características

- Diseño minimalista y elegante
- Colores de marca: Blanco y dorado (#C99114)
- 5 categorías principales: Novia, Fiesta, Tallas Especiales, Complementos y Outlet
- Secciones personalizables desde el editor de Shopify
- Responsive y optimizado para móviles
- Tipografía elegante (Cormorant Garamond + Montserrat)

## Estructura

```
tema/
├── config/
│   └── settings_schema.json      # Configuración de colores y logo
├── layout/
│   └── theme.liquid               # Layout principal con navegación
├── templates/
│   ├── index.json                 # Página principal
│   ├── product.json               # Página de producto
│   ├── collection.json            # Página de colección
│   ├── page.json                  # Páginas estáticas
│   └── cart.json                  # Carrito
├── sections/
│   ├── hero.liquid                # Banner principal con imagen
│   ├── categories.liquid          # Categorías principales
│   ├── featured-products.liquid   # Productos destacados
│   ├── about.liquid               # Sección Conócenos
│   └── weddings-gallery.liquid    # Galería de bodas
├── snippets/
│   ├── product-card.liquid        # Tarjeta de producto reutilizable
│   └── icon-cart.liquid           # Icono del carrito
├── assets/
│   ├── theme.css                  # Estilos principales
│   └── theme.js                   # JavaScript
│   └── [TUS LOGOS AQUÍ]           # Añade tus logos en esta carpeta
└── locales/
    ├── en.default.json            # Traducciones inglés
    └── es.json                    # Traducciones español
```

## Instalación en Shopify

1. Sube el repositorio a GitHub
2. En tu tienda Shopify, ve a **Online Store > Themes**
3. Click en **Add theme > Connect from GitHub**
4. Selecciona este repositorio
5. Personaliza desde el Theme Editor

## Personalización

### Añadir logo
1. Coloca tu logo en la carpeta `assets/` (formatos recomendados: PNG, SVG o JPG)
2. Haz commit y push de los cambios
3. En Shopify Admin: **Online Store > Themes > Customize**
4. En la configuración del tema, sube tu logo en la sección "Logo"

### Configurar colores
Los colores se pueden ajustar desde **Theme settings > Colores** en el editor de Shopify.

### Añadir imágenes de categorías
En el Theme Editor, edita la sección "Categorías principales" y sube imágenes para cada categoría.

### Añadir fotos de bodas
En la sección "Nuestras Bodas", puedes añadir bloques de imágenes con sus descripciones.

## Colecciones necesarias

Crea estas colecciones en Shopify:
- `/collections/novia`
- `/collections/fiesta`
- `/collections/tallas-especiales`
- `/collections/complementos`
- `/collections/outlet`

## Páginas necesarias

Crea estas páginas en Shopify:
- `/pages/conocenos`
- `/pages/nuestras-bodas`
- `/pages/contacto`
- `/pages/envios`

## Soporte

Para dudas o problemas, visita azaleanovias.es

---

© 2026 Azalea Novias. Todos los derechos reservados.


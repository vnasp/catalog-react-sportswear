# Catálogo Deportivo - Tienda Delta

Sitio web tipo catálogo desarrollado para una marca de ropa deportiva enfocada en clubes amateur y torneos. Los usuarios pueden explorar productos, personalizar talla y entalle, y solicitar cotizaciones directamente desde la página.

> Nota: Proyecto realizado como trabajo freelance para un cliente.

## Vista previa

[https://vnasp.github.io/catalog-react-sportswear/](https://vnasp.github.io/catalog-react-sportswear/)

## Funcionalidades

- Catálogo dinámico con tank tops, camisetas manga larga y hoodies
- Selector de entalle, tipo, talla y cantidad
- Carrito de cotización con mínimo de 10 prendas
- Formulario de cotización con envío por email (EmailJS)
- Slider de imágenes de productos y clientes (SwiperJS)
- Botones para compartir en redes sociales
- Diseño responsive con Tailwind CSS

## Tecnologías

- React 18
- Vite
- Tailwind CSS
- Context API (estado global)
- EmailJS
- SwiperJS
- React Icons
- React Share

## Estructura del Proyecto

```
catalog-react-sportswear/
├── public/
│   └── assets/img/
├── src/
│   ├── components/
│   │   ├── CatalogForm.jsx
│   │   ├── CatalogType.jsx
│   │   ├── CatalogSize.jsx
│   │   ├── CatalogFit.jsx
│   │   ├── CatalogQuantity.jsx
│   │   ├── CartDetail.jsx
│   │   ├── CartEmpty.jsx
│   │   ├── ContactForm.jsx
│   │   ├── Cover.jsx
│   │   ├── Customers.jsx
│   │   ├── Nav.jsx
│   │   ├── Footer.jsx
│   │   └── ...
│   ├── context/
│   │   └── DataContext.jsx
│   ├── App.jsx
│   └── main.jsx
├── vite.config.js
└── package.json
```

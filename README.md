# Ramos y Detalles 🌸

Tienda virtual de **maquillaje, skincare y dulces**. Página web de un solo archivo (`index.html`) con HTML5, Tailwind CSS (CDN), FontAwesome y JavaScript vainilla.

## Características

- **Top bar** con anuncios y selector de región.
- **Header** con logo, buscador, cuenta, favoritos y carrito con contador.
- **Menú de categorías**: Maquillaje, Skincare, Dulces & Antojos, Ofertas, Catálogo.
- **Hero slider** estilo revista con CTAs.
- **Categorías circulares** (Maquillaje y Skincare) con imagen.
- **Best Sellers y Novedades** con tarjetas de producto (zoom, descuento, detalle).
- **Catálogo digital funcional**: revista hojeable con productos clickeables y detalle.
- **Carrito lateral (drawer)** con sugerencia de dulces como complemento.
- **Checkout por WhatsApp** al número de la tienda.
- **Cuentas de usuario (Club)**: registro/login con `localStorage`.
- **Favoritos por usuario**.
- **Chat de asesoría de belleza** integrado (simulado).
- **Botón flotante de WhatsApp** (solo compras).
- **Footer** con newsletter, enlaces, políticas, métodos de pago y redes.
- Diseño **responsive** (mobile first).

## 📸 Imágenes

Las imágenes van en la carpeta `images/`. Nombres esperados:

| Archivo | Uso |
|---|---|
| `logo.png` | Logo de la marca (header, menú, footer) |
| `images/cat-maquillaje.png` | Círculo de categoría Maquillaje |
| `images/cat-skincare.png` | Círculo de categoría Skincare |

> Si una imagen no existe, se muestra un respaldo automático (ícono con color) para que nunca se vea rota.

## ⚙️ Configuración

El número de WhatsApp se cambia en `index.html`, en la línea:

```js
const WHATSAPP_NUMBER = '573143085580'; // código país + número, sin + ni espacios
```

## 🚀 Ver la página

Abre `index.html` en el navegador, o publícala con GitHub Pages
(Settings → Pages → Branch: `main` → `/root`).

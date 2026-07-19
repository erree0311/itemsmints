# 🧢 ITEMSMINTS

Tienda web de **resale** (reventa de streetwear / piezas de segunda mano) — un catálogo de una sola página con productos, filtros por categoría y carrito de compras, todo en una estética editorial en blanco con acentos en rojo.

## Cómo funciona

1. Entras a la página y ves el catálogo de piezas disponibles.
2. Filtras por categoría desde la barra de filtros.
3. Agregas piezas al carrito y ves el contador actualizarse en tiempo real.

Todo corre en el navegador — no hay backend ni base de datos. Es un sitio estático de un solo archivo `index.html` (HTML + CSS + JavaScript en línea).

## Stack

- HTML + CSS + JavaScript puro (sin frameworks)
- Google Fonts (Bebas Neue, Space Mono, Syne)
- Un único archivo `index.html`

## Cómo correrlo localmente

No necesita instalación ni dependencias. Basta con abrir el archivo:

```bash
# Ábrelo directamente en el navegador
start index.html
```

O, si prefieres servirlo con un servidor local:

```bash
# Requiere Python instalado
python -m http.server 8080
```

Y abre `http://localhost:8080` en tu navegador.

## Repositorio

[github.com/erree0311/itemsmints](https://github.com/erree0311/itemsmints)

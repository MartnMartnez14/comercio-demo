# 🛒 Mercado Central — Prototipo web para comercios

Página de ejemplo de un **comercio ficticio** (supermercado mayorista y minorista), pensada para mostrar a clientes cómo puede verse la web de su negocio.

🔗 **Demo en vivo:** https://martnmartnez14.github.io/comercio-demo/

> ⚠️ Todos los datos son **ficticios**: nombre, dirección, precios y teléfono (099 123 456). Sirve solo de demostración.

## ✨ Qué incluye

- 📱 **Diseño responsive**: se ve bien en celular, tablet y PC
- 💬 **Pedidos por WhatsApp**: botones y botón flotante con mensaje ya escrito
- 🏷️ **Ofertas de la semana** con precio anterior y descuento
- 🗂️ **Categorías** de productos
- 📦 **Sección mayorista** con beneficios y estadísticas
- 🕒 **Horarios, contacto y mapa** de Google Maps integrado
- 📣 **Redes sociales**: Facebook e Instagram
- ⚡ **Liviana**: un solo archivo HTML, sin frameworks ni dependencias

## 🎨 Cómo adaptarla a un comercio real

Todo está en `index.html`:

| Qué cambiar | Dónde |
|---|---|
| Nombre y logo | `.brand-mark` y `.brand-text` en el header y el footer |
| Colores de marca | Variables `--brand`, `--brand-d` y `--brand-l` en `:root` |
| WhatsApp | Buscar y reemplazar `59899123456` |
| Redes sociales | Links `facebook.com` / `instagram.com` |
| Dirección y mapa | Sección `#ubicacion` (coordenadas del `iframe`) |
| Productos y precios | Secciones `#ofertas` y `#categorias` |

## 🚀 Verla en tu compu

Abrí `index.html` en el navegador. No hace falta instalar nada.

## 🛠️ Tecnologías

HTML5 · CSS3 (Grid, Flexbox, variables) · JavaScript vanilla · Google Fonts

---

¿Querés una web así para tu negocio? ¡Escribime! 🙌

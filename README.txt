# UrbanStep — Tienda V2

Esta versión rediseña la tienda para que se vea como una marca de calzado moderna y profesional.

## Cambios principales
- Se eliminaron por completo las categorías de niños.
- Solo existen Hombre y Mujer.
- Dos líneas de producto:
  - **Americanos:** tenis de medio uso de marcas reconocidas, aproximadamente tallas 41–45.
  - **Económicos:** tenis de muy buena calidad, en horma chica, aproximadamente tallas 35–44.
- Diseño editorial/minimalista, más limpio y coherente.
- Fotografías reales de tenis mediante imágenes externas de Pexels como demostración.
- Carrusel horizontal de destacados.
- Catálogo con filtros por Hombre, Mujer, Americanos y Económicos.
- Buscador.
- Ficha de producto con fotografía, categoría, precio y tallas.
- Selección obligatoria de talla.
- Carrito funcional.
- Pedido por WhatsApp con productos, categoría, talla y total.
- Diseño responsive para celular, tablet y PC.
- Preparado para GitHub Pages porque todo funciona desde `index.html`.

## IMPORTANTE ANTES DE PUBLICAR
Las fotografías y productos que aparecen son **demostrativos**. Para una tienda real conviene reemplazar cada URL de imagen por las fotografías reales de tu inventario y actualizar nombres, marcas, precios y tallas.

También debes cambiar en `index.html`:
`const WHATSAPP = "59170000000";`
por el número real de WhatsApp de tu tienda.

## Publicar en GitHub Pages
1. Crea un repositorio en GitHub.
2. Sube `index.html`.
3. En Settings → Pages selecciona la rama principal y la carpeta `/root`.
4. GitHub te dará la dirección pública de la tienda.

## Próxima etapa recomendada
Para convertirla en una tienda realmente completa se puede añadir:
- inventario administrable,
- fotografías propias por producto,
- cantidades disponibles por talla,
- botón de compra/reserva,
- panel de administración,
- persistencia del carrito,
- formulario de datos del cliente,
- cálculo de envío,
- integración con una base de datos,
- y eventualmente pagos en línea.

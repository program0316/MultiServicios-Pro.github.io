# MultiServicios Pro

Tienda estática en `index.html`; puedes abrir ese archivo directamente en el navegador. No requiere instalación ni servidor.

El logo está en `multiservicios-pro-logo.svg` y se muestra en la pantalla de carga, la cabecera y el pie de página.

Las doce fichas de gorras usan las fotografías subidas en `assets/gorras/` y llevan el nombre del logo/equipo más el color o tipo de modelo: New York Yankees (roja, negra, celeste, trucker rosada, trucker azul noche y rosada), Detroit Tigers D, Los Angeles Dodgers (trucker beige, beige con visera azul y denim con corazón rosado), Oakland Athletics A's y Holstein Dairy Cattle Ranch & Corral.

La sección de gorras permite solicitar por WhatsApp otros diseños; los modelos disponibles pueden variar.

La sección Suéteres muestra las camisetas existentes y detecta las fotos `small` de las carpetas de equipos dentro de `assets/sueteres/`. Los modelos nuevos se identifican por equipo y número; el filtro permite ver todos, los demás equipos o solo los modelos de mujer (Arsenal, Barcelona, Bayern Múnich y Real Madrid). Los precios no se publican: se consultan por privado. El carrito y WhatsApp indican que el precio debe confirmarse, sin calcular un total falso.

La sección Llaveros 3D y sublimables muestra diseños sencillos con logos y textos en siluetas de llaveros: marcas, autos, nombres, ambulancia, enfermería, paramédico, mascotas e iniciales, además de una taza sublimada. Los precios se consultan por privado.

La sección Suplementos no publica fotos ni precios de muestra; permite elegir proteína, creatina, pre-entreno u otro tipo y consulta por WhatsApp disponibilidad y precios.

Los métodos de pago mostrados son Yappy, transferencia bancaria y efectivo. Los datos o la coordinación se comparten al confirmar cada pedido.

Debajo de la galería hay un formulario para pedir cualquier otro equipo/modelo por WhatsApp; solicita nombre y talla, y opcionalmente nombre/número para imprimir. La personalización se marca como costo adicional a cotizar por privado.

## Antes de publicar

1. Abre `index.html` y busca `const STORE` al final del archivo.
2. El número de WhatsApp de Panamá está configurado como `50760634927`.
3. El perfil de Instagram ya está configurado como `https://www.instagram.com/multiservicios_pro507/`.
4. En el arreglo `products`, cambia nombres, descripciones, precios e imágenes de muestra por los datos reales.

El checkout prepara el mensaje con el nombre del cliente, productos y cantidades. Los artículos con precio publicado muestran subtotal; las camisetas indican consulta privada y quedan fuera del cálculo hasta confirmar su precio. El cliente revisa y envía el mensaje desde WhatsApp; esta página no cobra ni confirma automáticamente el inventario.

La sección de pedidos Temu acepta un enlace `temu.com` o `temu.to` por artículo y el nombre del cliente. Envía el enlace por WhatsApp con el aviso de que se cobra el precio vigente de Temu más USD 1 de servicio por artículo; el total se confirma antes de procesar el pedido.

Las imágenes y tipografías cargan desde internet.
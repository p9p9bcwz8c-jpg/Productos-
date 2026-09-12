VENTAS LA YOLA — PRODUCTOS

- Este ZIP usa la misma configuración Firebase de los comanderos (laptop e iPhone).
- Mantén firebase-config.js en la misma carpeta que index.html.
- Aquí puedes ver todos los productos organizados por categoría, cambiar sus
  precios, agregar productos nuevos y eliminarlos.
- Los cambios se guardan en Firebase (nodo "ventas_la_yola/productos") y se
  reflejan automáticamente en los dos comanderos (laptop e iPhone), sin
  necesidad de volver a subir esos zips.

Cómo funciona "eliminar":
- Los productos que ya venían por defecto en el menú (los que ya usan los
  comanderos) no se pueden borrar del todo, porque el comandero siempre espera
  encontrarlos — en su lugar se OCULTAN: desaparecen de las pantallas de
  Comandero, Cocina y Barra, pero el precio queda guardado por si algún día
  quieres restaurarlos (botón ↩️, activando "Ver también los productos
  ocultos").
- Los productos que agregues tú desde aquí sí se pueden eliminar por completo.

Recomendación: despliega este ZIP como un tercer sitio en Cloudflare Pages
(por ejemplo, productos.tudominio.workers.dev), conectado a su propio
repositorio de GitHub, igual que hiciste con los otros dos.

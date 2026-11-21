# Entrega C3-A2 mejorada

El ZIP contiene dos proyectos independientes, cada uno en su propia carpeta:

1. `fase-ui-pwa-personal/fase-ui-pwa/` — Perfil personal.
2. `deporzone/deporzone-pwa/` — DeporZone Canchas.

## Mejoras incluidas

### Perfil personal
- Foto de perfil incorporada desde la imagen enviada.
- Redes sociales: WhatsApp, Facebook, TikTok, Instagram y GitHub.
- Formulario de registro con nombre, apellido, celular boliviano de 8 dígitos, correo, edad y departamento.
- Validaciones estrictas y botón **Hidratar perfil** con confirmación de datos.
- Alternancia entre tema claro y oscuro.
- Estado de conexión en línea / sin conexión.
- Caché PWA actualizado para la nueva fotografía.

### DeporZone
- Fotografías de canchas generadas para esta entrega y aplicadas al catálogo.
- Tema claro/oscuro.
- Estado de conexión en línea / sin conexión.
- Formulario de reserva con nombre y apellido, celular y correo.
- Fecha mínima igual al día actual y máxima 31/12/2028.
- Datos de contacto y redes al pie de la página.
- Caché PWA actualizado para las fotografías nuevas.

## Cómo ejecutar
Para que funcionen `fetch()` y los Service Workers, ejecuta cada proyecto desde un servidor local (no abras `index.html` directamente como archivo). Por ejemplo, con VS Code usa la extensión Live Server.

## Importante
Son proyectos demostrativos: los formularios validan y guardan datos localmente cuando el código original así lo contempla. No se conectó una pasarela de pago ni una base de datos/servidor real. El estado `navigator.onLine` indica conectividad del navegador, no garantiza que un servidor externo esté disponible.

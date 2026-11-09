# PINOTRÉS CONSTRUCTORA — sitio web

Sitio web estático, responsive y listo para GitHub + Vercel.

## Probar localmente
Abre `index.html` en el navegador. Para probar como servidor local, desde esta carpeta ejecuta:
`python -m http.server 8000`
y visita `http://localhost:8000`.

## Publicar
1. Crea un repositorio nuevo en GitHub.
2. Sube el contenido de esta carpeta (no la carpeta ZIP).
3. En Vercel selecciona **Add New → Project** y conecta el repositorio.
4. Framework preset: **Other**. Build command: vacío. Output directory: `.`.
5. Deploy.

Se incluye `vercel.json` para servir la web estática y configurar rutas.

## Contenido
- `index.html`, `styles.css`, `script.js`
- `assets/`: logo, renders, plano y videos aportados.
- `PROMPT-PARA-CHATGPT.md`: prompt base editable para futuras iteraciones.

## Antes de publicar en producción
- Verificar que el mapa incrustado apunte exactamente a la sala de ventas.
- Confirmar teléfonos, dirección, disponibilidad, precios y condiciones comerciales.
- Revisar con el equipo jurídico/comercial cada texto sobre subsidios, cajas, FNA y financiación.
- Los mosaicos de cajas y bancos son identificadores tipográficos de referencia y enlaces a sus canales oficiales; no son reproducciones de sus logos oficiales.
- El formulario de opiniones es una demostración: guarda comentarios únicamente en el almacenamiento local del navegador donde se envían. Para recibir y moderar comentarios desde todos los dispositivos se debe conectar un backend/CMS o servicio de formularios.
- El tour 360 se carga desde el enlace externo existente de PINOTRÉS. Si el proveedor bloquea la inserción en iframe, el enlace directo seguirá disponible.
- El precio se omitió del cartel principal para evitar publicar una cifra que pueda cambiar. El brochure cargado muestra un precio desde COP $215 millones y referencia proyectada 135 SMMLV año 2027; confirmar vigencia antes de mostrarlo públicamente.

## Nota de proyecto
El sitio presenta ALTEZZA como proyecto destacado de PINOTRÉS, no como único contenido de la constructora. Los renders se identifican como ilustrativos y las áreas se acompañan de notas de referencia al brochure.

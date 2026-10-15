# Estudio Theiler (app web)

Un solo archivo (`index.html`) que usa Supabase. Para publicarlo:

1. Crear un repositorio PRIVADO en GitHub (github.com/new), por ejemplo `estudio-theiler`.
2. En el repositorio: "Add file" > "Upload files" y subir `index.html` y `vercel.json`.
3. En vercel.com: "Add New" > "Project" > importar ese repositorio > "Deploy" (sin cambiar nada).
4. Vercel da una dirección https://... con HTTPS: la cámara del escáner QR funciona ahí.
5. Para actualizar la app: reemplazar `index.html` en GitHub; Vercel vuelve a publicar solo.

La clave `sb_publishable_...` que aparece en el archivo es pública por diseño (los permisos reales están en la base de datos).
Nunca poner en este repositorio la contraseña de la base ni la clave `service_role`.

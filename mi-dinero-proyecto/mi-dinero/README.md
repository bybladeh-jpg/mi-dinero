# Mi Dinero — app PWA

Aplicación sencilla para registrar gastos e ingresos. Datos guardados en el navegador (localStorage), sin servidor ni cuenta.

## Incluye
- Resumen mensual y presupuesto
- Registro, edición y eliminación de gastos/ingresos
- Categorías, historial, filtros y estadísticas
- Exportación/importación JSON
- PWA instalable y caché offline

## Prueba local
Necesitas servir los archivos por HTTP (el service worker no funciona desde `file://`). Una opción es instalar Node.js y ejecutar:

```bash
npx serve .
```

Abre la URL que indique en el navegador.

## Publicar gratis con GitHub Pages
1. Crea una cuenta en GitHub si no tienes.
2. Crea un repositorio nuevo, por ejemplo `mi-dinero`.
3. Sube todos los archivos de esta carpeta a la raíz del repositorio.
4. En el repositorio abre **Settings → Pages**.
5. En Build and deployment elige **Deploy from a branch**, branch `main`, folder `/ (root)`, y Save.
6. Espera a que aparezca la URL pública HTTPS de Pages.
7. Abre esa URL en Safari en tu iPhone.
8. Pulsa Compartir → **Añadir a pantalla de inicio** → Añadir.

## Privacidad y copias
Los datos viven en el almacenamiento del navegador en ese dispositivo. No hay sincronización. Exporta una copia desde Ajustes. No borres los datos del sitio/navegador si no tienes una copia de seguridad.

## Limitaciones de esta versión
- Los datos no se sincronizan entre dispositivos.
- No es una app nativa de App Store.
- Los datos no están cifrados por la app; protege el dispositivo y sus copias.

# ARES Tracker v2

Página estática para llevar el proyecto ARES durante 60 días.

## Archivos

- `index.html`: app completa.
- La app guarda datos en el navegador con `localStorage`.
- Puede exportar JSON/CSV.
- Puede sincronizar `data/ares-datos.json` con GitHub mediante la API de GitHub.

## Instalación en GitHub Pages

1. Crea un repositorio, por ejemplo `ares-tracker`.
2. Sube `index.html`.
3. En GitHub, entra a `Settings > Pages`.
4. Publica desde la rama `main` y carpeta raíz.
5. Abre la URL que GitHub te dé.

## Almacenamiento local

No debes configurar localStorage. El navegador lo administra de forma automática por dominio.
Si abres la página desde GitHub Pages, los datos quedan guardados para ese sitio y navegador.

## Sincronización con GitHub

En la pestaña `GitHub` dentro de la app:

1. Escribe tu usuario/owner.
2. Escribe el nombre del repo.
3. Rama: normalmente `main`.
4. Ruta del archivo: `data/ares-datos.json`.
5. Pega un token de GitHub solo cuando vayas a sincronizar.
6. Presiona `Subir datos a GitHub`.

### Seguridad

No pegues tu token en el código.
No subas tu token al repo.
Usa un token con permisos mínimos para contenido del repositorio.

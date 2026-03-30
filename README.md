# assets-multimedia

Repositorio para almacenar archivos multimedia y utilizarlos como CDN.

## Estructura de carpetas

```
assets-multimedia/
├── images/    # Imágenes (PNG, JPG, JPEG, WebP, etc.)
├── icons/     # Íconos (SVG, ICO, etc.)
├── fonts/     # Fuentes tipográficas (TTF, WOFF, WOFF2, etc.)
└── videos/    # Videos (MP4, WebM, etc.)
```

## Cómo usar como CDN

### jsDelivr (recomendado)

jsDelivr sirve los archivos directamente desde GitHub con caché global:

```
https://cdn.jsdelivr.net/gh/franvozzi/assets-multimedia@main/<ruta/al/archivo>
```

**Ejemplos:**

```
https://cdn.jsdelivr.net/gh/franvozzi/assets-multimedia@main/images/logo.png
https://cdn.jsdelivr.net/gh/franvozzi/assets-multimedia@main/icons/icon.svg
https://cdn.jsdelivr.net/gh/franvozzi/assets-multimedia@main/fonts/mifuente.woff2
```

### GitHub Raw

También podés acceder directamente a través de la URL raw de GitHub:

```
https://raw.githubusercontent.com/franvozzi/assets-multimedia/main/<ruta/al/archivo>
```

**Ejemplos:**

```
https://raw.githubusercontent.com/franvozzi/assets-multimedia/main/images/logo.png
https://raw.githubusercontent.com/franvozzi/assets-multimedia/main/icons/icon.svg
```

## Cómo agregar archivos

1. Subí el archivo a la carpeta correspondiente según su tipo.
2. Hacé commit y push a la rama `main`.
3. Usá la URL del CDN que corresponda para acceder al archivo.

> **Tip:** Usá jsDelivr para mejor rendimiento, ya que tiene caché distribuida globalmente.

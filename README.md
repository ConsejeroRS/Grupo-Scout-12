# Grupo Scout No.12 — San Pedro Apóstol

Sitio web oficial del Grupo Scout No.12, Guatemala. Página única (single-file HTML) con panel de administración integrado.

## 🌐 Ver el sitio en vivo

Una vez publicado en GitHub Pages, el sitio estará disponible en:
`https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`

## 🔐 Panel de administración

Accede haciendo clic en el botón "⚙ Admin" en la barra de navegación.

- **Usuario:** `admin`
- **Contraseña:** `scout12`

> ⚠️ **Importante:** cambia esta contraseña antes de compartir el link públicamente. Búscala en `index.html` dentro de la función `doLogin()`.

## ⚠️ Cómo funciona el contenido (muy importante)

Este sitio **no tiene base de datos ni servidor**. Todo el contenido (fotos, textos, datos de contacto) vive directamente en el código del archivo `index.html`.

Esto significa:
- Los cambios que hagas desde el panel admin **se ven al instante en tu navegador**, pero...
- **No se guardan permanentemente** solo con cerrar el navegador o recargar la página.
- Para que un cambio sea visible para **todos los visitantes** del sitio publicado, ese cambio debe quedar escrito en el archivo `index.html` y subido (`git push`) a GitHub.

### Flujo recomendado para editar contenido

1. Abre el sitio (local o publicado) y entra al panel admin.
2. Haz los cambios que necesites (fotos, textos, colores, etc.) y haz clic en "Guardar".
3. Pide que se actualice el archivo `index.html` con esos mismos cambios (o edítalo directamente si sabes HTML/JS).
4. Sube el archivo actualizado a GitHub con `git add`, `git commit` y `git push`.
5. GitHub Pages se actualiza automáticamente en 1-2 minutos.

## 📁 Estructura

```
index.html   ← Todo el sitio: HTML + CSS + JS en un solo archivo
README.md    ← Este archivo
```

## 🛠 Stack

- HTML5 + CSS3 (sin frameworks)
- JavaScript vanilla
- Tipografía: Manrope (Google Fonts)
- Sin dependencias externas, sin build step — funciona directo en cualquier navegador

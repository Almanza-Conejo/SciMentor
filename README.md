# SciMentor — Landing del Mini-curso

Página web del Módulo 01 *"Cómo encontrar y evaluar el estado del arte"*, asesoría científica del **Dr. Oscar Almanza-Conejo** (Universidad de Guanajuato, DICIS).

La página es un único archivo (`index.html`) autocontenido: la mascota y los recursos gráficos van incrustados, así que no depende de imágenes externas. Solo necesitas subir ese archivo.

---

## 🚀 Cómo publicarla en GitHub Pages (gratis)

1. Crea una cuenta en [github.com](https://github.com) si aún no tienes.
2. Crea un repositorio nuevo:
   - Si lo nombras exactamente `tu-usuario.github.io`, el sitio quedará en la raíz: `https://tu-usuario.github.io`
   - Si le pones otro nombre (por ejemplo `scimentor`), quedará en: `https://tu-usuario.github.io/scimentor`
3. Dentro del repositorio, haz clic en **Add file → Upload files** y arrastra el archivo `index.html`. Confirma con **Commit changes**.
4. Ve a **Settings → Pages**. En **Source**, elige la rama `main` y la carpeta `/ (root)`. Guarda.
5. Espera 1–2 minutos. En esa misma pantalla aparecerá la dirección pública de tu sitio. ¡Listo!

> Cada vez que subas una versión nueva de `index.html`, el sitio se actualiza solo en un par de minutos.

---

## ✏️ Qué personalizar antes de lanzar

Abre `index.html` con cualquier editor de texto y busca estos dos marcadores:

### 1. El video (`VIDEO_ID`)
- Sube tu video de presentación a YouTube como **"No listado"** (unlisted).
- Copia el ID del video: en una URL como `https://www.youtube.com/watch?v=ABC123xyz`, el ID es `ABC123xyz`.
- En el archivo, reemplaza `VIDEO_ID` por ese identificador. Aparece en la línea del `<iframe>`.

### 2. El botón de pago (`REEMPLAZA-CON-TU-LINK`)
- Entra a [mercadopago.com.mx](https://www.mercadopago.com.mx) → **Cobrar → Link de pago**.
- Crea un link por **$299 MXN** con el nombre del curso.
- Copia el enlace generado (se ve como `https://mpago.la/XXXXXX`).
- En el archivo, reemplaza `https://mpago.la/REEMPLAZA-CON-TU-LINK` por tu enlace real.

> Opcional: el enlace del grupo de Telegram en el pie de página también puede actualizarse (busca el texto `Telegram`).

---

## 🎨 Identidad visual

- **Colores:** azul marino y dorado de la Universidad de Guanajuato, con acentos de la mascota (coral y azul-violeta).
- **Tipografías:** Fraunces (títulos) + Outfit (texto), cargadas desde Google Fonts.
- **Mascota:** "SciMentor", un cerebro-mentor con birrete.

---

## 📂 Estructura

```
.
├── index.html      ← la página completa (súbela a GitHub Pages)
└── README.md       ← este archivo
```

---

© SciMentor · Universidad de Guanajuato · Campus Irapuato-Salamanca (DICIS)

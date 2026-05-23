# 🌐 Portfolio Profesional Premium — Hebert Suárez Burgos

¡Bienvenido al repositorio de mi sitio web profesional! Este proyecto es un portfolio de diseño premium, moderno y responsivo, desarrollado con tecnologías web estándar para máxima velocidad y flexibilidad. Presenta mi currículum vitae interactivo, mis servicios, mi stack tecnológico de software y hardware, y se integra de forma dinámica con mis repositorios públicos de GitHub.

## 🚀 Características Principales

*   **📱 Diseño Ultra Moderno & Glassmorphism:** Interfaz oscura y elegante construida con CSS personalizado que utiliza desenfoques de vidrio, gradientes armónicos HSL, bordes semitransparentes y brillos dinámicos.
*   **🔌 Integración Dinámica con GitHub (Desplegable):** Un componente de acordeón/desplegable interactivo que, al abrirse, utiliza la API REST de GitHub para obtener y listar mis repositorios públicos en tiempo real con sus estrellas, lenguajes principales y descripciones. Cuenta con un fallback seguro si se excede el límite de consultas de la API.
*   **⌨️ Consola de Comando Interactive (Terminal Card):** Un bloque visual en el hero que imita una terminal de comandos ejecutando un `cat perfil.json`, proyectando mis datos fundamentales de forma técnica y creativa.
*   **📬 Formulario de Contacto Inteligente con Redirección a WhatsApp:** Formulario validado con HTML5 y JavaScript que recopila la información del interesado y, tras el envío, genera un mensaje personalizado y redirige al usuario directamente a mi chat de WhatsApp.
*   **🎓 Currículum Interactivo:** Página dedicada `curriculum.html` que organiza detalladamente mi formación, experiencia como docente técnico, certificaciones y habilidades en hardware/redes y desarrollo web.
*   **⚡ Rendimiento y SEO Optimizados:** Cero frameworks pesados. Carga instantánea, animaciones fluidas con `IntersectionObserver` activadas al scroll, etiquetas semánticas y configuraciones de metadatos SEO.

---

## 📂 Estructura del Proyecto

```
📁 Nueva carpeta/
│
├── 📄 index.html                # Página principal (Portfolio)
├── 📄 curriculum.html           # Currículum Vitae interactivo
├── 📄 README.md                 # Esta guía de proyecto e instalación
├── 📄 README_PERFIL_GITHUB.md   # README profesional para mi perfil de GitHub
│
├── 📁 css/
│   └── 📄 estilos.css           # Estilos personalizados premium
│
└── 📁 img/
    └── 📄 foto.jpg              # Foto de perfil extraída de mi CV
```

---

## 🛠️ Cómo Desplegar este Portfolio en GitHub Pages (Paso a Paso)

Para que cualquier persona en el mundo pueda ingresar a tu portfolio de forma directa (por ejemplo, a través de `https://hebertsb.github.io`), debes subir este código a GitHub y activar **GitHub Pages**. Sigue estos sencillos pasos:

### Paso 1: Crear un nuevo repositorio en GitHub
1. Entra a tu cuenta de GitHub (`hebertsb`).
2. Haz clic en el botón **New** (Nuevo) o ve a [github.com/new](https://github.com/new).
3. En **Repository name**, escribe el nombre que desees. Hay dos opciones:
    *   **Opción A (Recomendada - URL directa y limpia):** Nombra tu repositorio exactamente como tu usuario de GitHub seguido de `.github.io` (es decir, **`hebertsb.github.io`**). Esto hará que tu web se abra directamente al ingresar a `https://hebertsb.github.io`.
    *   **Opción B (Subdirectorio):** Nómbralo como quieras (ej. `mi-portfolio`). Tu web se abrirá en `https://hebertsb.github.io/mi-portfolio/`.
4. Asegúrate de que el repositorio sea **Public** (Público).
5. Deja las opciones de inicializar (README, .gitignore, license) desmarcadas y haz clic en **Create repository**.

### Paso 2: Subir tus archivos a GitHub
Puedes subir tus archivos usando la consola de comandos de Git o directamente desde la web de GitHub:

#### Opción Web (Sin instalar Git):
1. En la página de tu nuevo repositorio vacío, haz clic en el enlace que dice **"uploading an existing file"** (subir un archivo existente).
2. Arrastra y suelta todos los archivos de esta carpeta (`index.html`, `curriculum.html`, las carpetas `css` e `img`) en el navegador. *(Ojo: Asegúrate de arrastrar las carpetas enteras para que se mantenga la estructura).*
3. Al fondo de la página, escribe un mensaje de confirmación (ej: `Primer commit`) y haz clic en el botón verde **Commit changes** (Confirmar cambios).

#### Opción por Consola (Si usas Git en tu computadora):
Abre PowerShell o tu terminal dentro de la carpeta del proyecto y ejecuta:
```bash
# Inicializar repositorio local
git init

# Agregar todos los archivos
git add .

# Guardar los cambios localmente
git commit -m "first commit - portfolio premium"

# Crear la rama principal
git branch -M main

# Conectar tu carpeta local con el repositorio de GitHub
# (Reemplaza URL con la de tu repositorio)
git remote add origin https://github.com/hebertsb/hebertsb.github.io.git

# Subir los archivos
git push -u origin main
```

### Paso 3: Activar GitHub Pages
*(Si usaste la **Opción A** del Paso 1, este paso suele activarse automáticamente. De todas formas, verifícalo así):*

1. En la página de tu repositorio en GitHub, ve a la pestaña **Settings** (Configuración) en el menú superior derecho.
2. En la barra lateral izquierda, busca la sección **Code and automation** y haz clic en **Pages**.
3. En la sección **Build and deployment**:
    *   **Source:** Selecciona *Deploy from a branch*.
    *   **Branch:** Selecciona la rama **`main`** (o `master`) y en la carpeta contigua selecciona **`/ (root)`**.
4. Haz clic en **Save** (Guardar).

¡Listo! Espera de 1 a 2 minutos. GitHub generará tu sitio web. Verás un mensaje en verde arriba en esa misma pantalla con la URL pública: **`Your site is live at https://hebertsb.github.io/`**.

---

## 👨‍💻 Cómo Usar el README Profesional en tu Perfil de GitHub

GitHub te permite crear un README especial que se muestra en tu página de perfil principal (`github.com/hebertsb`). Para activarlo:

1. Ve a [github.com/new](https://github.com/new) para crear un nuevo repositorio.
2. En **Repository name**, escribe exactamente tu nombre de usuario en minúsculas: **`hebertsb`**.
3. Verás un mensaje especial que dice: *"You found a secret! hebertsb/hebertsb is a special repository..."*
4. Asegúrate de que el repositorio sea **Public** (Público).
5. Activa la casilla **Initialize this repository with a README**.
6. Haz clic en **Create repository**.
7. En tu nuevo repositorio, edita el archivo `README.md`, copia todo el contenido del archivo local [README_PERFIL_GITHUB.md](file:///c:/Users/USUARIO/Documents/UNIVERSIDAD/Tecnologia_Web/Practicos/roly/Nueva%20carpeta/README_PERFIL_GITHUB.md) que he creado para ti, pégalo allí y guarda los cambios (Commit).

¡Tu perfil de GitHub ahora se verá increíblemente profesional, atrayendo a clientes y reclutadores! 🚀

# Alejandro Blé Marketing — Sitio web

Sitio web personal de marca para **Alejandro Blé Marketing**: consultoría de mercadotecnia, conferencias y capacitación. Bilingüe (español e inglés), con formulario de contacto funcional.

---

## Archivos del proyecto

Estos cuatro archivos deben subirse **siempre juntos** y en la **misma carpeta**:

| Archivo | Qué es |
|---|---|
| `index.html` | Página principal en español (es la que se abre por defecto) |
| `index-en.html` | Versión en inglés |
| `logo.png` | Logo de marca (menú y marca de agua del inicio) |
| `perfil.jpg` | Foto de perfil (sección "Sobre mí") |

Las imágenes se enlazan con rutas relativas, así que si falta alguna o se cambia de carpeta, se verán rotas. Mantén los cuatro juntos.

---

## Cómo publicar en GitHub Pages

1. Entra a tu repositorio en GitHub.
2. Pulsa **Add file → Upload files**.
3. Arrastra los **cuatro archivos** (`index.html`, `index-en.html`, `logo.png`, `perfil.jpg`) y pulsa **Commit changes**.
4. Ve a **Settings → Pages**.
5. En **Source**, elige **Deploy from a branch**, selecciona la rama `main` y la carpeta `/ (root)`, y pulsa **Save**.
6. Espera uno o dos minutos. Tu sitio quedará en línea.

**Direcciones del sitio una vez publicado:**
- Español: la raíz del sitio (`.../` o `.../index.html`)
- Inglés: `.../index-en.html`

Los botones **ES / EN** del menú conectan ambas versiones automáticamente.

---

## El formulario de contacto

El formulario está conectado al servicio **Formspree** con el endpoint `https://formspree.io/f/xrevlpve`. Cada mensaje enviado llega al correo **alejandro.blemarketing@gmail.com**.

**Paso único la primera vez:** al enviar el primer mensaje desde el sitio ya publicado, Formspree manda un correo de verificación a tu Gmail. Haz clic una vez para confirmar y, a partir de ahí, todos los mensajes llegan directo a tu bandeja.

Notas:
- El plan gratuito de Formspree permite 50 envíos al mes.
- El formulario incluye protección anti-spam y un asunto automático para que identifiques los mensajes en tu bandeja.
- Si el formulario falla al probarlo en tu computadora (abriendo el archivo directamente), es normal: solo funciona cuando el sitio está publicado en línea.

---

## Cómo hacer cambios comunes

Para editar textos, abre el archivo en GitHub (o en cualquier editor de texto), haz el cambio y guarda. **Recuerda hacer el mismo cambio en `index.html` (español) y en `index-en.html` (inglés)** para que ambas versiones queden iguales.

### Cambiar la foto de perfil
Sustituye el archivo `perfil.jpg` por uno nuevo con **el mismo nombre**. Idealmente vertical (proporción 4:5, por ejemplo 1080 x 1350 px) y en formato JPG para que pese poco.

### Cambiar el logo
Sustituye `logo.png` por uno nuevo con el mismo nombre. Cuadrado y con fondo transparente o negro funciona mejor.

### Editar tus datos de contacto o redes
Busca en el archivo los enlaces de tus redes (LinkedIn, YouTube, Instagram, Facebook, TikTok). Están en la sección de contacto, cerca del final.

### Actualizar tus métricas o experiencia
Las cifras del inicio (años, audiencia, horas, franquicias) y los puestos de la sección "Actividades realizadas" son texto normal: búscalos y edítalos directamente.

---

## Identidad de marca (referencia)

- **Color principal (navy):** `#001F56`
- **Acento (ámbar):** `#E8A33D`
- **Tipografía:** Roboto (titulares en Roboto Condensed)
- **Frase de marca:** "Visible desde el día uno"
- **Contacto:** alejandro.blemarketing@gmail.com

---

## Conectar un dominio propio (opcional)

Si más adelante compras un dominio (por ejemplo `alejandroble.com`):

1. Ve a **Settings → Pages → Custom domain**.
2. Escribe tu dominio y guarda.
3. En el panel de tu proveedor de dominio, apunta los registros DNS a GitHub Pages (GitHub te muestra las instrucciones exactas).

Los botones ES / EN seguirán funcionando sin tocar nada, porque usan enlaces relativos.

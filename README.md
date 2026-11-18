# Registro Fonoaudiológico Integral · V78 (Web App & PWA)

Aplicación web clínica para historia clínica fonoaudiológica, consentimiento informado, anamnesis, catálogo de instrumentos, tamizaje, evaluación, diagnóstico, plan de intervención y evoluciones, adaptada para **celulares, tablets y escritorio**.

## Características principales

- **Diseño adaptable (Responsive) para Celulares y Tablets:**
  - Barra superior deslizable por módulos y vista desplegable de los 9 módulos.
  - Barra inferior fija de navegación rápida (`◀ Ant.` | `Módulo actual` | `🖨️ PDF` | `Sig. ▶`).
  - Controles táctiles optimizados (`44px` de alto mínimo y `16px` de fuente en móviles para evitar el auto-zoom en iOS/Android).
  - Tabla de consentimiento informado adaptable a tarjetas en pantallas pequeñas, conservando el formato de tabla de 3 columnas en impresión A4.
- **Firma táctil en pantalla (`<canvas>`):**
  - Permite firmar con el dedo o lápiz óptico (*stylus*) en el Consentimiento Informado o dejar el espacio limpio para firma manuscrita en papel.
- **Autoguardado local + Respaldo en archivo (`.json`):**
  - Guarda automáticamente el avance en el dispositivo (`localStorage`) para evitar pérdida de información si el navegador móvil se cierra o recarga en segundo plano.
  - Permite exportar e importar respaldos `.json` por paciente.
- **Instalable como App (PWA Offline):**
  - Incluye `manifest.webmanifest`, `sw.js` e `icon.svg` para instalar en la pantalla de inicio de Android, iPhone, iPad o PC y funcionar sin conexión a internet.

## Archivos del repositorio

- `index.html` — Aplicación web principal (conectada al manifiesto PWA y Service Worker).
- `manifest.webmanifest` — Configuración de instalación PWA.
- `sw.js` — Service Worker para funcionamiento offline.
- `icon.svg` — Ícono vectorial adaptable de la aplicación.
- `Instrumento_Fonoaudiologico_Digital_V78_Movil_PWA.html` — Copia portable en un único archivo.

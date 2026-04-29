---
layout: bare
title: Spanish Reader Extension - Guía del usuario
lang: es
---

# Spanish Reader - Guía del usuario

> Versión: v1.0.0

## Introducción

Spanish Reader es una extensión de navegador diseñada para estudiantes de español. Agrega anotaciones de pronunciación y marcas de división silábica a las palabras en español en páginas web y PDF, con soporte para acentos de Latinoamérica y España. Incluye un diccionario integrado offline, texto a voz con voz adaptada al acento, y funciones de traducción.

---

## Funciones principales

- **Modo página completa** — Agregar anotaciones de pronunciación a todas las palabras con un clic
- **División silábica** — Mostrar la separación de sílabas con marcas de acento (ej: "com·pu·ta·do·ra")
- **Diccionario hover** — Pasar el cursor sobre las palabras para ver definiciones, pronunciación y botón de audio; modo Diccionario, Tooltip o Desactivado
- **Lector PDF** — Lector PDF integrado con anotaciones, diccionario, voz y traducción; arrastrar y soltar, URL y detección automática
- **Acentos regionales** — Alternar entre pronunciación latinoamericana (es-419) y española (es-ES)
- **TTS español** — Voz española adaptada al acento seleccionado via Chrome TTS
- **Lectura con karaoke** — Seleccionar texto; barra de herramientas ofrece lectura y traducción; resaltado palabra por palabra
- **Traducción** — Seleccionar texto y traducir al instante con Bing o Google Traductor
- **Atajos de teclado** — Acceso rápido a funciones principales
- **Interfaz multilingüe** — Disponible en múltiples idiomas

---

## Cómo usar

### Paso 1: Instalar la extensión

Instala **Spanish Reader** desde la [Chrome Web Store](https://chromewebstore.google.com/), o cárgala en modo desarrollador.

### Paso 2: Abrir cualquier página web

Visita cualquier página con contenido en español.

### Paso 3: Activar pronunciación

Haz clic en el icono de la extensión. Activa **Activar pronunciación** y **Página completa** para anotar todas las palabras.

### Paso 4: Ver pronunciación y definiciones

Pasa el cursor sobre las palabras para ver anotaciones y definiciones. Haz clic en el icono del altavoz para escuchar la pronunciación en el acento seleccionado. La división silábica muestra la estructura (ej: "com·pu·ta·do·ra").

### Paso 5: Leer y traducir texto seleccionado

Selecciona texto español. Aparece una barra de herramientas con dos botones:
- **Leer** — Lee el texto en voz alta con resaltado palabra por palabra
- **Traducir** — Muestra una burbuja de traducción

También puedes usar el menú contextual: **Spanish Reader > Leer selección** o **Traducir selección**.

> **Consejo:** Abre el popup de la extensión para ajustar acento, modo hover, velocidad de lectura, motor de traducción y más.

---

## Modo página completa

Con el modo página completa activado, todas las palabras españolas muestran la pronunciación en estilo ruby sobre el texto. La extensión ajusta automáticamente la altura de línea para que las anotaciones sean legibles.

---

## División silábica

Cuando "Mostrar división silábica" está activado:

- Las sílabas se separan con un punto medio (·)
- La sílaba tónica se identifica según las reglas de acentuación
- Las palabras con tilde (á, é, í, ó, ú) siempre llevan el estrés en la sílaba acentuada

Esto ayuda a entender:
- Dónde colocar el énfasis al hablar
- La estructura rítmica del español
- Cómo se dividen las palabras al final de línea

---

## Diccionario hover

La extensión incluye un **diccionario español** integrado (local, offline). Modos disponibles:

| Modo | Comportamiento |
|------|----------------|
| **Diccionario** | Pronunciación + definición + botón de audio |
| **Tooltip** | Pronunciación + botón de audio (sin definiciones) |
| **Desactivado** | Sin efecto hover |

> **Consejo:** Los datos del diccionario se cargan solo cuando el modo Diccionario está activo.

---

## Lector PDF

Abre PDFs con las mismas funciones de pronunciación, diccionario, voz y traducción que en la web.

**Formas de abrir:**
- Popup → **Abrir lector PDF** → arrastrar archivo o pegar URL
- Menú contextual en enlace `.pdf` → **Abrir con Spanish Reader**
- **Detección inteligente de PDF** para redirección automática

**Funciones del lector:** Anotaciones, clic para buscar, seleccionar para leer/traducir/copiar, barra lateral con índice y miniaturas, búsqueda, temas oscuro/claro/sepia, zoom

---

## Lectura con karaoke

**Barra de herramientas** — Seleccionar texto → **Leer**; las palabras se resaltan en sincronía con el audio.

**Menú contextual** — Spanish Reader > Leer selección

**Atajo** — `Alt+Mayús+S` (Mac: `Ctrl+Mayús+S`)

> Instala voces españolas del sistema operativo para mejor calidad de audio.

---

## Traducción

**Barra de herramientas** — Seleccionar texto → **Traducir**; resultado en burbuja.

**Menú contextual** — Spanish Reader > Traducir selección

**Atajo** — `Alt+Mayús+T` (Mac: `Ctrl+Mayús+T`)

**Motores:** Bing (predeterminado) y Google; múltiples idiomas de destino. La traducción requiere internet; solo se envía el texto seleccionado cuando tú lo solicitas.

---

## Atajos de teclado

| Atajo | Mac | Acción |
|-------|-----|--------|
| `Alt+Mayús+I` | `Ctrl+Mayús+I` | Activar/desactivar anotaciones |
| `Alt+Mayús+S` | `Ctrl+Mayús+S` | Leer texto seleccionado |
| `Alt+Mayús+T` | `Ctrl+Mayús+T` | Traducir texto seleccionado |

> Personaliza en `chrome://extensions/shortcuts`.

---

## Configuración

| Ajuste | Descripción |
|--------|-------------|
| **Activar pronunciación** | Interruptor principal |
| **Página completa** | Mostrar pronunciación en todas las palabras |
| **Acento** | Elegir entre Latinoamérica y España |
| **División silábica** | Mostrar marcas de separación silábica |
| **Modo hover** | Diccionario / Tooltip / Desactivado |
| **Velocidad de lectura** | Ajustar velocidad del TTS para oraciones |
| **Motor de traducción** | Bing o Google Traductor |
| **Idioma destino** | Idioma de la traducción |
| **Detección PDF** | Redirigir automáticamente URLs de PDF |

Notas adicionales:

- **Primera vez:** Tras instalar, abre el popup para confirmar la configuración; actualiza las pestañas abiertas si las anotaciones no aparecen.
- **Rendimiento:** En artículos largos, el modo página completa procesa más texto; usa el modo Tooltip si la página se siente pesada.
- **Privacidad:** El diccionario y las anotaciones funcionan localmente; solo la traducción envía texto cuando tú la activas.

---

## Consejos para estudiantes

1. **Empieza con un párrafo** — Activa el modo página completa en un artículo corto antes de usarlo en textos largos.
2. **Combina pronunciación y audio** — Haz clic en el altavoz para palabras nuevas; la voz coincide con tu acento seleccionado.
3. **Presta atención al acento** — Las reglas de acentuación son consistentes; la sílaba tónica siempre está marcada.
4. **Estudia con PDF** — Importa materiales de clase via el lector PDF integrado.
5. **Compara acentos** — Alterna entre acentos para escuchar diferencias (ej: c/z/ll).

---

## Preguntas frecuentes

**P: ¿Por qué no funciona en algunas páginas?**  
R: Las extensiones no pueden ejecutarse en páginas internas como `chrome://`, configuración del navegador o la Chrome Web Store.

**P: ¿No aparecen anotaciones?**  
R: Intenta actualizar la página. Si se cargó antes de activar la extensión, necesita un refresh.

**P: ¿Sin sonido?**  
R: Verifica el volumen del sistema y que estén instalados los paquetes de voz en español.

**P: ¿Traducción no funciona?**  
R: Se requiere conexión a internet; intenta cambiar de motor; firewalls corporativos pueden bloquear APIs.

**P: ¿El diccionario funciona offline?**  
R: Sí. Las definiciones y datos de pronunciación son locales.

---

## Enlaces

- [Política de privacidad](../privacy-policy)
- [Soporte](../support)

---

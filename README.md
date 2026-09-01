# Autodidakta

Sistema metodológico de estudio en temas informáticos, diseñado para aprender con apoyo de IA en vez de un profesor humano — pensado para quienes aprenden mejor a su propio ritmo y a su manera.

Sirve para estudiar lenguajes de programación, programas y herramientas (ej: OpenCode, Git, Docker) o cualquier tema informático que se pueda enseñar con explicación, ejemplos y ejercicios en texto.

## Qué descargar

Este repositorio contiene **solo `autodidakta.md`** — es el único archivo que necesitas. Descárgalo (en tu navegador aparecerá como `autodidakta-main.md`) y úsalo en tu propio chat con IA.

Los demás archivos mencionados abajo (`curso-<tema>.md`, `avance-<tema>.md`, `README.md`, `Clase-0N.md`) **no están en este repo** — se generan automáticamente cuando tú usas el sistema, y quedan en tu propio proyecto o repo separado, no acá.

## Cómo descargar el archivo (paso a paso)

> Si nunca has descargado algo de GitHub, esta sección es para ti. Ya estás dentro de la página del repositorio, así que empieza directamente en el paso 1.

```
┌─────────────────────────────────────────────────────┐
│  PASO 1 — Mira arriba: el botón verde "Code" ▼     │
│                                                     │
│  En la parte de arriba de esta página hay varios    │
│  botones. Busca el que es VERDE y dice "Code".      │
│  Está a la derecha, junto a los botones de          │
│  "Star" y "Fork".                                   │
│                                                     │
│  ┌───────────┐                                      │
│  │  <> Code ▼│  ← clic aquí                         │
│  └───────────┘                                      │
└──────────────────────────┬──────────────────────────┘
                           │
                           ▼
┌─────────────────────────────────────────────────────┐
│  PASO 2 — Selecciona "Download ZIP"                │
│                                                     │
│  Se abrirá un menú desplegable. Haz clic en la      │
│  opción que dice "Download ZIP".                    │
│                                                     │
│  ┌─────────────────────────┐                        │
│  │  Open with...           │                        │
│  │  ↓                     │                        │
│  │  Codespaces            │                        │
│  │  ↓                     │                        │
│  │  Download ZIP  ← clic  │                        │
│  └─────────────────────────┘                        │
└──────────────────────────┬──────────────────────────┘
                           │
                           ▼
┌─────────────────────────────────────────────────────┐
│  PASO 3 — Se descarga un archivo .zip              │
│                                                     │
│  Tu navegador descargará un archivo comprimido.     │
│  Busca en tu carpeta "Descargas". Se verá algo      │
│  como: "autodidakta-main.zip"                       │
│                                                     │
│  💡 Ese .zip contiene el archivo que te interesa,    │
│  llamado autodidakta-main.md                        │
└──────────────────────────┬──────────────────────────┘
                           │
                           ▼
┌─────────────────────────────────────────────────────┐
│  PASO 4 — Descomprime el archivo                   │
│                                                     │
│  Haz clic DERECHO sobre el archivo .zip.           │
│  Selecciona "Extraer todo..." (Windows).            │
│  O usa "The Unarchiver" / "Archive Utility" (Mac). │
│  Se creará una carpeta con el contenido.            │
└──────────────────────────┬──────────────────────────┘
                           │
                           ▼
┌─────────────────────────────────────────────────────┐
│  PASO 5 — Busca "autodidakta-main.md"              │
│                                                     │
│  Abre la carpeta que se creó. Dentro encontrarás    │
│  varios archivos. El que necesitas se llama:        │
│                                                     │
│  📄 autodidakta-main.md                             │
│                                                     │
│  Ese es el archivo que usarás en tu chat con IA.    │
└─────────────────────────────────────────────────────┘
```

**¿En Mac o Linux?** El proceso es igual: clic derecho → "Descomprimir" / "Extract".

**¿No encuentras el archivo?** Asegúrate de haber entrado a la carpeta que se creó al descomprimir — a veces hay una carpeta dentro de otra.

### Diagrama de flujo rápido

```
Ya estás dentro del repo
        │
        ▼
Mira arriba: botón verde "Code"
        │
        ▼
Clic en "Download ZIP"
        │
        ▼
Se descarga el .zip ──► Ve a tu carpeta "Descargas"
        │
        ▼
Clic derecho ──► "Extraer todo..."
        │
        ▼
Busca: autodidakta-main.md  ✅
        │
        ▼
¡Listo! Súbelo en tu chat con IA
```

## ¿Qué hace?

`autodidakta-main.md` es el único archivo que necesitas subir. Define cómo una IA debe enseñarte: estructura de cada clase, cómo evalúa tus respuestas, cómo guarda tu avance, y las reglas generales de enseñanza (ir de a un tema a la vez, ejemplos simples antes de los reales, no avanzar con dudas importantes sin resolver, etc).

A partir de ese archivo, la IA genera automáticamente el resto por tema de estudio:

- `curso-<tema>.md` — el plan de estudios (módulos y lecciones, organizados en niveles Básico / Intermedio / Avanzado).
- `avance-<tema>.md` — tu progreso: en qué lección vas, qué dominas, qué te falta.
- `README.md` — opcional, solo si usas GitHub para ese curso. Un resumen rápido de estado (barra de progreso, nivel actual) para consultar de un vistazo. No confundir con este archivo (que estas leyendo ahora), tu README.md que se generara sera el resumen mencionado de tu avance.
- `Clase-0N.md` — opcional, el registro completo de cada clase si decides guardarlo.

## Cómo usarlo

1. Abre un chat nuevo con tu IA de preferencia.
2. Sube `autodidakta-main.md` (el archivo que descargaste).
3. Escribe **"Iniciar clase"**.
4. Si es tu primera vez, la IA te preguntará qué tema quieres estudiar, tu nombre, si usarás GitHub, y si quieres guardar el registro de cada clase.
5. Estudia la lección: explicación, ejemplos, ejercicio guiado (resuelto por la IA), espacio para dudas, y ejercicios para que tú resuelvas.
6. Responde los ejercicios. La IA evalúa y cierra con un resumen.
7. Escribe **"Cerrar clase"** y guarda los archivos actualizados que te entregue.
8. Repite desde el paso 1 en tu próxima sesión — sube los archivos actualizados junto con `autodidakta-main.md`.

## ¿Encontraste un problema o tienes una idea?

Abre un [Issue](../../issues) en este repo — es la forma más ordenada de reportar errores o sugerir mejoras, y queda visible para otros que usen el sistema. Para algo más directo, también puedes escribir a contacto@nbits.cl.

❤ Si te gusto este sistema, agrega una estreya a mi repositorio por favor.

## Créditos

Creado por **Ricardo Nieto**
🌐 www.nbits.cl
✉️ contacto@nbits.cl

Licencia: CC BY 4.0 — uso y modificación libre, se agradece mención del autor.

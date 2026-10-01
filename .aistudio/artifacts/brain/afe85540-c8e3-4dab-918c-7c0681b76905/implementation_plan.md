# Kōbō Anime Studio (工房) — Generador y Laboratorio de Personajes 2D & VTuber

Estudio integral de animación japonesa 2D concebido como un entorno de producción profesional (Production Studio), enfocado en recrear las estéticas de los estudios de animación más influyentes (MAPPA, Ufotable, Bones, Wit Studio, Toei Animation, Madhouse, CloverWorks, A-1 Pictures, David Production) y diseñar personajes virtuales/VTubers con fichas técnicas detalladas (Settei/Genga), bloques interactivos deslizables (toggle on/off), control por voz e imagen de referencia para consistencia visual entre poses y situaciones.

---

## User Review & Critical Decisions

> [!IMPORTANT] 
> Hemos integrado todas tus respuestas para estructurar la aplicación como un auténtico **Estudio de Animación Japonés**:

- **Concepto Central de Estudio de Animación**: La aplicación se llamará **Kōbō Anime Studio (工房)**, articulada en departamentos reales de producción:
  1. *Art Direction & Studio Engine*: Selector de estéticas de estudios emblemáticos (*Ufotable* con iluminación volumétrica, *MAPPA* con trazo áspero y cinematográfico, *Wit Studio* con líneas de contorno dinámicas, *Toei/Toriyama* para Daima/Super, *Bones* para secuencias de acción fluida, *Madhouse* para fantasía oscura como Overlord, *David Production* para sombreados dramáticos, *8bit* para TenSura).
  2. *Character Design & VTuber Desk*: Diseñador modular de personajes y VTubers con arquetipos base (Guerrero Shonen, Hechicero Isekai, Idol Cibernética, Asesino Cazador, Demonio/Monstruo) y modo lienzo libre.
  3. *Reference Engine (Google Flow-style Consistency)*: Anclaje de personaje generado o subido para mantener consistencia de rasgos faciales, peinado y paleta cromática a través de múltiples poses, planos de cámara y expresiones.
  4. *Genga & Settei Sheet (Ficha Técnica & Lore)*: Ficha canónica de producción completa con datos biométricos, personalidad, habilidades, vestimentas alternativas y lore narrativo con exportación en PDF/PNG.
- **Bloques Modulares con Interruptores Deslizables (Toggle Switches)**: Cada bloque (Estudio/Estilo, Situación/Escena, Expresión Facial, Ángulo de Cámara, Vestimenta, Iluminación de Estudio y Lore) dispone de un slider horizontal ergonómico (deslizar a la derecha para activar, a la izquierda para desactivar).
- **Entrada Dual (Texto + Micrófono/Voz)**: Cada bloque cuenta con dictado por voz interactivo en tiempo real y asistencia de inspiración con IA para sugerir detalles técnicos de animación (ej. "sakuga", cel-shading, chromatic aberration, rim lighting).
- **Dirección Visual Artística**: Paleta cromática inspirada en degradados azul índigo/ultramar profundo (`#0B132B`, `#1C2541`) combinados con acentos coral neón cálido (`#FF6B6B`, `#FF8E72`) y blanco pergamino de animación (`#F8FAFC`), sin píldoras genéricas ni ruido visual.

---

## 1. Overview & Core Concept

### What It Does
Kōbō Studio permite a ilustradores, creadores de contenido, streamers y aficionados al anime concebir personajes virtuales y escenas 2D con fidelidad visual a los mejores estudios de animación japonesa. Mediante un flujo de trabajo basado en bloques independientes que pueden activarse o desactivarse con conmutadores deslizables, los usuarios modulan la dirección artística, el contexto ambiental, los planos cinematográficos y la vestimenta mediante texto o voz. Además, permite fijar una imagen de referencia para generar variaciones consistentes (hoja de expresiones, poses de acción, planos de streaming) y generar una ficha de personaje (Settei) completa con biografía y trasfondo narrativo.

### Target Audience & Persona
- **Creadores de Contenido y Futuros VTubers**: Buscan materializar su avatar 2D con un diseño distintivo, múltiples expresiones de streaming (feliz, enfadado, pánico, puchero, concentración) y una ficha de lore cohesionada.
- **Fans y Guionistas de Anime/Manga**: Desean visualizar conceptos con el estilo gráfico reconocible de franquicias como *Jujutsu Kaisen, Kimetsu no Yaiba, Shingeki no Kyojin, Dragon Ball Daima, Overlord* o *Tokyo Revengers*.
- **Diseñadores de Personajes**: Requieren un generador modular rápido para iterar arquetipos de animación con indicaciones técnicas profesionales.

### Key Value
- **Control granular sin complejidad**: En lugar de redactar prompts caóticos, los bloques modulares permiten aislar variables (por ejemplo, cambiar solo la expresión o el ángulo de cámara sin perder el atuendo ni el estudio de animación).
- **Consistencia multi-escena**: Motor de referencia visual para mantener la identidad del personaje entre diferentes fotogramas.
- **Inspiración y refinamiento inteligente**: Sugerencias automáticas con IA que traducen ideas coloquiales en terminología técnica de producción de anime.

---

## 2. User Experience & Visual Design

### Key User Flows
1. **Selección de Modo & Arquetipo**:
   - El usuario entra al estudio y puede elegir comenzar con una plantilla de arquetipo curada (ej. *Cazador de Sombras estilo MAPPA*, *Paladín Celestial estilo Ufotable*, *Reencarnado Mágico estilo 8bit*, *Luchador Urbano estilo Tokyo Revengers*) o comenzar desde cero con un lienzo en blanco.
2. **Configuración de Bloques Modulares**:
   - Cada bloque (Estudio de Animación, Escena/Situación, Expresión, Ángulo/Cámara, Ropa/Atuendo, Iluminación & FX, Lore) tiene un **deslizador horizontal suave** para activarlo o desactivarlo.
   - El usuario escribe en el bloque o pulsa el botón del micrófono para dictar por voz sus preferencias.
   - Cada bloque incluye un botón *✨ Inspirar bloque* que genera variantes descriptivas con vocabulario de producción de anime.
3. **Generación & Visor Central**:
   - Al pulsar *"Generar Fotograma de Estudio"*, la obra se renderiza en alta fidelidad respetando la relación de aspecto elegida (1:1, 16:9, 9:16, 4:3, 21:9).
   - El visor ofrece zoom artístico, descarga en alta resolución y la opción de *"Fijar como Personaje Referencia"*.
4. **Modo Consistencia & Galería de Variaciones**:
   - Con el personaje anclado, se activa el modo *Multi-Pose & Expresiones*: el usuario puede generar rápidamente al mismo personaje en 4 expresiones clave (sonrisa, combate, sorpresa, chivi/divertido) o en situaciones cotidianas/dramáticas preservando su fisonomía.
5. **Ficha Técnica Settei & Lore**:
   - Pestaña de diseño de personaje con desglose de paleta de colores de cabello/ojos, rol (VTuber debut, streamer, guerrero), personalidad, vestuario principal y bloque de Lore/Trasfondo narrativo expandible.

### Visual Identity & Theme
- **Atmósfera & Estilo**: Un entorno de estudio de animación nocturno en Tokio, fusionando la seriedad de un software creativo profesional con la energía vibrante del anime contemporáneo.
- **Paleta de Colores (60-30-10)**:
  - *Neutro dominante (60%)*: Azul índigo medianoche oscuro (`#090D16`, `#0F172A`) y pizarra profunda (`#131D31`).
  - *Estructura y Paneles (30%)*: Contenedores en azul acero satinado (`#1E293B` / `#162032`) con bordes sutiles en azul escarcha (`rgba(56, 189, 248, 0.15)`).
  - *Acento de alta intención (10%)*: Degradado Coral Neón cálido (`#FF6B6B` a `#FF8E72`) y acento secundario Turquesa Eléctrico (`#38BDF8`), evocando las barras de color de postproducción de anime.
- **Tipografía**:
  - *Titulares y Rótulos de Estudio*: `Cabinet Grotesk` o `Plus Jakarta Sans` con peso semibold y tracking refinado.
  - *Cuerpo y Metadatos*: `Satoshi` / sans-serif contemporáneo legible a 13px–15px.
  - *Metadatos de Producción y Ficha Técnica*: `JetBrains Mono` con cifras tabulares (`tabular-nums`) para códigos de corte (Cut #, Scene #, Color Code).
- **Anti-Slop & Disciplina Visual**:
  - Cero píldoras decorativas estáticas; las etiquetas de metadatos se renderizan en texto limpio con separadores sutiles (`·`).
  - Interruptores deslizables con animación táctil clara: riel oscuro con botón coral/azul que se desplaza físicamente de izquierda a derecha.

---

## 3. Key Product Decisions & Trade-Offs

### Decisión 1: Arquitectura de Bloques Modulares con Interruptores Deslizables
- **Elección**: Paneles modulares desacoplados donde cada bloque tiene un estado booleano explícito (`enabled: boolean`) accionado por un switch deslizable.
- **Razón**: Permite al usuario aislar parámetros rápidamente. Si solo quiere cambiar la vestimenta manteniendo la misma pose y ángulo, apaga los bloques innecesarios o ajusta únicamente el bloque deseado.
- **Alternativas descartadas**: Un solo campo de prompt largo (provoca pérdida de control y mezclas confusas de estilos).

### Decisión 2: Consistencia de Personaje mediante Referencia Multimodal (Google Flow style)
- **Elección**: Cuando el usuario fija una imagen base, el motor backend envía dicha imagen junto con la instrucción contextual de consistencia anatómica, paleta cromática y rasgos distintivos (cabello, ojos, accesorios) al generar nuevas situaciones o expresiones.
- **Razón**: Proporciona consistencia visual inmediata sin requerir entrenamientos pesados de LoRA en servidores externos.

### Decisión 3: Dictado por Voz & Asistente de Transcripción
- **Elección**: Integración dual: compatibilidad nativa con la API de Reconocimiento de Voz del navegador (Web Speech API) para dictado instantáneo sin latencia, y soporte en backend con Gemini para transcripción y enriquecimiento de conceptos.
- **Razón**: Experiencia de dictado rápida y fluida mientras el usuario diseña en el estudio.

### Decisión 4: Arquitectura Full-Stack Segura (Vite + Server Proxy)
- **Elección**: Las llamadas a Gemini (`@google/genai`) se gestionan en rutas proxy del servidor (`/api/generate-frame`, `/api/expand-prompt`, `/api/character-lore`), protegiendo la clave de API y encapsulando los prompts de dirección artística japonesa.

---

## 4. Technical Architecture & Data Strategy

### System Architecture & Component Diagram

```
┌──────────────────────────────────────────────────────────────────────────────┐
│                            KŌBŌ ANIME STUDIO UI                              │
├──────────────────────────────────────┬───────────────────────────────────────┤
│          PANEL DE PRODUCCIÓN         │            VISOR DE FOTOGRAMAS        │
│                                      │                                       │
│ ┌──────────────────────────────────┐ │ ┌───────────────────────────────────┐ │
│ │ Top Bar: Estudio · Modo · Preset │ │ │ Canvas Central (Relación Aspecto) │ │
│ ├──────────────────────────────────┤ │ │ [ 1:1 · 16:9 · 9:16 · 4:3 · 21:9] │ │
│ │ Selector de Estudios Anime 2D    │ │ ├───────────────────────────────────┤ │
│ │ (Ufotable, MAPPA, Wit, Toei, etc)│ │ │ Controles: Zoom · Descarga ·      │ │
│ ├──────────────────────────────────┤ │ │ Anclar como Personaje Referencia  │ │
│ │ Bloques Modulares Deslizables:   │ │ └───────────────────────────────────┘ │
│ │ [ON/OFF] 🎭 Expresión Facial     │ │                                       │
│ │ [ON/OFF] 🎬 Situación / Escena   │ │ ┌───────────────────────────────────┐ │
│ │ [ON/OFF] 📐 Ángulo de Cámara     │ │ │ Galería de Consistencia & Poses   │ │
│ │ [ON/OFF] 🥋 Tipo de Vestimenta   │ │ │ [Pose 1] [Pose 2] [Exp 1] [Exp 2] │ │
│ │ [ON/OFF] 💡 Iluminación & FX     │ │ └───────────────────────────────────┘ │
│ │ [ON/OFF] 📜 Lore & Bio VTuber    │ │                                       │
│ │ (Texto + Micrófono en c/u)       │ │ ┌───────────────────────────────────┐ │
│ └──────────────────────────────────┘ │ │ Ficha Técnica Settei (Color/Datos)│ │
│                                      │ └───────────────────────────────────┘ │
└──────────────────────────────────────┴───────────────────────────────────────┘
                                       │
                         Llamadas API cliente (/api/*)
                                       ▼
┌──────────────────────────────────────────────────────────────────────────────┐
│                         EXPRESS / VITE SERVER BACKEND                        │
│                                                                              │
│  • POST /api/generate-frame       -> Gemini 3.1 Flash Image Preview          │
│  • POST /api/generate-variation   -> Gemini con Imagen de Referencia         │
│  • POST /api/inspire-block        -> Gemini 3.8 Flash (Vocabulario Sakuga)   │
│  • POST /api/generate-lore        -> Gemini 3.8 Flash (Ficha Settei)         │
│                                                                              │
│                         GoogleGenAI SDK (Server-Side)                        │
└──────────────────────────────────────────────────────────────────────────────┘
```

### Data Model & State

```ts
interface StudioStyle {
  id: string;
  name: string;
  signatureAnimes: string[];
  visualDNA: string;
  accentColor: string;
}

interface BlockField {
  id: string;
  title: string;
  enabled: boolean;
  value: string;
  suggestions: string[];
  category: 'expression' | 'situation' | 'angle' | 'outfit' | 'lighting' | 'lore';
}

interface CharacterSettei {
  name: string;
  aliasTitle: string;
  archetype: string;
  genderOrVibe: string;
  eyeColor: string;
  hairColorAndStyle: string;
  keyOutfit: string;
  personalityTraits: string[];
  loreBackstory: string;
  vtuberStreamTheme: string;
  colorPalette: string[];
}

interface GeneratedFrame {
  id: string;
  imageUrl: string;
  aspectRatio: string;
  promptSummary: string;
  studioName: string;
  createdAt: number;
  isReference: boolean;
}
```

### Key Integrations
1. **Generación de Fotogramas de Anime**:
   - Motor de síntesis visual con relación de aspecto configurable (1:1, 16:9, 9:16, 4:3, 21:9).
   - Inyección experta de estética 2D cel-shaded auténtica evitando aspectos fotorrealistas o modelos 3D genéricos.
2. **Generación con Referencia**:
   - Envío de fotograma base al backend para condicionar las siguientes generaciones respetando vestuario y facciones del personaje.
3. **Entrada de Voz**:
   - Compatibilidad directa con micrófono para rellenar cualquier bloque modular mediante habla en español o japonés.
4. **Ficha de Lore & Exportación Settei**:
   - Generación de ficha técnica oficial de estudio con formato descargable.

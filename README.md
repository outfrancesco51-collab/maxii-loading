
```
╔════════════════════════════════════════════════════════════════════════╗
║                                                                        ║
║                   🎬 MAXII STUDIO LOADING SCREEN 🎬                   ║
║                                                                        ║
║              A Modern & Advanced FiveM Loading Experience             ║
║                                                                        ║
║            💎 Professional Grade | 🚀 Production Ready                ║
║                                                                        ║
╚════════════════════════════════════════════════════════════════════════╝
```

---

## 📊 Status & Badges

![Version](https://img.shields.io/badge/version-1.0.0-blue?style=flat-square)
![License](https://img.shields.io/badge/license-Custom%20Proprietaria-red?style=flat-square)
![FiveM](https://img.shields.io/badge/FiveM-Compatible-brightgreen?style=flat-square)
![Languages](https://img.shields.io/badge/languages-5-orange?style=flat-square)
![Build](https://img.shields.io/badge/build-passing-success?style=flat-square)
![Maintenance](https://img.shields.io/badge/maintenance-active-blue?style=flat-square)
![Author](https://img.shields.io/badge/author-MAXII%20STUDIO-9b59b6?style=flat-square)
![Status](https://img.shields.io/badge/status-Production%20Ready-green?style=flat-square)

### 📜 License Information

**MAXII Loading Screen** è distribuito sotto **Licenza Proprietaria Custom**

```
═══════════════════════════════════════════════════════════════
                    CUSTOM LICENSE AGREEMENT
                   © 2026 MAXII STUDIO - All Rights Reserved
═══════════════════════════════════════════════════════════════

TERMS OF USE:
✅ ALLOWED:
   • Uso personale e privato
   • Installazione su server FiveM
   • Modifiche interne al progetto
   • Redistribuzione con attribuzione

❌ NOT ALLOWED:
   • Vendita del prodotto
   • Rimozione dell'attribuzione MAXII STUDIO
   • Uso commerciale senza accordo scritto
   • Redistribuzione come proprio lavoro

CONTACT: hello@maxii-studio.com
═══════════════════════════════════════════════════════════════
```

---

## 📑 TABLE OF CONTENTS

<details>
<summary><b>🇮🇹 ITALIAN - Indice Completo</b></summary>

- [Panoramica Tecnica](#-panoramica-tecnica)
- [Architettura Sistema](#-architettura-sistema)
- [Requisiti & Dipendenze](#-requisiti--dipendenze)
- [Installazione Avanzata](#-installazione-avanzata)
- [Configurazione Professionale](#-configurazione-professionale)
- [API Reference Sviluppatore](#-api-reference-sviluppatore)
- [Sistema CSS & Theming](#-sistema-css--theming)
- [Ottimizzazione Performance](#-ottimizzazione-performance)
- [Troubleshooting Avanzato](#-troubleshooting-avanzato)
- [Sicurezza & Best Practices](#-sicurezza--best-practices)
- [Versionamento](#-versionamento)
- [Contribuire al Progetto](#-contribuire-al-progetto)
- [Changelog](#-changelog)

</details>

<details>
<summary><b>🇬🇧 ENGLISH - Full Index</b></summary>

- [Technical Overview](#-technical-overview)
- [System Architecture](#-system-architecture)
- [Requirements & Dependencies](#-requirements--dependencies)
- [Advanced Installation](#-advanced-installation)
- [Professional Configuration](#-professional-configuration)
- [Developer API Reference](#-developer-api-reference)
- [CSS & Theming System](#-css--theming-system)
- [Performance Optimization](#-performance-optimization)
- [Advanced Troubleshooting](#-advanced-troubleshooting)
- [Security & Best Practices](#-security--best-practices)
- [Versioning](#-versioning)
- [Contributing to Project](#-contributing-to-project)
- [Changelog](#-changelog)

</details>

---

## 🌍 LINGUA | LANGUAGE

---

## 🌍 LINGUA | LANGUAGE

### 🇮🇹 ITALIANO

---

## 🔬 PANORAMICA TECNICA

**MAXII Loading Screen** è una soluzione di caricamento moderna e ottimizzata per server FiveM con architettura **event-driven** basata su:

- **NUI (Native UI)**: Interfaccia renderizzata con CEF/Chromium
- **Multilingue**: Sistema i18n dinamico con 5 lingue supportate
- **Responsive Audio**: Engine audio con sincronizzazione visuale
- **Hardware Accelerated CSS**: Animazioni GPU-optimized
- **Progressive Loading**: Barra di avanzamento in tempo reale

### 📋 Stack Tecnologico

```
┌─────────────────────────────────────┐
│  HTML5 + CSS3 + ES6+ JavaScript     │
├─────────────────────────────────────┤
│  • Media API (Audio/Video)           │
│  • DOM APIs (querySelector, classList)
│  • Event System (addEventListener)   │
│  • Animation Frame API               │
└─────────────────────────────────────┘
        ↓
┌─────────────────────────────────────┐
│  FiveM NUI Framework                │
├─────────────────────────────────────┤
│  • CEF/Chromium Renderer            │
│  • Window Focus Management           │
│  • TriggerEvent Broadcasting        │
│  • Resource Lifecycle                │
└─────────────────────────────────────┘
```

---

## 🏗️ ARCHITETTURA SISTEMA

### Diagramma dei Componenti

```
┌──────────────────────────────────────────────────────────┐
│                  Loading Screen UI                       │
├──────────────────────────────────────────────────────────┤
│                                                           │
│  ┌───────────────────────────────────────────────────┐   │
│  │              Video Background Layer               │   │
│  │  (background.mp4 @ 60fps)                         │   │
│  └───────────────────────────────────────────────────┘   │
│                                                           │
│  ┌───────────────────────────────────────────────────┐   │
│  │          Brand Logo & Effects Layer               │   │
│  │  • logoPulse animation                            │   │
│  │  • logoGlow effect (music-active)                 │   │
│  │  • Neon blur effect                               │   │
│  └───────────────────────────────────────────────────┘   │
│                                                           │
│  ┌───────────────────────────────────────────────────┐   │
│  │      Status & Text Display Layer                  │   │
│  │  • Status message (i18n)                          │   │
│  │  • Rotating tips (8 per lingua)                   │   │
│  │  • Brand tagline                                  │   │
│  └───────────────────────────────────────────────────┘   │
│                                                           │
│  ┌───────────────────────────────────────────────────┐   │
│  │      Progress & Control Layer                     │   │
│  │  • Progress bar (shimmer animation)               │   │
│  │  • Volume slider (gradient)                       │   │
│  │  • Mute button (dynamic SVG icon)                 │   │
│  │  • Language selector (5 opzioni)                  │   │
│  └───────────────────────────────────────────────────┘   │
│                                                           │
│  ┌───────────────────────────────────────────────────┐   │
│  │        Audio Controller (Background)              │   │
│  │  • Volume control (0-100%)                        │   │
│  │  • Music reactive effects                         │   │
│  │  • Auto-pause at 0%                               │   │
│  └───────────────────────────────────────────────────┘   │
│                                                           │
└──────────────────────────────────────────────────────────┘
                        ↓
        ┌───────────────────────────────┐
        │  FiveM Event System           │
        │  ┌─────────────────────────┐  │
        │  │ loadProgress (0-100)    │  │
        │  │ onClientMapStart        │  │
        │  │ Custom Events           │  │
        │  └─────────────────────────┘  │
        └───────────────────────────────┘
```

### Flusso Dati

```
User Interaction
      ↓
Event Handler
      ↓
State Update
      ↓
DOM Manipulation
      ↓
CSS Animation/Transition
      ↓
Visual Feedback
```

---

## 🔧 REQUISITI & DIPENDENZE

### Requisiti di Sistema

| Componente | Versione | Stato |
|-----------|----------|-------|
| **FiveM** | v1.0+ | ✅ Richiesto |
| **NUI** | Default | ✅ Richiesto |
| **Browser CEF** | Built-in | ✅ Automatico |
| **JavaScript** | ES6+ | ✅ Supportato |
| **HTML5** | 5+ | ✅ Supportato |
| **CSS3** | 3+ | ✅ Supportato |

### Dipendenze Esterne

```json
{
  "dependencies": "none",
  "peerDependencies": "none",
  "optionalDependencies": {
    "custom_music": "any",
    "custom_video": "any",
    "custom_logo": "any"
  }
}
```

### Risorse Richieste

```
✅ HTML5 (index.html)
✅ CSS3 (Inline in index.html)
✅ JavaScript ES6+ (Inline in index.html)
✅ Video H.264 MP4 (background.mp4)
✅ Audio MP3 (music_yt.mp3)
✅ PNG/JPEG Logo (logo.png)
✅ Lua Manifest (fxmanifest.lua)
```

---

## 📦 INSTALLAZIONE AVANZATA

### Metodo 1: Installazione Standard

```bash
# 1. Clona o scarica il repository
git clone https://github.com/maxii-studio/maxii-loading.git

# 2. Sposta nella cartella resources
mv maxii-loading resources/maxii_loading

# 3. Aggiungi al server.cfg
echo "ensure maxii_loading" >> server.cfg

# 4. Riavvia il server
# restart
```

### Metodo 2: Download rapido tramite cURL

```bash
# Scarica l'ultima release direttamente nella cartella resources tramite cURL
mkdir -p resources/maxii_loading
curl -L https://github.com/outfrancesco51-collab/maxii-loading/archive/refs/heads/main.zip -o maxii_loading.zip
unzip maxii_loading.zip -d resources/
mv resources/maxii-loading-main/* resources/maxii_loading/
rm -rf resources/maxii-loading-main maxii_loading.zip

# Aggiungi al server.cfg
echo "ensure maxii_loading" >> server.cfg
```

### Metodo 3: Setup Automatizzato (PowerShell)

```powershell
# Per Windows
$resourcePath = "resources\maxii_loading"
if (Test-Path $resourcePath) {
    Write-Host "✅ Risorsa già presente"
} else {
    Write-Host "📦 Scaricando risorsa..."
    # Download logic here
}
```

### Metodo 3: Setup Docker

```dockerfile
FROM fivem/base:latest

COPY maxii_loading /opt/server/resources/maxii_loading

ENV FIVEM_LOADING_SCREEN="maxii_loading"
```

### Post-Installazione Checklist

- [ ] Cartella risorsa nella corretta posizione (`resources/maxii_loading/`)
- [ ] File `fxmanifest.lua` presente e valido
- [ ] File `index.html` presente
- [ ] File audio e video presenti o personalizzati
- [ ] Riga `ensure maxii_loading` in `server.cfg`
- [ ] Permessi lettura/scrittura corretti
- [ ] Server riavviato correttamente
- [ ] Loading screen appare all'avvio

---

## ⚙️ CONFIGURAZIONE PROFESSIONALE

### Schema JSON - Configurazione Avanzata

```json
{
  "metadata": {
    "name": "MAXII Loading Screen",
    "version": "1.0.0",
    "description": "Professional FiveM Loading Screen"
  },
  "ui": {
    "position": "fullscreen",
    "resolution": "adaptive",
    "scaling": "responsive"
  },
  "multimedia": {
    "video": {
      "enabled": true,
      "source": "background.mp4",
      "autoplay": true,
      "loop": true,
      "muted": true,
      "fps": 60,
      "quality": "1080p"
    },
    "audio": {
      "enabled": true,
      "source": "music_yt.mp3",
      "autoplay": false,
      "volume": 0.15,
      "loop": true,
      "format": "mp3"
    },
    "logo": {
      "source": "logo.png",
      "width": "200px",
      "height": "200px",
      "animation": "logoPulse"
    }
  },
  "localization": {
    "default": "it",
    "supported": ["it", "en", "fr", "de", "ja"],
    "fallback": "en",
    "rtl": false
  },
  "effects": {
    "animations": {
      "logoPulse": { "duration": "2s", "easing": "ease-in-out" },
      "logoGlow": { "duration": "0.6s", "easing": "ease-in-out" },
      "statusPulse": { "duration": "1.5s", "easing": "ease-in-out" },
      "shimmer": { "duration": "2s", "easing": "linear" },
      "musicActive": { "duration": "0.6s", "easing": "ease-in-out" }
    },
    "transitions": {
      "default": "0.3s ease-in-out",
      "progress": "0.2s linear",
      "language": "0.4s ease"
    }
  },
  "performance": {
    "hardwareAcceleration": true,
    "fps_target": 60,
    "memory_limit": "256MB",
    "render_optimization": true
  },
  "accessibility": {
    "screenReaderSupport": true,
    "highContrastMode": false,
    "keyboardNavigation": true
  }
}
```

### Variabili CSS Personalizzabili

```css
/* Colori Primari */
--color-primary: #2563eb;
--color-secondary: #1e40af;
--color-accent: #3b82f6;
--color-success: #10b981;
--color-warning: #f59e0b;
--color-danger: #ef4444;

/* Dimensioni */
--size-xs: 0.25rem;
--size-sm: 0.5rem;
--size-md: 1rem;
--size-lg: 1.5rem;
--size-xl: 2rem;

/* Tipografia */
--font-sans: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
--font-mono: 'Monaco', 'Courier New', monospace;
--font-size-base: 16px;
--line-height-normal: 1.5;

/* Effetti */
--blur-sm: 4px;
--blur-md: 8px;
--blur-lg: 12px;
--glow-color: #3b82f6;
--glow-intensity: 0.8;
```

### Come Modificare Variabili

```html
<!-- In index.html, modifica la sezione <style> -->
<style>
  :root {
    --color-primary: #YOUR_COLOR;
    --glow-color: #YOUR_GLOW;
  }
</style>
```

---

## 🔨 API REFERENCE SVILUPPATORE

### Oggetti Globali Disponibili

```javascript
// ELEMENTOS DEL DOM
window.bgVideo              // <video> background element
window.bgMusic              // <audio> music element
window.volumeSlider         // <input type="range"> volume
window.volumeValue          // <span> volume display
window.muteButton           // <button> mute toggle
window.languageSelect       // <select> language selector
window.statusText           // <div> status display
window.tipText              // <div> tips display
window.brandTag             // <span> brand tagline
window.brandLogo            // <img> logo element
window.progressFill         // <div> progress bar
```

### Funzioni Principali

```javascript
// Cambio Lingua
updateLanguage(code)
// code: 'it', 'en', 'fr', 'de', 'ja'
// Aggiorna tutti i testi visibili

// Controllo Audio
startMusic()                // Avvia la musica
function volumeControl()    // Handler volume change
function muteToggle()       // Toggle mute

// Animazioni Effetti
progressBar.classList.add('music-active')
brandLogo.classList.add('music-active')

// Gestione Stato
musicStoppedByUser          // boolean flag
```

### Event Listeners FiveM

```javascript
// Ascolto evento caricamento
on('loadProgress', (progress) => {
  progressFill.style.width = (progress * 100) + '%';
});

// Evento di chiusura
on('stopLoadingScreen', () => {
  // Cleanup logic
});

// Evento inizializzazione
on('onClientMapStart', () => {
  startMusic();
});
```

### Estensioni Personalizzate

```javascript
// Aggiungere nuovo linguaggio
const newLanguageMessages = {
  loading: "Caricamento in corso...",
  status: "Status personalizzato",
  tip: "Suggerimento personalizzato"
};
messages.push(newLanguageMessages);

// Aggiungere effetto personalizzato
const customStyle = document.createElement('style');
customStyle.textContent = `
  @keyframes customGlow {
    0% { opacity: 0.8; }
    50% { opacity: 1; }
    100% { opacity: 0.8; }
  }
  .custom-effect { animation: customGlow 1s ease-in-out infinite; }
`;
document.head.appendChild(customStyle);
```

---

## 🎨 SISTEMA CSS & THEMING

### Architettura CSS

```
┌─ Base Styles (Reset, Typography)
├─ Component Styles (Video, Logo, Progress)
├─ Layout Styles (Positioning, Grid)
├─ Animation Styles (@keyframes)
├─ Theme Styles (Colors, Gradients)
└─ Utility Styles (Utils, Helpers)
```

### Animazioni Disponibili

| Animazione | Durata | Trigger | Uso |
|-----------|--------|---------|-----|
| `logoPulse` | 2s | Inizio schermata | Logo pulsante |
| `logoGlow` | 0.6s | Musica start | Effetto blu neon |
| `statusPulse` | 1.5s | Continuo | Testo pulsante |
| `shimmer` | 2s | Continuo | Barra loading |
| `musicActive` | 0.6s | Musica start | Effetto luminoso |

### Tema Scuro vs Chiaro

```css
/* Tema Scuro (Default) */
:root {
  --bg-primary: #0f172a;
  --text-primary: #ffffff;
  --glow-color: #3b82f6;
}

/* Tema Chiaro (Alternativo) */
[data-theme="light"] {
  --bg-primary: #ffffff;
  --text-primary: #1e293b;
  --glow-color: #1e40af;
}
```

### Come Creare Tema Personalizzato

```html
<style>
  /* Sovrascrivi variabili CSS */
  :root {
    --color-primary: #8b5cf6;  /* Purple */
    --glow-color: #8b5cf6;
    --color-accent: #a78bfa;
  }
</style>
```

---

## ⚡ OTTIMIZZAZIONE PERFORMANCE

### Best Practices

```javascript
// ✅ BUONO: Usa classList per animazioni
element.classList.add('music-active');

// ❌ CATTIVO: Manipola style direttamente per animazioni
element.style.animation = 'glow 0.6s ease-in-out';

// ✅ BUONO: Event delegation
document.addEventListener('change', (e) => {
  if (e.target === languageSelect) { /* ... */ }
});

// ❌ CATTIVO: Multiple listeners
languageSelect.addEventListener('change', handler1);
languageSelect.addEventListener('change', handler2);

// ✅ BUONO: Debounce per input frequenti
const debounce = (fn, delay) => {
  let timer;
  return (...args) => {
    clearTimeout(timer);
    timer = setTimeout(() => fn(...args), delay);
  };
};

// ✅ BUONO: RequestAnimationFrame per animazioni
requestAnimationFrame(() => {
  progressFill.style.width = value + '%';
});
```

### Profiling & Monitoring

```javascript
// Misurare performance
console.time('loadResource');
// ... codice ...
console.timeEnd('loadResource');

// Monitorare frame rate
let frameCount = 0;
setInterval(() => {
  console.log(`FPS: ${frameCount}`);
  frameCount = 0;
}, 1000);
requestAnimationFrame(() => { frameCount++; });
```

### Memoria & Resource Management

| Risorsa | Limite | Stato |
|---------|--------|-------|
| **Memory** | 256MB | ⚠️ Monitor |
| **CPU Usage** | <15% | ✅ Tipico |
| **GPU Load** | 5-10% | ✅ Basso |
| **Network** | ~50MB | ✅ Una sola volta |

---

## 🐛 TROUBLESHOOTING AVANZATO

### Problema: Audio non parte automaticamente

**Diagnostica:**
```javascript
// Controlla console (F12)
console.log(bgMusic);  // Deve mostrare elemento <audio>
console.log(bgMusic.src);  // Deve mostrare percorso file
```

**Soluzioni:**
```javascript
// 1. CEF autoplay policy
// FiveM permette autoplay in NUI, verifica percorso file

// 2. Aggiungi fallback
bgMusic.play().catch(error => {
  console.error('Autoplay fallito:', error);
  console.log('Aspettando interazione utente...');
});

// 3. Aggiungi click handler
document.addEventListener('click', () => {
  bgMusic.play().catch(console.error);
});
```

### Problema: Effetti glow non visibili

**Diagnostica:**
```javascript
console.log('brandLogo:', brandLogo);
console.log('Classi applicate:', brandLogo?.classList);
console.log('Stile computato:', getComputedStyle(brandLogo));
```

**Soluzioni:**
```javascript
// Verifica CSS sia caricato
const styles = document.styleSheets;
console.log('Fogli stile caricati:', styles.length);

// Forza ridisegno
brandLogo.offsetHeight; // Trigger reflow
brandLogo.classList.add('music-active');
```

### Problema: Performance scarse (FPS bassi)

**Monitoraggio:**
```javascript
// Profilo di caricamento
performance.mark('start');
// ... operazione ...
performance.mark('end');
performance.measure('duration', 'start', 'end');
console.log(performance.getEntriesByType('measure'));
```

**Ottimizzazione:**
```javascript
// Disable VSsync temporaneamente durante animazioni intensive
// Riduci shader effects nel CSS
// Ottimizza video: comprimi 1080p → 720p
// Riduci frame rate video: 60fps → 30fps
```

### Problema: Testo non cambia con lingua

**Debug:**
```javascript
console.log('Lingua selezionata:', languageSelect.value);
console.log('Array messaggi disponibili:', messages);
console.log('Testo status:', statusText.textContent);
```

**Soluzione:**
```javascript
// Verifica array linguaggi
if (!messages[languageSelect.value]) {
  console.error('Lingua non trovata, fallback a EN');
  updateLanguage('en');
}
```

### Verifica Generale Sistema

```bash
# Check FiveM server logs
tail -f server.log | grep "maxii_loading\|LoadingScreen"

# Check browser console
# F12 → Console tab
# Cerca errori in rosso
```

---

## 🔐 SICUREZZA & BEST PRACTICES

### Validazione Input

```javascript
// ✅ Valida linguaggio prima di usare
const VALID_LANGUAGES = ['it', 'en', 'fr', 'de', 'ja'];
function updateLanguage(code) {
  if (!VALID_LANGUAGES.includes(code)) {
    console.warn('Lingua non valida:', code);
    code = 'en';
  }
  // Procedi con lingua validata
}

// ✅ Valida volume
if (volume >= 0 && volume <= 1) {
  bgMusic.volume = volume;
}
```

### XSS Prevention

```javascript
// ❌ CATTIVO: Usa innerHTML per testo dinamico
statusText.innerHTML = userInput;

// ✅ BUONO: Usa textContent per testo
statusText.textContent = userInput;

// ✅ BUONO: Sanitizza se serve HTML
function sanitize(html) {
  const div = document.createElement('div');
  div.textContent = html;
  return div.innerHTML;
}
```

### Protezione Risorsa

```lua
-- fxmanifest.lua - Limitazioni di accesso
fx_version 'cerulean'
game 'gta5'

author 'MAXII Studio'
description 'Professional Loading Screen'
version '1.0.0'

-- Solo come loading screen
loadingScreenScript 'index.html'

-- Nessun server code, asset server safe
```

### Rate Limiting

```javascript
// Evita spam di eventi
let lastEventTime = 0;
const MIN_INTERVAL = 100; // ms

function handleFrequentEvent() {
  const now = Date.now();
  if (now - lastEventTime < MIN_INTERVAL) return;
  lastEventTime = now;
  // Procedi
}
```

---

## 📦 VERSIONAMENTO

### Semantic Versioning

```
MAXII Loading Screen v1.0.0
                    │ │ │
                    │ │ └─ PATCH: Bug fixes (1.0.0 → 2.1.1)
                    │ └──── MINOR: Features (1.0.0 → 2.2.0)
                    └─────── MAJOR: Breaking changes (1.0.0 → 3.0.0)
```

### Cronologia Versioni

| Versione | Data | Note |
|----------|------|------|
| **1.0.0** | 2026-01 | ✅ Music effects, fix audio |
| **2.0.0** | 2025-12 | ✅ 5-language support |
| **1.5.0** | 2025-11 | ✅ GitHub Actions CI/CD |
| **1.0.0** | 2025-10 | ✅ Initial release |

### Politica Update

- **Patch Updates**: Automatici, bug fixes
- **Minor Updates**: Opzionali, nuove features
- **Major Updates**: Valutare, breaking changes

---

## 🤝 CONTRIBUIRE AL PROGETTO

### Processo Contributing

```
1. Fork il repository
2. Crea branch: git checkout -b feature/nome
3. Commit: git commit -m "feat: descrizione"
4. Push: git push origin feature/nome
5. Apri Pull Request
6. Attendi review
```

### Commit Message Format

```
feat(scope): descrizione breve
body (opzionale)
footer (opzionale)

Esempi:
- feat(ui): add dark mode toggle
- fix(audio): resolve autoplay issue
- docs(readme): update installation guide
- style(css): refactor animation timings
- test(effects): add glow animation tests
```

### Code Style Guide

```javascript
// Naming Conventions
const variable_name = 'snake_case';
function functionName() { } // camelCase
class ClassName { } // PascalCase

// Indentazione
✅ 2 spazi (soft tabs)
❌ Tabs hard

// Commenti
// Commento singola riga
/* Commento
   multilinea
*/
```

---

## 📋 CHANGELOG

### v1.0.0 (2026-01-14)
```
🎉 Major Release - Music Effects & Stability

Features:
  ✨ Dynamic glow effects when music plays
  ✨ Pulsing progress bar with music activation
  ✨ Animated logo with neon blur effect
  ✨ Volume slider modernization with gradient

Fixes:
  🐛 Audio continues at 0% volume - FIXED
  🐛 Music effects not appearing - FIXED
  🐛 Language selector dropdown styling - FIXED
  🐛 Deprecated GitHub Actions warnings - FIXED

Performance:
  ⚡ GPU-accelerated animations
  ⚡ Optimized DOM manipulation
  ⚡ Reduced memory footprint

Docs:
  📖 Professional README enhancement
  📖 Advanced configuration guide
  📖 Developer API documentation
```

### v2.0.0 (2025-12-01)
```
🌍 Multilingual Support Release

Features:
  ✨ 5-language support (IT, EN, FR, DE, JA)
  ✨ Dynamic language selector
  ✨ Translated tips system
  ✨ Localized taglines

Breaking:
  🔴 HTML structure changes for i18n support
  🔴 CSS class naming conventions updated

Docs:
  📖 Multilingual guide added
```

### v1.5.0 (2025-11-15)
```
🚀 CI/CD Automation Release

Features:
  ✨ GitHub Actions workflow
  ✨ Automated .zip creation
  ✨ Auto GitHub Releases
  ✨ Version auto-extraction from package.json

Docs:
  📖 Deployment guide added
```

### v1.0.0 (2025-10-01)
```
🎬 Initial Release

Features:
  ✨ Professional loading screen UI
  ✨ Video background support
  ✨ Audio system with controls
  ✨ Progress bar animation
  ✨ Mute button with dynamic icon
  ✨ Responsive design



### ⚡ Passaggi Rapidi

```
1️⃣  Estrai la cartella della loading screen
2️⃣  Inserisci nella cartella: resources/
3️⃣  Apri il file: server.cfg
4️⃣  Aggiungi: ensure maxii_loading
5️⃣  Riavvia il server
```

---

## 📁 STRUTTURA DELLA RISORSA

```
maxii_loading/
│
├── 📄 fxmanifest.lua
├── 🌐 index.html
├── 🎵 music_yt.mp3
└── 🎬 background.mp4
```

---

## 🎨 PERSONALIZZAZIONE

### 🖼️ Logo Personalizzato

- 📌 **Nome file:** `logo.png`
- 📍 **Posizione:** Nella cartella della risorsa
- ⚠️ **Importante:** Non modificare il nome del file

Per utilizzare il tuo logo, sostituisci semplicemente il file esistente con la tua immagine. Il nuovo file deve essere chiamato esattamente `logo.png`.

---

### 🎵 Musica Personalizzata

- 📌 **Nome file:** `music_yt.mp3`
- 📍 **Posizione:** Nella cartella della risorsa
- ⚠️ **Importante:** Non rinominare se non modifichi anche index.html

Puoi sostituire la musica inclusa con una tua traccia. Il file verrà utilizzato automaticamente dalla loading screen.

---

### 🎬 Sfondo Personalizzato

- 📌 **Nome file:** `background.mp4`
- 📍 **Posizione:** Nella cartella della risorsa
- ⚠️ **Importante:** Mantenere il nome esatto

La loading screen supporta uno sfondo video personalizzato. Il video verrà caricato automaticamente come sfondo.

---

## 🎛️ SISTEMA MUSICALE

### Controlli Audio

| Comando | Descrizione |
|---------|------------|
| ▶️ **PLAY** | Avvia la musica |
| ⏸️ **PAUSA** | Mette in pausa senza chiudere la loading screen |
| 🔊 **VOLUME** | Regola il volume da 0% a 100% |
| 🔇 **MUTE** | Icona che cambia quando il volume è a 0% |

**Volume Predefinito:** 15%

### ⚠️ Autoplay

In alcuni casi FiveM potrebbe impedire l'avvio automatico dell'audio.

**Soluzione:** Clicca una volta sulla loading screen → La musica partirà automaticamente

---

## 🌐 SISTEMA MULTILINGUE

### 🗣️ Lingue Supportate

- 🇬🇧 **English**
- 🇮🇹 **Italiano**
- 🇫🇷 **Français**
- 🇩🇪 **Deutsch**
- 🇯🇵 **日本語**

**Cambio lingua:** Tramite il selettore in alto a destra della loading screen

---

## ✨ EFFETTI E ANIMAZIONI

### 🎆 Effetti Dinamici

- ⭐ **Glow Animato:** Effetto luminoso quando la musica parte
- 📊 **Barra Pulsante:** La barra di caricamento si illumina in blu
- 🌟 **Logo Brillante:** Il logo pulsa con effetto neon blu
- 💫 **Particelle:** Effetti di particelle in background

---

## 📊 SISTEMA DI PROGRESSO

La barra di caricamento è progettata per funzionare con gli eventi di caricamento di FiveM.

**Evento Ascoltato:** `loadProgress`

La loading screen:
- ✅ Aggiorna automaticamente la percentuale
- ✅ Mantiene l'animazione della barra
- ✅ Evita il blocco allo 0% durante le prime fasi

---

## ⚙️ CONFIGURAZIONE

### 🎯 Elementi Personalizzabili

| Elemento | Dove |
|----------|------|
| 🎨 Logo | `index.html` |
| 📝 Testi | `index.html` |
| 🎨 Colori | Sezione CSS in `index.html` |
| 🎵 Musica | Sostituisci `music_yt.mp3` |
| 🎬 Video | Sostituisci `background.mp4` |
| 💬 Suggerimenti | `index.html` (array tips) |
| 🔗 Discord | `index.html` |

---

## 🔧 REQUISITI DI SISTEMA

- ✅ FiveM
- ✅ NUI abilitata
- ✅ Resource FiveM funzionante
- ✅ fxmanifest.lua configurato correttamente

---

## ⚡ INSTALLAZIONE RAPIDA

```
resources/
└── maxii_loading/
    ├── fxmanifest.lua
    ├── index.html
    ├── music_yt.mp3
    ├── background.mp4
    └── logo.png
```

**server.cfg:**
```
ensure maxii_loading
```

---

## ❗ NOTE IMPORTANTI

- ⚠️ Non rinominare `music_yt.mp3` senza modificare il riferimento in `index.html`
- ⚠️ Non rinominare `background.mp4` senza modificare il riferimento in `index.html`
- ⚠️ Assicurati che la risorsa venga avviata prima di entrare nel server
- ⚠️ Riavvia FiveM/server per applicare i cambiamenti

---

## 🚀 BUG FIX & FEATURE

### Versione Attuale

- ✅ Supporto multilingue (5 lingue)
- ✅ Icona volume dinamica (mute/normal)
- ✅ Effetti glow sincronizzati con la musica
- ✅ Volume slider modernizzato con gradient
- ✅ GitHub Actions CI/CD automatico
- ✅ Audio pause corretto a 0%

---

<div align="center">

### 🎬 MAXII STUDIO

**Una loading screen moderna e ottimizzata per server FiveM**

Designed & Developed by **MAXII STUDIO**

Con supporto per video di sfondo, musica personalizzata,
controllo volume e sistema di caricamento dinamico.

**[Discord](https://discord.gg/C4GPF6JevM)** • **[Website](#)**

</div>

---

## 🇬🇧 ENGLISH

---

## � TECHNICAL OVERVIEW

**MAXII Loading Screen** is a modern and optimized loading solution for FiveM servers with an **event-driven architecture** based on:

- **NUI (Native UI)**: Interface rendered with CEF/Chromium
- **Multilingual**: Dynamic i18n system with 5 supported languages
- **Responsive Audio**: Audio engine with visual synchronization
- **Hardware Accelerated CSS**: GPU-optimized animations
- **Progressive Loading**: Real-time progress bar

### 📋 Technological Stack

```
┌─────────────────────────────────────┐
│  HTML5 + CSS3 + ES6+ JavaScript     │
├─────────────────────────────────────┤
│  • Media API (Audio/Video)           │
│  • DOM APIs (querySelector, classList)
│  • Event System (addEventListener)   │
│  • Animation Frame API               │
└─────────────────────────────────────┘
        ↓
┌─────────────────────────────────────┐
│  FiveM NUI Framework                │
├─────────────────────────────────────┤
│  • CEF/Chromium Renderer            │
│  • Window Focus Management           │
│  • TriggerEvent Broadcasting        │
│  • Resource Lifecycle                │
└─────────────────────────────────────┘
```

---

## 🏗️ SYSTEM ARCHITECTURE

### Component Diagram

```
┌──────────────────────────────────────────────────────────┐
│                  Loading Screen UI                       │
├──────────────────────────────────────────────────────────┤
│                                                           │
│  ┌───────────────────────────────────────────────────┐   │
│  │              Video Background Layer               │   │
│  │  (background.mp4 @ 60fps)                         │   │
│  └───────────────────────────────────────────────────┘   │
│                                                           │
│  ┌───────────────────────────────────────────────────┐   │
│  │          Brand Logo & Effects Layer               │   │
│  │  • logoPulse animation                            │   │
│  │  • logoGlow effect (music-active)                 │   │
│  │  • Neon blur effect                               │   │
│  └───────────────────────────────────────────────────┘   │
│                                                           │
│  ┌───────────────────────────────────────────────────┐   │
│  │      Status & Text Display Layer                  │   │
│  │  • Status message (i18n)                          │   │
│  │  • Rotating tips (8 per language)                 │   │
│  │  • Brand tagline                                  │   │
│  └───────────────────────────────────────────────────┘   │
│                                                           │
│  ┌───────────────────────────────────────────────────┐   │
│  │      Progress & Control Layer                     │   │
│  │  • Progress bar (shimmer animation)               │   │
│  │  • Volume slider (gradient)                       │   │
│  │  • Mute button (dynamic SVG icon)                 │   │
│  │  • Language selector (5 options)                  │   │
│  └───────────────────────────────────────────────────┘   │
│                                                           │
│  ┌───────────────────────────────────────────────────┐   │
│  │        Audio Controller (Background)              │   │
│  │  • Volume control (0-100%)                        │   │
│  │  • Music reactive effects                         │   │
│  │  • Auto-pause at 0%                               │   │
│  └───────────────────────────────────────────────────┘   │
│                                                           │
└──────────────────────────────────────────────────────────┘
                        ↓
        ┌───────────────────────────────┐
        │  FiveM Event System           │
        │  ┌─────────────────────────┐  │
        │  │ loadProgress (0-100)    │  │
        │  │ onClientMapStart        │  │
        │  │ Custom Events           │  │
        │  └─────────────────────────┘  │
        └───────────────────────────────┘
```

### Data Flow

```
User Interaction
      ↓
Event Handler
      ↓
State Update
      ↓
DOM Manipulation
      ↓
CSS Animation/Transition
      ↓
Visual Feedback
```

---

## 🔧 REQUIREMENTS & DEPENDENCIES

### System Requirements

| Component | Version | Status |
|-----------|---------|--------|
| **FiveM** | v1.0+ | ✅ Required |
| **NUI** | Default | ✅ Required |
| **Browser CEF** | Built-in | ✅ Automatic |
| **JavaScript** | ES6+ | ✅ Supported |
| **HTML5** | 5+ | ✅ Supported |
| **CSS3** | 3+ | ✅ Supported |

### External Dependencies

```json
{
  "dependencies": "none",
  "peerDependencies": "none",
  "optionalDependencies": {
    "custom_music": "any",
    "custom_video": "any",
    "custom_logo": "any"
  }
}
```

### Required Resources

```
✅ HTML5 (index.html)
✅ CSS3 (Inline in index.html)
✅ JavaScript ES6+ (Inline in index.html)
✅ Video H.264 MP4 (background.mp4)
✅ Audio MP3 (music_yt.mp3)
✅ PNG/JPEG Logo (logo.png)
✅ Lua Manifest (fxmanifest.lua)
```

---

## 📦 ADVANCED INSTALLATION

### Method 1: Standard Installation

```bash
# 1. Clone or download repository
git clone https://github.com/maxii-studio/maxii-loading.git

# 2. Move to resources folder
mv maxii-loading resources/maxii_loading

# 3. Add to server.cfg
echo "ensure maxii_loading" >> server.cfg

# 4. Restart server
# restart
```

### Method 2: Automated Setup (PowerShell)

```powershell
# For Windows
$resourcePath = "resources\maxii_loading"
if (Test-Path $resourcePath) {
    Write-Host "✅ Resource already present"
} else {
    Write-Host "📦 Downloading resource..."
    # Download logic here
}
```

### Method 3: Docker Setup

```dockerfile
FROM fivem/base:latest

COPY maxii_loading /opt/server/resources/maxii_loading

ENV FIVEM_LOADING_SCREEN="maxii_loading"
```

### Post-Installation Checklist

- [ ] Resource folder in correct location (`resources/maxii_loading/`)
- [ ] `fxmanifest.lua` file present and valid
- [ ] `index.html` file present
- [ ] Audio and video files present or customized
- [ ] `ensure maxii_loading` line in `server.cfg`
- [ ] Correct read/write permissions
- [ ] Server restarted correctly
- [ ] Loading screen appears on startup

---

## ⚙️ PROFESSIONAL CONFIGURATION

### JSON Schema - Advanced Configuration

```json
{
  "metadata": {
    "name": "MAXII Loading Screen",
    "version": "1.0.0",
    "description": "Professional FiveM Loading Screen"
  },
  "ui": {
    "position": "fullscreen",
    "resolution": "adaptive",
    "scaling": "responsive"
  },
  "multimedia": {
    "video": {
      "enabled": true,
      "source": "background.mp4",
      "autoplay": true,
      "loop": true,
      "muted": true,
      "fps": 60,
      "quality": "1080p"
    },
    "audio": {
      "enabled": true,
      "source": "music_yt.mp3",
      "autoplay": false,
      "volume": 0.15,
      "loop": true,
      "format": "mp3"
    },
    "logo": {
      "source": "logo.png",
      "width": "200px",
      "height": "200px",
      "animation": "logoPulse"
    }
  },
  "localization": {
    "default": "en",
    "supported": ["it", "en", "fr", "de", "ja"],
    "fallback": "en",
    "rtl": false
  },
  "effects": {
    "animations": {
      "logoPulse": { "duration": "2s", "easing": "ease-in-out" },
      "logoGlow": { "duration": "0.6s", "easing": "ease-in-out" },
      "statusPulse": { "duration": "1.5s", "easing": "ease-in-out" },
      "shimmer": { "duration": "2s", "easing": "linear" },
      "musicActive": { "duration": "0.6s", "easing": "ease-in-out" }
    },
    "transitions": {
      "default": "0.3s ease-in-out",
      "progress": "0.2s linear",
      "language": "0.4s ease"
    }
  },
  "performance": {
    "hardwareAcceleration": true,
    "fps_target": 60,
    "memory_limit": "256MB",
    "render_optimization": true
  },
  "accessibility": {
    "screenReaderSupport": true,
    "highContrastMode": false,
    "keyboardNavigation": true
  }
}
```

### Customizable CSS Variables

```css
/* Primary Colors */
--color-primary: #2563eb;
--color-secondary: #1e40af;
--color-accent: #3b82f6;
--color-success: #10b981;
--color-warning: #f59e0b;
--color-danger: #ef4444;

/* Sizes */
--size-xs: 0.25rem;
--size-sm: 0.5rem;
--size-md: 1rem;
--size-lg: 1.5rem;
--size-xl: 2rem;

/* Typography */
--font-sans: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
--font-mono: 'Monaco', 'Courier New', monospace;
--font-size-base: 16px;
--line-height-normal: 1.5;

/* Effects */
--blur-sm: 4px;
--blur-md: 8px;
--blur-lg: 12px;
--glow-color: #3b82f6;
--glow-intensity: 0.8;
```

### How to Modify Variables

```html
<!-- In index.html, modify the <style> section -->
<style>
  :root {
    --color-primary: #YOUR_COLOR;
    --glow-color: #YOUR_GLOW;
  }
</style>
```

---

## 🔨 DEVELOPER API REFERENCE

### Global Objects Available

```javascript
// DOM ELEMENTS
window.bgVideo              // <video> background element
window.bgMusic              // <audio> music element
window.volumeSlider         // <input type="range"> volume
window.volumeValue          // <span> volume display
window.muteButton           // <button> mute toggle
window.languageSelect       // <select> language selector
window.statusText           // <div> status display
window.tipText              // <div> tips display
window.brandTag             // <span> brand tagline
window.brandLogo            // <img> logo element
window.progressFill         // <div> progress bar
```

### Main Functions

```javascript
// Language Change
updateLanguage(code)
// code: 'it', 'en', 'fr', 'de', 'ja'
// Updates all visible text

// Audio Control
startMusic()                // Start music
function volumeControl()    // Volume handler
function muteToggle()       // Toggle mute

// Animation Effects
progressBar.classList.add('music-active')
brandLogo.classList.add('music-active')

// State Management
musicStoppedByUser          // boolean flag
```

### FiveM Event Listeners

```javascript
// Listen to loading progress
on('loadProgress', (progress) => {
  progressFill.style.width = (progress * 100) + '%';
});

// Closing event
on('stopLoadingScreen', () => {
  // Cleanup logic
});

// Initialization event
on('onClientMapStart', () => {
  startMusic();
});
```

### Custom Extensions

```javascript
// Add new language
const newLanguageMessages = {
  loading: "Loading in progress...",
  status: "Custom status",
  tip: "Custom tip"
};
messages.push(newLanguageMessages);

// Add custom effect
const customStyle = document.createElement('style');
customStyle.textContent = `
  @keyframes customGlow {
    0% { opacity: 0.8; }
    50% { opacity: 1; }
    100% { opacity: 0.8; }
  }
  .custom-effect { animation: customGlow 1s ease-in-out infinite; }
`;
document.head.appendChild(customStyle);
```

---

## 🎨 CSS & THEMING SYSTEM

### CSS Architecture

```
┌─ Base Styles (Reset, Typography)
├─ Component Styles (Video, Logo, Progress)
├─ Layout Styles (Positioning, Grid)
├─ Animation Styles (@keyframes)
├─ Theme Styles (Colors, Gradients)
└─ Utility Styles (Utils, Helpers)
```

### Available Animations

| Animation | Duration | Trigger | Use |
|-----------|----------|---------|-----|
| `logoPulse` | 2s | Screen start | Pulsing logo |
| `logoGlow` | 0.6s | Music start | Blue neon effect |
| `statusPulse` | 1.5s | Continuous | Pulsing text |
| `shimmer` | 2s | Continuous | Loading bar |
| `musicActive` | 0.6s | Music start | Glowing effect |

### Dark vs Light Theme

```css
/* Dark Theme (Default) */
:root {
  --bg-primary: #0f172a;
  --text-primary: #ffffff;
  --glow-color: #3b82f6;
}

/* Light Theme (Alternative) */
[data-theme="light"] {
  --bg-primary: #ffffff;
  --text-primary: #1e293b;
  --glow-color: #1e40af;
}
```

### How to Create Custom Theme

```html
<style>
  /* Override CSS variables */
  :root {
    --color-primary: #8b5cf6;  /* Purple */
    --glow-color: #8b5cf6;
    --color-accent: #a78bfa;
  }
</style>
```

---

## ⚡ PERFORMANCE OPTIMIZATION

### Best Practices

```javascript
// ✅ GOOD: Use classList for animations
element.classList.add('music-active');

// ❌ BAD: Manipulate style directly for animations
element.style.animation = 'glow 0.6s ease-in-out';

// ✅ GOOD: Event delegation
document.addEventListener('change', (e) => {
  if (e.target === languageSelect) { /* ... */ }
});

// ❌ BAD: Multiple listeners
languageSelect.addEventListener('change', handler1);
languageSelect.addEventListener('change', handler2);

// ✅ GOOD: Debounce for frequent inputs
const debounce = (fn, delay) => {
  let timer;
  return (...args) => {
    clearTimeout(timer);
    timer = setTimeout(() => fn(...args), delay);
  };
};

// ✅ GOOD: RequestAnimationFrame for animations
requestAnimationFrame(() => {
  progressFill.style.width = value + '%';
});
```

### Profiling & Monitoring

```javascript
// Measure performance
console.time('loadResource');
// ... code ...
console.timeEnd('loadResource');

// Monitor frame rate
let frameCount = 0;
setInterval(() => {
  console.log(`FPS: ${frameCount}`);
  frameCount = 0;
}, 1000);
requestAnimationFrame(() => { frameCount++; });
```

### Memory & Resource Management

| Resource | Limit | Status |
|----------|-------|--------|
| **Memory** | 256MB | ⚠️ Monitor |
| **CPU Usage** | <15% | ✅ Typical |
| **GPU Load** | 5-10% | ✅ Low |
| **Network** | ~50MB | ✅ One-time |

---

## 🐛 ADVANCED TROUBLESHOOTING

### Issue: Audio doesn't auto-start

**Diagnostics:**
```javascript
// Check console (F12)
console.log(bgMusic);  // Should show <audio> element
console.log(bgMusic.src);  // Should show file path
```

**Solutions:**
```javascript
// 1. CEF autoplay policy
// FiveM allows autoplay in NUI, verify file path

// 2. Add fallback
bgMusic.play().catch(error => {
  console.error('Autoplay failed:', error);
  console.log('Waiting for user interaction...');
});

// 3. Add click handler
document.addEventListener('click', () => {
  bgMusic.play().catch(console.error);
});
```

### Issue: Glow effects not visible

**Diagnostics:**
```javascript
console.log('brandLogo:', brandLogo);
console.log('Applied classes:', brandLogo?.classList);
console.log('Computed style:', getComputedStyle(brandLogo));
```

**Solutions:**
```javascript
// Verify CSS is loaded
const styles = document.styleSheets;
console.log('Stylesheets loaded:', styles.length);

// Force redraw
brandLogo.offsetHeight; // Trigger reflow
brandLogo.classList.add('music-active');
```

### Issue: Poor performance (low FPS)

**Monitoring:**
```javascript
// Load profiling
performance.mark('start');
// ... operation ...
performance.mark('end');
performance.measure('duration', 'start', 'end');
console.log(performance.getEntriesByType('measure'));
```

**Optimization:**
```javascript
// Disable VSync temporarily during intensive animations
// Reduce shader effects in CSS
// Optimize video: compress 1080p → 720p
// Reduce video frame rate: 60fps → 30fps
```

### Issue: Text doesn't change with language

**Debug:**
```javascript
console.log('Selected language:', languageSelect.value);
console.log('Available messages:', messages);
console.log('Status text:', statusText.textContent);
```

**Solution:**
```javascript
// Verify language arrays
if (!messages[languageSelect.value]) {
  console.error('Language not found, fallback to EN');
  updateLanguage('en');
}
```

### General System Verification

```bash
# Check FiveM server logs
tail -f server.log | grep "maxii_loading\|LoadingScreen"

# Check browser console
# F12 → Console tab
# Look for red error messages
```

---

## 🔐 SECURITY & BEST PRACTICES

### Input Validation

```javascript
// ✅ Validate language before use
const VALID_LANGUAGES = ['it', 'en', 'fr', 'de', 'ja'];
function updateLanguage(code) {
  if (!VALID_LANGUAGES.includes(code)) {
    console.warn('Invalid language:', code);
    code = 'en';
  }
  // Proceed with validated language
}

// ✅ Validate volume
if (volume >= 0 && volume <= 1) {
  bgMusic.volume = volume;
}
```

### XSS Prevention

```javascript
// ❌ BAD: Use innerHTML for dynamic text
statusText.innerHTML = userInput;

// ✅ GOOD: Use textContent for text
statusText.textContent = userInput;

// ✅ GOOD: Sanitize if HTML needed
function sanitize(html) {
  const div = document.createElement('div');
  div.textContent = html;
  return div.innerHTML;
}
```

### Resource Protection

```lua
-- fxmanifest.lua - Access limitations
fx_version 'cerulean'
game 'gta5'

author 'MAXII Studio'
description 'Professional Loading Screen'
version '1.0.0'

-- Only as loading screen
loadingScreenScript 'index.html'

-- No server code, asset server safe
```

### Rate Limiting

```javascript
// Prevent event spam
let lastEventTime = 0;
const MIN_INTERVAL = 100; // ms

function handleFrequentEvent() {
  const now = Date.now();
  if (now - lastEventTime < MIN_INTERVAL) return;
  lastEventTime = now;
  // Proceed
}
```

---

## 📦 VERSIONING

### Semantic Versioning

```
MAXII Loading Screen v1.0.0
                    │ │ │
                    │ │ └─ PATCH: Bug fixes (1.0.0 → 2.1.1)
                    │ └──── MINOR: Features (1.0.0 → 2.2.0)
                    └─────── MAJOR: Breaking changes (1.0.0 → 3.0.0)
```

### Version History

| Version | Date | Notes |
|---------|------|-------|
| **1.0.0** | 2026-01 | ✅ Music effects, fix audio |
| **2.0.0** | 2025-12 | ✅ 5-language support |
| **1.5.0** | 2025-11 | ✅ GitHub Actions CI/CD |
| **1.0.0** | 2025-10 | ✅ Initial release |

### Update Policy

- **Patch Updates**: Automatic, bug fixes
- **Minor Updates**: Optional, new features
- **Major Updates**: Review carefully, breaking changes

---

## 🤝 CONTRIBUTING TO PROJECT

### Contributing Process

```
1. Fork the repository
2. Create branch: git checkout -b feature/name
3. Commit: git commit -m "feat: description"
4. Push: git push origin feature/name
5. Open Pull Request
6. Wait for review
```

### Commit Message Format

```
feat(scope): brief description
body (optional)
footer (optional)

Examples:
- feat(ui): add dark mode toggle
- fix(audio): resolve autoplay issue
- docs(readme): update installation guide
- style(css): refactor animation timings
- test(effects): add glow animation tests
```

### Code Style Guide

```javascript
// Naming Conventions
const variable_name = 'snake_case';
function functionName() { } // camelCase
class ClassName { } // PascalCase

// Indentation
✅ 2 spaces (soft tabs)
❌ Hard tabs

// Comments
// Single line comment
/* Multi-line
   comment
*/
```

---

## 📋 CHANGELOG

### v1.0.0 (2026-01-14)
```
🎉 Major Release - Music Effects & Stability

Features:
  ✨ Dynamic glow effects when music plays
  ✨ Pulsing progress bar with music activation
  ✨ Animated logo with neon blur effect
  ✨ Volume slider modernization with gradient

Fixes:
  🐛 Audio continues at 0% volume - FIXED
  🐛 Music effects not appearing - FIXED
  🐛 Language selector dropdown styling - FIXED
  🐛 Deprecated GitHub Actions warnings - FIXED

Performance:
  ⚡ GPU-accelerated animations
  ⚡ Optimized DOM manipulation
  ⚡ Reduced memory footprint

Docs:
  📖 Professional README enhancement
  📖 Advanced configuration guide
  📖 Developer API documentation
```

### v2.0.0 (2025-12-01)
```
🌍 Multilingual Support Release

Features:
  ✨ 5-language support (IT, EN, FR, DE, JA)
  ✨ Dynamic language selector
  ✨ Translated tips system
  ✨ Localized taglines

Breaking:
  🔴 HTML structure changes for i18n support
  🔴 CSS class naming conventions updated

Docs:
  📖 Multilingual guide added
```

### v1.5.0 (2025-11-15)
```
🚀 CI/CD Automation Release

Features:
  ✨ GitHub Actions workflow
  ✨ Automated .zip creation
  ✨ Auto GitHub Releases
  ✨ Version auto-extraction from package.json

Docs:
  📖 Deployment guide added
```

### v1.0.0 (2025-10-01)
```
🎬 Initial Release

Features:
  ✨ Professional loading screen UI
  ✨ Video background support
  ✨ Audio system with controls
  ✨ Progress bar animation
  ✨ Mute button with dynamic icon
  ✨ Responsive design
```

---

<div align="center">

### 🎬 MAXII STUDIO

**A modern, advanced and optimized loading screen for FiveM servers**

Designed & Developed with ❤️ by **MAXII STUDIO**

Featuring professional-grade video backgrounds, custom music controls,
dynamic visual effects, and comprehensive multilingual support.

**[Discord Community](https://discord.gg/C4GPF6JevM)** • **[Website](#)** • **[GitHub](https://github.com/maxii-studio/maxii-loading)**

---

**Version 1.0.0** — © 2026 MAXII STUDIO — All Rights Reserved

Made for the FiveM Community with passion and attention to detail.

</div>


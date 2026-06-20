
# 🎨 MemeDesign

![Version](https://img.shields.io/badge/version-1.1.0-red?style=flat-square)
![License](https://img.shields.io/badge/license-WTFPL-brightgreen?style=flat-square)
![Made With](https://img.shields.io/badge/made%20with-%F0%9F%92%80%20cringe-purple?style=flat-square)
![API](https://img.shields.io/badge/API-stable-blue?style=flat-square)

> When you want your UI to be absolutely **CHAD** 💪🗿

**MemeDesign** is a CSS library that brings the chaotic energy of internet meme culture to web design. Bold borders, Impact font, eye-searing colors, and zero subtlety — just like the internet intended.

---

## 🚀 Installation

### CDN (Recommended)
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/dryfish09/MemeDesign@main/src/MemeUIDesign.css">
```

### Local
```bash
git clone https://github.com/dryfish09/MemeDesign.git
```
```html
<link rel="stylesheet" href="path/to/src/MemeUIDesign.css">
```

> **Requires:** Google Fonts — Impact & Comic Neue (included in CSS)

---

## 📚 Components

### 🔴 Buttons
```html
<button class="meme-btn meme-btn-red">Red Button</button>
<button class="meme-btn meme-btn-blue">Blue Button</button>
<button class="meme-btn meme-btn-green">Green Button</button>
<button class="meme-btn meme-btn-yellow">Yellow Button</button>
<button class="meme-btn meme-btn-purple">Purple Button</button>
<button class="meme-btn meme-btn-pink">Pink Button</button>
```

**Variants:**
| Class | Description |
|-------|-------------|
| `meme-btn-lg` | Large button |
| `meme-btn-xl` | Extra large button |
| `meme-btn-block` | Full-width button |
| `meme-btn-subscribe` | Animated subscribe button |
| `meme-btn-rainbow` | 🌈 Animated rainbow button |
| `meme-btn-rainbow-static` | 🌈 Static rainbow button |

---

### 🃏 Cards
```html
<div class="meme-card">
  <div class="meme-card-img" style="background: linear-gradient(45deg, #FFD700, #FF8C00);">
    🐸
  </div>
  <div class="meme-card-body">
    <div class="meme-card-title">Card Title</div>
    <p class="meme-card-text">Your text here...</p>
    <button class="meme-btn meme-btn-green">ACTION</button>
  </div>
</div>
```

**Rainbow variants:** `meme-card-rainbow` (animated) · `meme-card-rainbow-static`

---

### 📝 Forms
```html
<label class="meme-label">Username:</label>
<input type="text" class="meme-input" placeholder="Enter epic name...">

<label class="meme-label">Bio:</label>
<textarea class="meme-textarea" placeholder="Write your copypasta..."></textarea>
```

**Rainbow variants:** `meme-input-rainbow` · `meme-input-rainbow-static`

---

### ⚠️ Alerts
```html
<div class="meme-alert meme-alert-success">✅ Success! Noice!</div>
<div class="meme-alert meme-alert-error">❌ Error! Bruh moment!</div>
<div class="meme-alert meme-alert-warning">⚠️ Warning! Sus!</div>
<div class="meme-alert meme-alert-info">ℹ️ Info: Touch grass!</div>

<!-- Auto glitch (use sparingly) -->
<div class="meme-alert meme-alert-error meme-glitch-auto">❌ AUTO GLITCH!</div>
```

**Rainbow variants:** `meme-alert-rainbow` · `meme-alert-rainbow-static`

---

### 🏷️ Badges
```html
<span class="meme-badge meme-badge-new">NEW</span>
<span class="meme-badge meme-badge-hot">HOT 🔥</span>
<span class="meme-badge">OG</span>
```

**Rainbow variants:** `meme-badge-rainbow` · `meme-badge-rainbow-static`

---

### 📊 Progress Bars
```html
<div class="meme-progress">
  <div class="meme-progress-bar" style="width: 69%;">69%</div>
</div>
```

**Rainbow variants:** `meme-progress-rainbow` · `meme-progress-rainbow-static`

---

### 🔘 Toggle Switch
```html
<label class="meme-toggle">
  <input type="checkbox" class="meme-toggle-input" id="my-toggle">
  <div class="meme-toggle-track">
    <div class="meme-toggle-thumb">👎</div>
  </div>
</label>
```

Toggle state is automatically saved to `localStorage` and restored on page load.

---

### 🎨 Layout & Utilities
```html
<!-- Grid -->
<div class="meme-grid">
  <div class="meme-card">...</div>
  <div class="meme-card">...</div>
</div>

<!-- Flex -->
<div class="meme-flex">...</div>
<div class="meme-flex-center">...</div>

<!-- Backgrounds -->
<div class="meme-bg-rainbow">Rainbow background</div>
<div class="meme-bg-dark">Dark background</div>

<!-- Text -->
<span class="meme-text-impact">Impact font text</span>
<span class="meme-text-comic">Comic font text</span>
<span class="meme-text-center">Centered text</span>

<!-- Spacing -->
<div class="meme-mt-2 meme-mb-3">Spaced content</div>
```

**Rainbow text:** `meme-text-rainbow` · `meme-text-rainbow-static`

---

### 🌈 Headers & Titles
```html
<!-- Rainbow Headers -->
<header class="meme-header-rainbow">
  <h1>Animated Rainbow Header</h1>
</header>

<header class="meme-header-rainbow-static">
  <h1>Static Rainbow Header</h1>
</header>

<!-- Rainbow Section Titles -->
<h2 class="meme-section-title-rainbow">Animated Rainbow Title</h2>
<h2 class="meme-section-title-rainbow-static">Static Rainbow Title</h2>
```

**Classic variants:** `meme-header` · `meme-section-title`

---

## 🎯 Complete Class Reference

| Category | Classes |
|----------|---------|
| **Buttons** | `meme-btn`, `meme-btn-red`, `meme-btn-blue`, `meme-btn-green`, `meme-btn-yellow`, `meme-btn-purple`, `meme-btn-pink`, `meme-btn-lg`, `meme-btn-xl`, `meme-btn-block`, `meme-btn-subscribe`, `meme-btn-rainbow`, `meme-btn-rainbow-static` |
| **Cards** | `meme-card`, `meme-card-img`, `meme-card-body`, `meme-card-title`, `meme-card-text`, `meme-card-rainbow`, `meme-card-rainbow-static` |
| **Forms** | `meme-input`, `meme-label`, `meme-textarea`, `meme-input-rainbow`, `meme-input-rainbow-static` |
| **Alerts** | `meme-alert`, `meme-alert-success`, `meme-alert-error`, `meme-alert-warning`, `meme-alert-info`, `meme-glitch-auto`, `meme-alert-rainbow`, `meme-alert-rainbow-static` |
| **Badges** | `meme-badge`, `meme-badge-new`, `meme-badge-hot`, `meme-badge-rainbow`, `meme-badge-rainbow-static` |
| **Progress** | `meme-progress`, `meme-progress-bar`, `meme-progress-rainbow`, `meme-progress-rainbow-static` |
| **Toggle** | `meme-toggle`, `meme-toggle-input`, `meme-toggle-track`, `meme-toggle-thumb` |
| **Headers** | `meme-header`, `meme-section-title`, `meme-header-rainbow`, `meme-header-rainbow-static`, `meme-section-title-rainbow`, `meme-section-title-rainbow-static` |
| **Text** | `meme-text-impact`, `meme-text-comic`, `meme-text-center`, `meme-text-rainbow`, `meme-text-rainbow-static` |
| **Layout** | `meme-container`, `meme-grid`, `meme-flex`, `meme-flex-center` |
| **Backgrounds** | `meme-bg-rainbow`, `meme-bg-dark` |
| **Spacing** | `meme-mt-1`, `meme-mt-2`, `meme-mt-3`, `meme-mb-1`, `meme-mb-2`, `meme-mb-3` |

---

## 🛠️ CSS Custom Properties

```css
:root {
  --meme-red: #FF0000;
  --meme-blue: #0000FF;
  --meme-green: #00FF00;
  --meme-yellow: #FFD700;
  --meme-orange: #FF4500;
  --meme-purple: #8B00FF;
  --meme-pink: #FF69B4;
  --meme-white: #FFFFFF;
  --meme-black: #000000;

  --meme-font-impact: 'Impact', 'Arial Black', sans-serif;
  --meme-font-comic: 'Comic Neue', 'Comic Sans MS', cursive;

  --meme-border: 3px solid #000000;
  --meme-shadow: 4px 4px 0px #000000;

  --rainbow-speed: 8s; /* Control all rainbow animations */
}
```

Override these variables to create your own cursed themes! 💀

---

## 📁 Project Structure

```
MemeDesign/
├── src/
│   └── MemeUIDesign.css    # Core CSS library (JS included)
├── demo/
│   └── index.html          # Demo page
├── README.md               # This file
└── LICENSE                 # WTFPL
```

---

## 🌐 Browser Support

| Browser | Supported |
|---------|:---------:|
| Chrome | ✅ |
| Firefox | ✅ |
| Safari | ✅ |
| Edge | ✅ |
| Internet Explorer | 💀 Bruh... |

---

## 📄 License

**WTFPL** — Do What The F*ck You Want to Public License

This means you can freely use, modify, distribute, and sell this code. No restrictions. Just don't blame us if your website gets roasted on r/ProgrammerHumor.

---

## 🤝 Contributing

Found a bug? Want to add more meme energy?

1. Fork the repo
2. Create your feature branch (`git checkout -b feature/dank-feature`)
3. Commit changes (`git commit -m 'Added dank feature 💀'`)
4. Push to branch (`git push origin feature/dank-feature`)
5. Open a Pull Request

---

## ⭐ Show Your Support

If this library made you exhale air through your nose slightly faster than normal:

- ⭐ Star this repo
- 🗿 Share with your fellow developers
- 💀 Use it in production (we dare you)

---

## 🗿 Acknowledgments

- **Impact font** — The undisputed king of meme typography
- **Comic Sans** — For that extra layer of cringe
- **Pepe the Frog** — Eternal inspiration 🐸
- **Moai** — 🗿
- **Internet culture** — For keeping us all slightly unhinged

---

**Made with 💀 by [dryfish09](https://github.com/dryfish09)**

*"Hey! That's pretty good!"* — Rock 🗿

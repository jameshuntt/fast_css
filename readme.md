# fast_css ⚡

> "Utilities for faster CSS. I do not use CSS anymore, but it was great for rapid script-like styling."

A lightweight toolkit designed for developers who want to style apps via "scripting" (applying shorthand classes) rather than writing traditional CSS files. These files are optimized for direct injection into your projects via CDN.

> [!WARNING]
> **Status: Experimental.** This repository reflects a personal workflow and is in active development. Class names, naming conventions, and values are subject to change without notice. Use in production at your own risk!

---

## 🚀 How to Use

GitHub serves raw files as `text/plain`, which browsers block for security. To use these utilities, use the **jsDelivr** CDN link to ensure the correct `text/css` MIME type.

### 1. Link via jsDelivr
Add the following to your `<head>` tag.

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/jameshuntt/fast_css@main/full.css">
```

### 2. Implementation: Script-Like Styling (JS/React)
Because these utilities are "atomic," you can group them in your JavaScript for cleaner components and better reusability. This "Composite Group" approach keeps your HTML clean and allows for global design updates.

```javascript
// Define your "Styles" as scripts
const layout = "dfr jcsb bgb cw p24"; 
const actionBtn = "poi br8 p12 bgb cw fs16p";

// Use them in your UI
function App() {
  return (
    <header className={layout}>
      <h1 className="fw700">fast_css</h1>
      <button className={actionBtn}>Click Me</button>
    </header>
  );
}
```

---

## 🛠 Shorthand Cheat Sheet

| Category | Class | CSS Property |
| :--- | :--- | :--- |
| **Flexbox** | `.df` / `.dfr` / `.dfc` | display: flex / row / column |
| **Alignment** | `.jcc` / `.jcsb` / `.jcse` | justify-content: center / between / evenly |
| **Colors** | `.bgb` / `.bgw` | background: black / white |
| **Text Color** | `.cb` / `.cw` | color: black / white |
| **Sizing** | `.w100p` / `.vh` / `.w40px` | width: 100% / height: 100vh / fixed |
| **Typography** | `.fw700` / `.fs32px` / `.centext` | font-weight / font-size / text-align |

---

## 🍱 Presets (Combined Types)
You can define compound classes at the bottom of your CSS file to act as "shortcuts" for common patterns.

| Class | Included Utilities | Purpose |
| :--- | :--- | :--- |
| `.nav-row` | `dfr`, `jcsb`, `aic` | Standard header/navigation layout. |
| `.flex-center` | `df`, `jcc`, `acc` | Perfectly centers content in a container. |
| `.hero-dark` | `dfc`, `jcc`, `bgb`, `cw` | Full-width black section with centered white text. |

---

## 📖 Local Development

```bash
# 1. Clone the repo
git clone https://github.com/jameshuntt/fast_css.git

# 2. Push changes to GitHub
git add .
git commit -m "Update flex utilities"
git push origin main
```

> **Note:** It may take a few minutes for the jsDelivr CDN cache to update after you push changes to your GitHub repository.

---

## 📄 License
This project is licensed under the MIT License.
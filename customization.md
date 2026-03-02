# 🛠 Customize & Create Your Own fast_css

`fast_css` is designed to be a foundation. The best way to use it is to fork it, add your own "crazy" precision classes, and host your own personal version of the library.

---

## 🚀 How to Fork and Deploy

### 1. Fork the Repo
Click the **Fork** button at the top right of this GitHub page. This creates a copy of the toolkit under your own GitHub account (e.g., `github.com/your-username/fast_css`).

### 2. Add Your Own "Script" Classes
Clone your fork locally and add the specific values you need for your projects.

```bash
git clone https://github.com/your-username/fast_css.git
cd fast_css
```

Open `style.css` and add your custom utilities:
```css
/* My personal brand colors */
.bg-brand { background: #007bff; }

/* My specific layout fixes */
.mt-neg-12 { margin-top: -12px; }
.lh-ultra-tight { line-height: 1.1; }
```

### 3. Push to GitHub
```bash
git add .
git commit -m "Add custom brand and layout utilities"
git push origin main
```

---

## 🌐 Your Personal CDN Link

Once you push your changes, your custom library is live. You can call it in any project using **jsDelivr**. 

Replace `your-username` with your GitHub handle:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/your-username/fast_css@main/style.css">
```

---

## 💡 Why Fork This?

* **No Build Step:** You get the power of utility-first CSS without ever running `npm install` or setting up a compiler.
* **AI Integration:** You can give your personal CDN link to any AI tool and say: *"Style this page using my shorthand classes found at this URL."*
* **Legacy Support:** Keep your "crazy" precision classes (like `.lh73p6px`) in your own repo so your older projects never break, even if the main `fast_css` repo updates.

---

## 📄 License
MIT
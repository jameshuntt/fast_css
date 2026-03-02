# Demo: fast_css in Action ⚡

This `index.html` file demonstrates how to use `fast_css` to build a clean, dark-mode card layout in seconds using nothing but shorthand "script-like" utility classes.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>fast_css Demo</title>
    
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/jameshuntt/fast_css@main/style.css">
    
    <style>
        /* Optional: Adding a font so it looks extra clean */
        body { font-family: sans-serif; }
    </style>
</head>
<body class="bgb cw vh100 df jcc acc">

    <div class="dfc p24 br12 bgw cb shadow-lg w40px" style="width: 350px;">
        
        <h1 class="fs24p mb8px fw700">fast_css⚡</h1>
        
        <p class="fs16p cb mb20px lh1p15">
            This card was built using rapid script-like styling. 
            No custom CSS files were harmed in the making of this UI.
        </p>

        <div class="dfr jcsb aic mt24">
            <span class="fs1p1r fw700">$0.00</span>
            <button class="p12p24p bgb cw br8 poi border-0 fs16p">
                Get Started
            </button>
        </div>

    </div>

</body>
</html>
```

---

### Why this works:
* **The Body:** `.bgb .cw .vh100 .df .jcc .acc` — In one line of "scripting," you've created a full-screen dark background and perfectly centered your content.
* **The Card:** `.dfc .p24 .br12 .bgw .cb` — You instantly swapped the color context back to a white card with black text, added padding, and rounded the corners.
* **The Button:** `.p12p24p` — Uses your custom "crazy" padding to get that perfect button shape without writing a single CSS rule.

---

## 📄 How to use this Demo
1. Create a file named `index.html`.
2. Paste the code block above.
3. Open it in your browser. 
4. **Enjoy the speed.**
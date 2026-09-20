# Crisp Studio — Brand Assets & Emailer Logos

This repository hosts official brand logos and icons for Crisp Studio, optimized for HTML emailers, email signatures, newsletters, and web applications.

---

## 🚀 Push to GitHub (One-time setup)

1. Create a public repository named **`crisp-brand-assets`** on GitHub:
   👉 **[Click here to create the repository](https://github.com/new?name=crisp-brand-assets&public=true)**
   *(Ensure visibility is set to **Public** so email clients can display the images without requiring authentication).*

2. Link and push the repository from your terminal:
   ```bash
   cd /Users/parthgupta/.gemini/antigravity/scratch/crisp-brand-assets
   git remote add origin https://github.com/parthg61/crisp-brand-assets.git
   git branch -M main
   git push -u origin main
   ```

---

## 🔗 Direct CDN Links (Once pushed)

We recommend using the **jsDelivr CDN** URLs because they are globally cached, load in milliseconds, and never hit GitHub rate limits.

| Asset | jsDelivr CDN Link (Recommended) | GitHub Raw Link |
| :--- | :--- | :--- |
| **Full Colour Logo** | `https://cdn.jsdelivr.net/gh/parthg61/crisp-brand-assets@main/logos/crisp-logo-fullcolour.png` | `https://raw.githubusercontent.com/parthg61/crisp-brand-assets/main/logos/crisp-logo-fullcolour.png` |
| **Mono Navy Logo** | `https://cdn.jsdelivr.net/gh/parthg61/crisp-brand-assets@main/logos/crisp-logo-mono-navy.png` | `https://raw.githubusercontent.com/parthg61/crisp-brand-assets/main/logos/crisp-logo-mono-navy.png` |
| **Mono Orange Logo** | `https://cdn.jsdelivr.net/gh/parthg61/crisp-brand-assets@main/logos/crisp-logo-mono-orange.png` | `https://raw.githubusercontent.com/parthg61/crisp-brand-assets/main/logos/crisp-logo-mono-orange.png` |
| **Mono Black Logo** | `https://cdn.jsdelivr.net/gh/parthg61/crisp-brand-assets@main/logos/crisp-logo-mono-black.png` | `https://raw.githubusercontent.com/parthg61/crisp-brand-assets/main/logos/crisp-logo-mono-black.png` |
| **Mono White Logo** | `https://cdn.jsdelivr.net/gh/parthg61/crisp-brand-assets@main/logos/crisp-logo-mono-white.png` | `https://raw.githubusercontent.com/parthg61/crisp-brand-assets/main/logos/crisp-logo-mono-white.png` |
| **Avatar / Icon (Orange)** | `https://cdn.jsdelivr.net/gh/parthg61/crisp-brand-assets@main/logos/crisp-avatar-orange.png` | `https://raw.githubusercontent.com/parthg61/crisp-brand-assets/main/logos/crisp-avatar-orange.png` |
| **Avatar / Icon (Navy)** | `https://cdn.jsdelivr.net/gh/parthg61/crisp-brand-assets@main/logos/crisp-avatar-navy.png` | `https://raw.githubusercontent.com/parthg61/crisp-brand-assets/main/logos/crisp-avatar-navy.png` |

---

## 📧 Emailer Copy-Paste Snippets

### 1. Standard Email Header / Signature (Full Colour)
```html
<a href="https://kakhaga.co.in" target="_blank" style="text-decoration: none; display: inline-block;">
  <img 
    src="https://cdn.jsdelivr.net/gh/parthg61/crisp-brand-assets@main/logos/crisp-logo-fullcolour.png" 
    alt="Crisp Studio" 
    width="150" 
    style="display: block; width: 150px; max-width: 100%; height: auto; border: 0; outline: none; text-decoration: none;" 
  />
</a>
```

### 2. Compact Square Avatar / Icon
```html
<img 
  src="https://cdn.jsdelivr.net/gh/parthg61/crisp-brand-assets@main/logos/crisp-avatar-orange.png" 
  alt="Crisp Studio" 
  width="48" 
  height="48" 
  style="display: block; width: 48px; height: 48px; border: 0; outline: none; border-radius: 8px;" 
/>
```

---

## 💡 Why PNG instead of SVG for Emailers?
* Major email clients (including **Gmail** web/apps and desktop **Outlook**) automatically strip or block `<svg>` images for security reasons.
* High-resolution transparent **PNG** images at 2× pixel density provide 100% email client compatibility while remaining crisp on high-DPI (Retina) mobile screens.

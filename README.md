# Crisp Studio — Complete Brand Assets & Emailer Kit

This repository hosts all official brand assets, logos, favicons, and watermarks for **Crisp Studio**, optimized for HTML emailers, email signatures, newsletters, web apps, and print.

---

## 🚀 Quick Push to GitHub

1. Create a public repository named **`crisp-brand-assets`** on GitHub:
   👉 **[Click here to create the repository](https://github.com/new?name=crisp-brand-assets&public=true)**  
   *(Ensure visibility is set to **Public** so email clients can display the images without authentication).*

2. Push all assets from your terminal:
   ```bash
   cd /Users/parthgupta/.gemini/antigravity/scratch/crisp-brand-assets
   git remote add origin https://github.com/parthg61/crisp-brand-assets.git
   git branch -M main
   git push -u origin main
   ```

---

## 🔗 Direct CDN Links (All Assets)

Use the **jsDelivr CDN** links for fastest loading, global caching, and high email deliverability.

### 1. Primary Logos (Email-Ready Transparent PNGs)
| Asset Name | jsDelivr CDN Link (Recommended) |
| :--- | :--- |
| **Full Colour Logo** | `https://cdn.jsdelivr.net/gh/parthg61/crisp-brand-assets@main/logos/crisp-logo-fullcolour.png` |
| **Mono Navy Logo** | `https://cdn.jsdelivr.net/gh/parthg61/crisp-brand-assets@main/logos/crisp-logo-mono-navy.png` |
| **Mono Orange Logo** | `https://cdn.jsdelivr.net/gh/parthg61/crisp-brand-assets@main/logos/crisp-logo-mono-orange.png` |
| **Mono Black Logo** | `https://cdn.jsdelivr.net/gh/parthg61/crisp-brand-assets@main/logos/crisp-logo-mono-black.png` |
| **Mono White Logo** *(Dark mode)* | `https://cdn.jsdelivr.net/gh/parthg61/crisp-brand-assets@main/logos/crisp-logo-mono-white.png` |
| **Logo V01 (Alt)** | `https://cdn.jsdelivr.net/gh/parthg61/crisp-brand-assets@main/logos/logo-v01.png` |
| **Logo V02 (Alt)** | `https://cdn.jsdelivr.net/gh/parthg61/crisp-brand-assets@main/logos/logo-v02.png` |
| **Logo V02.1 (Alt)** | `https://cdn.jsdelivr.net/gh/parthg61/crisp-brand-assets@main/logos/logo-v02-1.png` |

### 2. Avatars & Favicons
| Asset Name | jsDelivr CDN Link (Recommended) |
| :--- | :--- |
| **Avatar Orange** | `https://cdn.jsdelivr.net/gh/parthg61/crisp-brand-assets@main/logos/crisp-avatar-orange.png` |
| **Avatar Navy** | `https://cdn.jsdelivr.net/gh/parthg61/crisp-brand-assets@main/logos/crisp-avatar-navy.png` |
| **Favicon Transparent** | `https://cdn.jsdelivr.net/gh/parthg61/crisp-brand-assets@main/logos/crisp-favicon-transparent.png` |

### 3. Watermarks & Badges ("Made By Crisp")
| Asset Name | jsDelivr CDN Link (Recommended) |
| :--- | :--- |
| **MadeBy Pill (Navy)** | `https://cdn.jsdelivr.net/gh/parthg61/crisp-brand-assets@main/watermarks/crisp-madeby-pill-navy.png` |
| **MadeBy Pill (White)** | `https://cdn.jsdelivr.net/gh/parthg61/crisp-brand-assets@main/watermarks/crisp-madeby-pill-white.png` |
| **MadeBy Transparent (Navy)** | `https://cdn.jsdelivr.net/gh/parthg61/crisp-brand-assets@main/watermarks/crisp-madeby-transparent-navy.png` |
| **MadeBy Transparent (White)** | `https://cdn.jsdelivr.net/gh/parthg61/crisp-brand-assets@main/watermarks/crisp-madeby-transparent-white.png` |
| **MadeBy Overlay White (45%)** | `https://cdn.jsdelivr.net/gh/parthg61/crisp-brand-assets@main/watermarks/crisp-madeby-overlay-white45.png` |

### 4. Original Vector SVGs
Vector files are available under `svgs/logos/`, `svgs/favicons/`, and `svgs/watermarks/`. Example:
* `https://cdn.jsdelivr.net/gh/parthg61/crisp-brand-assets@main/svgs/logos/Crisp_Logo_FullColour.svg`

---

## 📧 Emailer Copy-Paste Snippets

### Standard Email Logo Header
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

### Email Footer "Made By" Watermark Badge
```html
<a href="https://kakhaga.co.in" target="_blank" style="text-decoration: none; display: inline-block;">
  <img 
    src="https://cdn.jsdelivr.net/gh/parthg61/crisp-brand-assets@main/watermarks/crisp-madeby-pill-navy.png" 
    alt="Made by Crisp Studio" 
    width="130" 
    style="display: block; width: 130px; height: auto; border: 0; outline: none;" 
  />
</a>
```

### Square Avatar (48×48px)
```html
<img 
  src="https://cdn.jsdelivr.net/gh/parthg61/crisp-brand-assets@main/logos/crisp-avatar-orange.png" 
  alt="Crisp" 
  width="48" 
  height="48" 
  style="display: block; width: 48px; height: 48px; border: 0; outline: none; border-radius: 8px;" 
/>
```

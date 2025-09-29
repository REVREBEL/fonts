# REVREBEL Fonts

This repository contains the official **REVREBEL brand fonts**, optimized for modern web use. Fonts are served via **jsDelivr CDN** or GitHub Pages. Each font family includes only the **approved weights** for consistent branding.

---

## 📚 Font Families & Approved Weights

### **Khand**  
- Weights: **500–700**  
- Usage: Headlines, bold accents

### **Fira Code**  
- Weights: **300–500**  
- Usage: Technical/code snippets, monospaced contexts

### **General Sans**  
- Weights: **300–500**  
- Usage: Body text, clean UI typography

### **Noto Emoji**  
- Weights: **700 only**  
- Usage: Emoji fallback and enhancements

### **Pacifico**  
- Weights: **400 only**  
- Usage: Decorative script, limited brand accents

### **Barlow**  
- Weights: **800–900**  
- Usage: Display, bold headers

---

## 🛠 Usage Examples

### Variable Font Example
```css
.my-heading {
  font-family: 'Khand', Impact;
  font-weight: 600; /* value within approved range 500–700 */
  font-style: normal;
}
```

### Static Font Example
```css
.my-subhead {
  font-family: 'Barlow', Impact;
  font-weight: 900; /* approved Black */
  font-style: normal;
}
```

### Load via `<link>`
```html
<link rel="preconnect" href="https://cdn.jsdelivr.net" crossorigin>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/REVREBEL/fonts@main/rebel-fonts.css">
```

### Load via `@import`
```css
@import url('https://cdn.jsdelivr.net/gh/REVREBEL/fonts@main/rebel-fonts.css');
```

---

## 📜 Licenses

All fonts are licensed under the **SIL Open Font License 1.1** or equivalent open license. Please review the individual font licenses before redistribution.

- **Khand** — © Indian Type Foundry — [Fontshare](https://www.fontshare.com/fonts/khand)
- **Fira Code** — © The Fira Code Project Authors — [GitHub](https://github.com/tonsky/FiraCode)
- **General Sans** — © Indian Type Foundry — [Fontshare](https://www.fontshare.com/fonts/general-sans)
- **Noto Emoji** — © Google LLC — [Google Fonts](https://fonts.google.com/noto/specimen/Noto+Emoji)
- **Pacifico** — © The Pacifico Project Authors — [GitHub](https://github.com/googlefonts/Pacifico)
- **Barlow** — © The Barlow Project Authors — [GitHub](https://github.com/jpt/barlow)

---

## ⚡ Best Practices

- Always preload **woff2** versions for performance:
  ```html
  <link rel="preload" as="font" href="https://cdn.jsdelivr.net/gh/REVREBEL/fonts@main/khand/khand-variable.woff2" type="font/woff2" crossorigin>
  ```
- Use only **approved weights** to maintain brand consistency.
- When using fallbacks, prefer the **closest web-safe font**:
  - Khand → Impact
  - Fira Code → Consolas
  - General Sans → Arial
  - Noto Emoji → Segoe UI Emoji
  - Pacifico → cursive
  - Barlow → Impact


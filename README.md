# 🏠 Property Poster Writer (Demo)

> **Live Demo:** [https://ebby74.github.io/property-poster-writer/](https://ebby74.github.io/property-poster-writer/)  
> **Alternate Vercel Mirror:** [https://rapid-platinum-yw6bo11.tmp.now](https://rapid-platinum-yw6bo11.tmp.now)

A lightweight, bold, and mobile-friendly single-page web app built for Malaysian real estate agents and owners to turn property details into ready-to-post messages and high-resolution downloadable social graphics in seconds.

---

## 🌟 Key Features

1. **⚡ Instant Reactive Poster Generator:**
   - 3 stacked sections down one screen (Property Details, Poster Preview, Edit & Copy).
   - Immediate live updates on every input change with zero lag.

2. **🇲🇾 Malaysian Sample Entries Built-in:**
   - **Cecawi 6 KD:** 2-Storey Landed Terrace House in Kota Damansara (`Cecawi 6 KD.jpg`).
   - **Bilik Sewa Keramat:** Muslimah room rental flyer in Kg. Datuk Keramat (`BilikSewaKeramat.jpg`).
   - **Villa Gombak:** Modern landed semi-D with grand porch & garden (`Gombak.jpg`).

3. **🔄 Instant Sale / Rent Toggle:**
   - Immediately alters badges, price placeholders, headline verbs, and copy format.

4. **📱 Multi-Platform Copywriting Switcher:**
   - **🟢 WhatsApp:** Formatted with bold bullet points (`*bold*`), emojis, and instant viewing CTA.
   - **🔵 Facebook Groups:** Long-form engaging hook with property specs, perks, and local hashtags (`#RumahUntukDijual`, `#SubsaleKL`).
   - **🟣 Instagram & TikTok:** Punchy aesthetic caption with DM/bio callouts and trending tags.

5. **🎨 1-Click High-Res PNG Poster Export:**
   - Directly renders a high-definition `1080x1350` graphic card on HTML5 Canvas ready for Instagram, Facebook, and WhatsApp.

6. **📸 Custom Photo Upload:**
   - Drag & drop or upload any property photo from your phone or PC (processed completely client-side via `FileReader`).

---

## 🛠️ Tech Stack

- **Pure Vanilla Web Stack:** Single self-contained [`index.html`](index.html) (HTML5, Responsive CSS3 Grid/Flexbox, Vanilla JS).
- **Zero Dependencies:** No npm, no node_modules, no build step, no framework.
- **Hosted On:** GitHub Pages & Vercel.

---

## 🚀 Running Locally

Simply double-click [`index.html`](index.html) to open in any web browser, or serve via Python:

```bash
python3 -m http.server 3000
```
Open [http://localhost:3000](http://localhost:3000) in your browser.

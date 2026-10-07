<div align="center">

# 🔮 AstroTamil

**A bilingual (Tamil / English) Vedic astrology platform that calculates real sidereal planetary positions in the browser and explains them in plain language.**

[![Live Demo](https://img.shields.io/badge/Live_Demo-astrotamil.pages.dev-7c3aed?style=for-the-badge)](https://astrotamil.pages.dev/)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Languages](https://img.shields.io/badge/Tamil_%7C_English-0f172a?style=for-the-badge)

</div>

---

## 📖 Overview

AstroTamil is an end-to-end astronomical calculation engine with an AI interpretation layer on top. It computes planetary positions, Nakshatra placements and Vimshottari Dasha timelines directly in the browser, then presents readable predictions in Tamil or English.

## ✨ Features

- 🪐 **Sidereal calculation engine** for planetary positions and Lagna
- ⭐ **Nakshatra placements** and **Vimshottari Dasha** timelines
- 🔍 **Automatic Dosha and Yoga detection** across chart combinations
- 🤖 **AI-assisted interpretation** of horoscope results
- 📍 **Birthplace search** with real-time geocoding and timezone lookup
- 🗓️ **Panchangam**, Rasi summary and South Indian style Rasi chart
- 🌐 **Bilingual UI** (Tamil / English) with a persistent language toggle
- 🌗 **Dark / light themes** and saved birth profiles
- 🖨️ **Print-friendly reports** via `@media print` styles

## 🧮 Technical Notes

- **Time corrections:** ΔT (UT → TT) correction using Espenak / Meeus polynomials
- **i18n:** `data-i18n` attribute tagging, a small translation helper, and a sweep engine for dynamically generated content
- **Persistence:** language, theme and profiles stored in `localStorage`
- **Geocoding:** Photon API with `tz-lookup` for timezones
- **Responsive typography:** fluid sizing with `clamp()`

## 🚀 Run Locally

The app is a self-contained web page, so no build step is needed.

```bash
git clone https://github.com/barathraj0812/Astro.git
cd Astro
# open the HTML file in your browser, or serve it locally:
npx serve .
```

## 🛠️ Tech Stack

`JavaScript` · `HTML5` · `CSS3` · `Astronomical algorithms` · `Geocoding API` · `localStorage`

## ⚠️ Disclaimer

AstroTamil is built for learning and cultural interest. Interpretations are not professional advice.

## 🙋 Author

**Barath Raj M** · Class XI student developer, Chennai
[Portfolio](https://barath.pages.dev) · [GitHub](https://github.com/barathraj0812)

---

<div align="center">Built independently · தமிழ் & English</div>

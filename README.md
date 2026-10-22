# Doro !Nawas Conservancy — "Where the Rhinos Roam"

Official multi-page website for **Doro !Nawas Conservancy** in Damaraland, Kunene Region, Namibia.

In the indigenous Khoekhoegowab (Damara) language, **"Doro !Nawas"** translates literally to *"the place where rhinos roam"* (hence the project URL slug `rhino-roam`). Spanning 407,300 hectares (4,073 km²) of unfenced wilderness, Doro !Nawas is home to the world's largest population of free-roaming desert-adapted black rhinos, desert elephants, and the UNESCO World Heritage rock art of Twyfelfontein.

---

## 🌍 Website Overview & Multipage Structure

The website is engineered as a responsive, lightweight, accessible multi-page platform with zero build dependencies, compatible with all static hosting providers (GitHub Pages, Netlify, Vercel, S3, Cloudflare Pages, Apache, Nginx):

| Page | File | Description |
| :--- | :--- | :--- |
| **Home** | [`index.html`](index.html) | Panoramic hero, official logo emblem, core pillars, stats counters, narrative of Doro !Nawas, and highlights. |
| **Rhino Conservation** | [`rhino-conservation.html`](rhino-conservation.html) | Deep-dive into *Rhino Roam*, desert black rhino biology, Save the Rhino Trust (SRT) partnership, and Community Rhino Ranger patrols. |
| **Wildlife & Safari** | [`wildlife-safari.html`](wildlife-safari.html) | Desert elephants, Hartmann's mountain zebras, safari expeditions, Wilderness Doro Nawas lodge, and rooftop stargazing. |
| **Cultural Heritage** | [`cultural-heritage.html`](cultural-heritage.html) | Twyfelfontein (/Ui-//aes) UNESCO World Heritage petroglyphs, Damara (ǂNūkhoen) culture, Living Museum, and geological landmarks. |
| **Community Projects** | [`community-projects.html`](community-projects.html) | Communal governance (CBNRM), elephant-safe water dams, predator-proof kraals, youth bursaries, and healthcare support. |
| **Visual Gallery** | [`gallery.html`](gallery.html) | Interactive filterable photo gallery (Rhinos, Elephants, Landscapes, Culture) with lightbox viewing. |
| **Plan Your Visit** | [`contact.html`](contact.html) | Self-drive routes from Windhoek & Swakopmund, Doro Nawas airstrip details, interactive permit inquiry form, and FAQ accordion. |

---

## 🎨 Design & Brand Identity

- **Color Palette**:
  - **Royal Navy / Deep Ocean**: `#0b1a30`, `#060e1a` (Honoring the badge's zenith sky)
  - **Desert Ochre Gold**: `#d4a359`, `#e6be7e`, `#b0823c` (Matching the golden star, mountain peaks, and typography)
  - **Damaraland Basalt & Terracotta**: `#c05c38`, `#1a222c`
  - **Ivory & Sandstone**: `#fbf9f5`, `#f3efe6`
- **Typography**:
  - Headings: `Cinzel` & `Cormorant Garamond` (Classic African heritage and elegance)
  - Body: `Manrope` (Clean, legible, modern sans-serif)
- **Features**:
  - Full mobile responsiveness with slide-out drawer menu
  - IntersectionObserver animated statistics counters
  - Interactive category-filtered image gallery
  - Modal image lightbox with keyboard accessibility (`Esc` to close)
  - Accordion FAQ for visiting guidelines
  - Interactive visit inquiry and permit booking form

---

## 🚀 Local Development & Preview

Open `index.html` directly in any web browser or serve locally using Python:

```bash
# Python 3
python -m http.server 8000
```

Navigate to `http://localhost:8000`.

---

## 📄 License & Credits

- **Emblem**: Official Doro !Nawas Conservancy Emblem (`assets/images/logo.png`)
- **Conservation Partners**: Save the Rhino Trust (SRT), NACSO (Namibian Association of CBNRM Support Organisations), Ministry of Environment, Forestry and Tourism (MEFT).
- **Copyright**: &copy; 2026 Doro !Nawas Conservancy, Republic of Namibia.

# johnmoss.co

Personal website for John Moss — 4th generation cranberry farmer, systems builder, and agricultural technology innovator.

## Quick Start

```bash
# Run any concept locally
cd concepts/concept-01
npm install
npm run dev
```

Each concept runs on its own port (default: 4321).

## The 10 Concepts

| # | Name | Description |
|---|------|-------------|
| 01 | Classic Serif | Traditional editorial with Playfair Display. Warm, timeless, legacy feel. |
| 02 | Swiss Minimalist | Clean grid-based Inter font. Precise, engineered, annual report feel. |
| 03 | Earth & Agriculture | Warm earth tones, forest green. Connected to the land but modern. |
| 04 | Tech Executive | DM Sans, sharp lines. Modern founder page meets tech startup. |
| 05 | Academic/Research | Scholarly Libre Baskerville. Numbered sections, citation-like. |
| 06 | Single Page Scroll | Everything on one scroll. IBM Plex Sans. Mobile-first. |
| 07 | Card-Based | Modular cards with Manrope. Portfolio-style project showcase. |
| 08 | Dark Mode | Near-black background, Space Grotesk. Premium, modern. |
| 09 | Two-Column Sidebar | Fixed navigation sidebar. Work Sans. Documentation-style. |
| 10 | Ultra Minimal | System fonts, no decoration. Raw, brutalist, text-only. |

## 🏆 Top 2 Recommendations

### **Concept 02: Swiss Minimalist** ⭐ Primary Recommendation

Best fit for the stated audience (board members, partners, investors). The grid-based layout and precise typography communicate competence without trying too hard. Clean, professional, credibility-first.

**Why it works:**
- Projects authority without flash
- Easy to scan for busy professionals
- Timeless — won't look dated in 3 years
- Information hierarchy is immediately clear

### **Concept 04: Tech Executive** ⭐ Runner-Up

Best if you want to emphasize the technology/startup angle. More modern feel while still being professional. Good for audiences who expect founder pages to look like other tech founders.

**Why it works:**
- Balances agriculture + tech identity
- Familiar pattern for investors
- Strong visual hierarchy
- Slightly more personality than 02

## Not Recommended

- **Concept 05 (Academic)**: Too scholarly for the audience
- **Concept 08 (Dark Mode)**: Can feel "tech bro" rather than trusted operator
- **Concept 10 (Ultra Minimal)**: Risks looking unfinished to unfamiliar visitors

## Deployment

Each concept can be deployed to any static host:

```bash
cd concepts/concept-02  # or your chosen concept
npm run build
# Deploy the ./dist folder
```

**Recommended hosts:**
- Vercel (zero config)
- Netlify (zero config)
- Cloudflare Pages (fast)
- GitHub Pages (free)

## File Structure

```
johnmoss.co/
├── concepts/
│   ├── concept-01/        # Classic Serif
│   ├── concept-02/        # Swiss Minimalist ⭐
│   ├── concept-03/        # Earth & Agriculture
│   ├── concept-04/        # Tech Executive ⭐
│   ├── concept-05/        # Academic/Research
│   ├── concept-06/        # Single Page Scroll
│   ├── concept-07/        # Card-Based
│   ├── concept-08/        # Dark Mode
│   ├── concept-09/        # Two-Column Sidebar
│   └── concept-10/        # Ultra Minimal
└── README.md
```

## Next Steps

1. Review concepts locally (`npm run dev`)
2. Pick favorite (recommend #02 or #04)
3. Add additional pages (About, Projects, Contact)
4. Replace placeholder content
5. Deploy to johnmoss.co

---

Built with [Astro](https://astro.build) — static-first, fast, low maintenance.

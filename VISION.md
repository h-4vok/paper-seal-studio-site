# 🦭 VISION.md: The Paper Seal Studio
## Digital Presence Strategy & Architecture

> **Tagline:** "You Will Feel The Difference."
> **Ethos:** Discernment over consumption. Gallery-grade artistry over mass-market prints.
> **Location:** Eastbourne, East Sussex.

---

## 1. BRAND ESSENCE & PSYCHOLOGY (The Sutherland Approach)
* **The Signal:** We don't sell "prints"; we sell **Archival Studio Pieces**. The site must signal "High Value" through whitespace, high-end typography, and macro-photography.
* **The Distinction:** We target the discerning middle-upper class. They don't buy "decor"; they buy a piece of East Sussex history on museum-grade paper (310gsm German Etching).
* **The "Seal":** Use the concept of the "Seal" as both the animal and the physical rubber stamp guarantee of authenticity.

---

## 2. NAVIGATION ARCHITECTURE (The Sitemap)

### Menu (Option A - Curated)
1. **Exhibitions** (The Gallery/Store)
2. **The Studio** (About & Commitment)
3. **Find Us** (Fair Calendar)
4. **Care & Framing** (Value-add content)

### Folder Structure (Hugo)
```text
/content
├── _index.md (Home: The Sensory Arrival)
├── /exhibitions
│   ├── _index.md (Collection view)
│   └── piece-name.md (Individual showcase)
├── /the-studio
│   └── index.md (The Artist + The Commitment Manifest)
├── /find-us
│   └── index.md (Interactive Fair Calendar)
└── /care-and-framing
    └── index.md (Educational content on Float Mounts & Preservation)
```

---

## 3. KEY PAGE STRATEGIES

### A. The Home (Hero Moment)
* **Visual:** Macro shot of paper grain or the deep Navy Blue ink being stamped.
* **Goal:** Immediate sensory impact. Establish "You Will Feel The Difference."

### B. The Exhibition (Collection)
* **Layout:** Editorial grid. High-vibrancy images.
* **Mockups:** Prints must be shown in "Discerning Homes" (Victorian/Georgian interiors, art-filled libraries, stone-top kitchens). Never "naked" JPGs.

### C. Individual Piece (The Showcase)
* **Visual:** "Apabullante". Screen-filling vibrance.
* **Data Points (Front Matter):** Vibe (Serene, Atmospheric, etc.), Story, Technical Specs.
* **CTA:** "Reserve for Pickup" (WhatsApp Concierge flow).

### D. The Studio Commitment (The Manifest)
* **Transparency:** Explain the 310gsm cotton paper.
* **Risk Reversal:** "We are a studio, not a factory." If you don't feel the quality, we solve it. No questions asked.
* **The Sello:** Show the manual process.

---

## 4. CONVERSION & TECH STACK (The Lean Method)
* **Platform:** Hugo (Static, Fast, Exclusive).
* **Sales Flow:** No traditional cart.
  1. User clicks "Reserve for Pickup" -> WhatsApp.
  2. Artist confirms availability.
  3. Payment link (Stripe/SumUp) for deposit/full price.
* **Fair Strategy:** Use the site to drive foot traffic. "Touch the paper at our next fair."

---

## 5. DESIGN GUIDELINES (Visual Cues)
* **Primary Color:** Navy Blue (`#000080` or specific logo hex).
* **Secondary Color:** Paper White / Bone (`#F9F7F2`).
* **Typography:** Sophisticated sans-serif (geometrical like Montserrat/Gotham) for UI. High-contrast serif for titles.
* **Photography:** High contrast, natural light, emphasizing texture and "The Spirit of East Sussex".

---

## 6. FRONT MATTER REQUIREMENTS (Hugo)
```yaml
title: "Piece Name"
collection: "Launch Collection"
vibe: ["Serene", "Coastal"]
paper: "Hahnemühle German Etching 310gsm"
sizes: ["7x5", "A4", "A3"]
status: "Available"
fair_exclusive: true
```

# BRIEF — Avtoličarstvo Draksler

## Business Info
- **Name:** Draksler Izidor s.p. — Avtoličarstvo
- **Owner:** Izidor Draksler
- **Industry:** Avtoličarstvo (auto body painting & repair)
- **Location:** Zasavska cesta 36B, 4000 Kranj, Slovenija
- **Phone:** 041 312 231
- **Email:** dore.draksler@gmail.com
- **Established:** Since 2010 (Draksler d.o.o. registered 14.05.2010)
- **Language:** Slovenian (all text in Slovenian)

## About the Business
Professional auto body painting and repair shop in Kranj, Slovenia. Specializing in car body painting (lakiranje), dent repair, and complete bodywork restoration. Long-established local business with over 14 years of experience.

## Page Structure (Single Page, Slovenian)

### 1. HERO SECTION
- **Headline:** "Vrhunsko avtoličarstvo v Kranju"
- **Subheadline:** "Profesionalno lakiranje, popravilo vdolbin in celovita obnova karoserije"
- **CTA:** "Pokličite za brezplačno oceno" → tel:041312231
- Dark dramatic background with automotive feel

### 2. O NAS (About)
- "Več kot 14 let izkušenj v avtoličarstvu"
- Family-run, precise craftsmanship
- Personal attention, every car treated with care
- Kranj-based, serving Gorenjska region

### 3. STORITVE (Services)
Cards/grid:
1. **Lakiranje vozil** — Popolno ali delno lakiranje vseh vrst vozil
2. **Popravilo vdolbin** — Strokovna odprava vdolbin in poškodb karoserije
3. **Obnova karoserije** — Celovita obnova poškodovanih delov karoserije
4. **Barvno usklajevanje** — Natančno ujemanje originalnega odtenka barve
5. **Antikorozijska zaščita** — Dolgotrajna zaščita pred rjo in korozijo
6. **Poliranje in zaščita laka** — Profesionalno poliranje za sijoč videz

### 4. ZAKAJ MI (Why Choose Us)
Stats section:
- 14+ let izkušenj
- 1000+ zadovoljnih strank
- 100% strokovno delo
- Garancija na opravljeno delo

### 5. POSTOPEK (Process)
Steps:
1. Brezplačen pregled in ocena → 2. Priprava ponudbe → 3. Strokovno delo → 4. Kontrola kakovosti → 5. Predaja vozila

### 6. KONTAKT (Contact)
- Phone: 041 312 231
- Email: dore.draksler@gmail.com
- Address: Zasavska cesta 36B, 4000 Kranj
- Map embed or direction link
- Working hours: Pon–Pet: 7:00–16:00

## Design Direction

### Style
Motion-driven, bold, masculine, professional. Think premium auto shop — not a generic business page.

### Colors
- **Primary background:** `#1E293B` (dark slate)
- **Secondary:** `#334155` (slate)
- **CTA/Accent:** `#DC2626` (action red)
- **Light sections:** `#F8FAFC` (off-white)
- **Text:** `#0F172A` (near black on light), `#F1F5F9` (light on dark)

### Typography (Google Fonts)
- **Headings:** Syncopate (wide, bold, automotive feel)
- **Body:** Space Mono (technical, precise) — but use it for small labels/captions only
- **Body text:** DM Sans (readable for paragraphs)
- Load: `https://fonts.googleapis.com/css2?family=Syncopate:wght@400;700&family=Space+Mono:wght@400;700&family=DM+Sans:ital,wght@0,400;0,500;0,700;1,400&display=swap`

### Layout
- Full-width dark hero with dramatic diagonal lines or metallic texture
- Alternating dark/light sections
- Service cards with red accent borders
- Stats section with animated counters
- Process section as horizontal steps
- Contact section with bold CTA

### Animation
- GSAP + ScrollTrigger for scroll reveals
- Parallax on hero background (0.3x speed)
- SplitText character reveal on hero headline
- Counter animations for stats (14+, 1000+, etc.)
- Stagger reveals for service cards
- Lenis smooth scrolling
- prefers-reduced-motion: respect it!

### Anti-patterns
- ❌ No emojis as icons (use SVG from Lucide/Heroicons)
- ❌ No stock photos of random cars
- ❌ No purple/pink gradients
- ❌ No Inter/Roboto for headings
- ❌ No opacity:0 in CSS for content (let GSAP handle initial state)

### CDN Libraries
```html
<script src="https://cdn.jsdelivr.net/npm/gsap@3/dist/gsap.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/gsap@3/dist/ScrollTrigger.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/gsap@3/dist/SplitText.min.js"></script>
<link rel="stylesheet" href="https://unpkg.com/lenis@latest/dist/lenis.css">
<script src="https://unpkg.com/lenis@latest/dist/lenis.min.js"></script>
```

### SVG Icons
Use inline SVG icons from Lucide (https://lucide.dev) for:
- Paint roller / spray gun → Services
- Car → Vehicles
- Shield check → Quality
- Phone → Contact
- Clock → Working hours
- Map pin → Location
- Wrench → Repair
- Sparkles → Polishing

### Reference
- Dark, bold automotive feel
- Think premium auto detailing studio
- Metallic textures, clean lines, red accents on dark backgrounds

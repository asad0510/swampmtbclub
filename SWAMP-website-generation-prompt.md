# AI Website Generation Prompt — SWAMP Mountain Bike Club

> Paste the block below into any AI website builder (v0, Lovable, Framer AI, Webflow AI, Relume, etc.). It was reverse-engineered from the club's current site and rewritten for a modern, premium result.

---

## PROMPT

**Role:** You are a senior product designer and front-end developer. Build a modern, premium, conversion-focused website for a nonprofit mountain-bike club.

**Business:** SWAMP Mountain Bike Club — Florida's premier MTB club and 501(c)(3) nonprofit based in Tampa Bay. It builds and maintains 150+ miles of sustainable trails across 6 systems, runs the annual CroomFest festival, supports NICA youth racing and adaptive "Ride Buddy" outreach, and is entirely volunteer-run. Mission: *responsible recreation and conservation, hand in hand.*

**Goal:** A best-in-class club homepage that drives memberships, donations, event registration, and volunteer sign-ups — outdoorsy but refined, not a generic template.

### Brand & Visual System
- **Palette:** deep swamp green `#0d1f14` / `#14251a` (dark sections & text), vivid trail green `#7dd13f` / `#5aa817` (accent, highlights), energetic orange `#e0651a` (primary CTAs only), warm off-white `#f5f4ee` (page background), soft sage `#eef0e6` (alternating sections). Golden `#f0b64a` and sky `#8fd0f0` as sparing difficulty/label tints.
- **Typography:** condensed athletic display face (e.g. **Anton** or **Oswald**) for oversized headlines set in near-uppercase; clean grotesque (e.g. **Archivo**) for body and UI, weights 400–800. Big, confident type — hero headline `clamp(52px, 8vw, 116px)`.
- **Style:** generous whitespace, 18–20px body, rounded corners (12–18px), soft layered shadows, subtle hover lifts (`translateY(-6px)`), full-bleed photography with dark gradient scrims for legibility. Alternate light and dark full-width sections for rhythm. Sticky translucent (blurred) nav. Avoid gradients-as-decoration, emoji-heavy UI, and clip-art.

### Layout & Sections (top → bottom)
1. **Utility bar** (dark green): location + trail-miles tag; Log In, Cart, Shop Gear.
2. **Sticky nav:** wordmark logo, links (Trails, CroomFest, Membership, Get Involved, Shop, News), outline "Donate" + solid orange "Join the Club" buttons.
3. **Hero:** full-bleed rider-on-singletrack photo, "Est. 2005 · Nonprofit" pill, huge headline **"RIDE THE SWAMP."**, supporting line, dual CTAs (Become a Member / Explore Trails), dark bottom gradient.
4. **Stat strip** (dark): 150+ miles · 6 trail systems · 500+ members · 20 yrs, in green display numerals.
5. **Mission:** two-column — copy + inline mini-stats (100% volunteer-run, NICA, Ride Buddy) beside a tall 4:5 photo.
6. **Trail network:** responsive card grid for Balm Boyette, Croom, Jay B Starkey, Flatwoods, RiverFront, plus a highlighted orange "Pinellas Bike Park — help us build it" card. Each card: photo, name, difficulty tag, mileage, one-line description.
7. **CroomFest feature:** full-bleed festival photo with dark side-gradient; "CAMP | PEDAL | PADDLE | PLAY", **CroomFest 2026**, Feb 4–9 2026, Register + "Volunteer & Ride Free" CTAs.
8. **Membership:** 4 pricing tiers (Individual $40, **Family $50 — Best Value, elevated dark card**, Flatwoods Explorer $100, Wilderness Warrior $250), benefit checklists, "per year" note, hover lift.
9. **Get Involved:** 3 cards (Trail Crew, Grant Writers, Board & Leadership) + "See all volunteer roles" CTA.
10. **Shop:** 4-product grid (Trucker Hat $20, Window Decal $5, Bottle Opener $10, Water Bottle $12) with image zoom on hover and "In Stock" badges; "Visit Full Store" link.
11. **Sponsors:** dark section, "Let's Support The Businesses That Support Our Club", auto-scrolling logo/name marquee (LMNT, Outspokin Bicycles, Tifosi, Küat, REI, Athletic Brewing, Hammer Nutrition, Stan's, NICA, Bike Florida, Sierra Nevada, Atömik Carbon…), "Become a Sponsor" CTA.
12. **Blog/News:** 3 article cards with photo, date · category, title, excerpt.
13. **Donate CTA band** (orange): bold headline "Your donation keeps the trails you love rideable" + Donate / Become a Member buttons.
14. **Footer** (dark green): wordmark + mission blurb + socials, Explore / Get Involved / Get in Touch columns, email newsletter capture, address `5128 Puritan Road, Tampa, FL 33617`, `info@swampmtbclub.com`, copyright.

### Interaction & Technical
- Sticky blurred header; smooth in-page anchor scrolling; card hover lifts and image zooms; marquee animation; scroll-reveal fade-ups.
- Fully responsive: 4-col → 2-col → 1-col grids; nav collapses to a hamburger on mobile; hero scales fluidly.
- Accessible: WCAG AA contrast (orange text only on dark/white; never orange-on-green), focus states, semantic landmarks, alt text on every image.
- Performance & SEO: lazy-loaded images, meta title/description, Open Graph tags, `LocalBusiness`/`SportsClub` + `Event` (CroomFest) schema, fast fonts.
- Deliver clean semantic HTML/CSS (or React + Tailwind) with real placeholder photo slots labeled by subject.

**Tone of copy:** warm, community-driven, a little rugged and playful ("get a little dirty", "it takes a village"), never corporate.

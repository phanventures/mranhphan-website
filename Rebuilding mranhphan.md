# Rebuilding mranhphan.com

**Status:** In progress — homepage HTML built, pending deployment
**Last updated:** 2026-04-22

---

## Goal

Rebuild mranhphan.com as the personal brand hub for The Phan Club — a community for queer entrepreneurs. Replace the outdated portfolio site (circa 2014–2019) with a focused, conversion-driven homepage that drives two actions: joining The Phan Club (founding members) and subscribing on YouTube.

---

## Brand

| Element | Value |
|---|---|
| Background | `#111111` (near black) |
| Primary text | White / off-white |
| Accent | `#FF6B00` (orange) — consistent with Phan Ventures brand language |
| Typography | Inter (Google Fonts) — 900 weight headlines, 400/500/700 for body and UI |
| Wordmark | "ANH" white bold + "PHAN" in orange — CSS text, no image dependency |

Design follows the same aesthetic as Productive Workflows — dark, minimal, text-forward. Single self-contained HTML file.

---

## Positioning

**mranhphan.com = The Phan Club's front door.**

Anh Phan's personal brand is the differentiator. This isn't a faceless brand — it's built by someone who actually runs businesses and communities. The site leads with that operator credibility, then converts to The Phan Club.

**Tagline:** You don't have to build community alone.
**Target:** Queer entrepreneurs (gay men to start, broader queer audience as model scales)

---

## Page Structure

### Nav
- Left: ANH PHAN wordmark
- Right: Instagram | YouTube | Join The Phan Club (CTA button)
- Sticky, dark, minimal

### Section 1 — Hero
- Eyebrow: `QUEER ENTREPRENEUR · COMMUNITY BUILDER · REAL OPERATOR`
- Headline: `Building businesses and communities for people who refuse to fit in.`
- Subhead: Real operator credibility, no theory
- CTAs: Join The Phan Club (primary filled) + Watch on YouTube (outlined)

### Section 2 — Three Pillars
- Numbered cards (01, 02, 03)
- Community Building / Business & Operations / Queer Entrepreneurship

### Section 3 — The Phan Club
- 2-col: left is the pitch, right is 4 stat cards
- Stats: 3 businesses, 8+ years, 200+ players, 100% queer-owned
- CTA: Join as a Founding Member

### Section 4 — About Anh
- 2-col: photo left (placeholder), bio right
- Headline: `Real operator. Not a guru.`
- Credential list: MN Dodgeball, Always Funday, Phan Ventures

### Section 5 — Content / YouTube
- 3 placeholder video cards
- CTA: Subscribe on YouTube

### Section 6 — Join CTA
- Full-width, centered
- `You belong here. Join The Phan Club.`
- CTA: Join as a Founding Member

### Footer
- Wordmark + links + copyright

---

## Deliverable

- **File:** `homepage.html` (self-contained, no framework, no build step)
- **Responsive:** Mobile-friendly — single column on small screens, nav collapses
- **Location:** This folder

---

## Open Items

- [ ] Add Instagram URL to nav and footer
- [ ] Add YouTube channel URL (handle: @Mr_AnhPhan)
- [ ] Add Skool/community join URL for "Join as a Founding Member" CTA
- [ ] Swap in Anh's headshot for the About section placeholder
- [ ] Add real YouTube video thumbnails and titles once channel is live
- [ ] Deploy to mranhphan.com (determine hosting — static host like Netlify/Vercel, or CMS)
- [ ] Decide on founding member waitlist mechanism (Skool, email form, etc.)

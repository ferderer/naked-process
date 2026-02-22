# naked-process.org — Website Outline

## Domain
`naked-process.org` — registered / available

## Technology
Static site generator (Hugo, Astro, or similar). No backend needed. Content lives in the repo.

---

## Site Structure

### Landing Page (`/`)

**Hero section:**
- Headline: **Naked Process**
- Subline: *Process is perfect when nothing can be taken away.*
- One-paragraph elevator pitch: "Most frameworks tell you what to add. Naked Process tells you what to remove. A decision tree that strips software development process down to what your team actually needs — backed by five decades of research."
- Two CTAs: "Read the Manifesto" | "Try the Decision Tree"

**The problem (3–4 sentences):**
The software industry optimizes the least important variable. Developer quality predicts project success. Process does not. The evidence has been clear since 1968.

**The approach (3–4 sentences):**
Take every process element from Scrum, Kanban, XP, and classical PM. Subject each to: "Under which conditions does this actually help?" What survives becomes your process. Everything else is removed.

**Core principles (visual grid, 5 items):**
1. Subtractive, not additive
2. Context-dependent
3. People over ceremony
4. Decision speed over ritual
5. Transparent accountability

**Social proof / credibility:**
Research foundation — logos or citations of key sources (Sackman 1968, Peopleware 1987, Standish Group, etc.)

---

### The Decision Tree (`/tree`)

**Interactive decision tree tool.**

User answers questions about their six dimensions → gets a tailored minimal process recommendation.

- Step-by-step guided flow or single-page form
- Output: specific practices recommended, with rationale for each
- Output also shows: what was *removed* and why (the subtractive philosophy made visible)
- Shareable result URL (e.g., `/tree/result?tc=strong&dc=cd&sa=direct&da=team&pc=specified&cn=low`)
- "Your process has 3 practices. A full Scrum implementation has 27. Here's why you don't need the other 24."

---

### The Manifesto (`/manifesto`)

Full text of `docs/manifesto.md`. Clean typography, no distractions.

---

### The Research (`/research`)

The "Points Don't Matter" article as a long-form page.

Sections as defined in the outline:
- The 10x Research
- Price's Law
- Peopleware
- Hive Mind
- Scrum's Own Data
- The Standish Numbers
- The Camouflage Problem
- The Irony

Each section with expandable references / footnotes. Academic rigor, blog readability.

---

### Methodology (`/methodology`)

How the decision tree was built. The four-step process:
1. Identify dimensions
2. Decompose existing processes
3. Map practices to conditions
4. Build the tree

Transparent about what's validated and what's still in progress.

---

### About (`/about`)

Origin story. 30 years of software delivery → pattern recognition → this framework.
Link to GitHub repo for contributions.
No certification program. Nothing to sell.

---

### Blog (`/blog`)

For ongoing articles, case studies, and community contributions.

Seed posts:
- "Points Don't Matter" (the manifesto article)
- "What Scrum Gets Right — And Where It Stops"
- "The Async Daily: What Minimal Communication Actually Looks Like"
- "Case Study: [anonymized project] — What Happened When We Stripped Process"

---

## Design Direction

- **Aesthetic:** Stark. Minimal. Almost brutalist. The design should embody the philosophy — nothing decorative, everything functional.
- **Typography:** One serif font for headings (authority), one mono or clean sans for body (developer-native).
- **Color:** Black, white, one accent color. That's it.
- **No stock photos.** Diagrams, data visualizations, whitespace.
- **Mobile-first.** Developers read on phones.

## Key Differentiator from Other Methodology Sites

Every other methodology site says "here's what to do." Naked Process says "here's what to stop doing." The decision tree is interactive and personal — it gives you *your* answer, not a universal prescription. The entire site should feel like the opposite of a SAFe sales deck.

---

## Implementation Priority

1. **Landing page + manifesto** — can launch with just these
2. **Research article** — drives SEO and sharing
3. **Decision tree (static version)** — even a non-interactive flowchart is valuable
4. **Decision tree (interactive)** — the killer feature, but needs the tree logic to be complete first
5. **Blog** — ongoing content engine

## Technical Notes

- Static site, deployed via GitHub Pages or Netlify/Vercel
- Content in Markdown, rendered by SSG
- Decision tree interactive component: React/Svelte widget embedded in static page
- Analytics: Plausible or Umami (privacy-respecting, no Google Analytics — consistent with the philosophy)

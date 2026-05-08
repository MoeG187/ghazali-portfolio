# Reference Portfolio & Agency Sites for "Funky Scroll, Bold Motion" Inspiration

**TL;DR**
- For a senior UX/product designer briefing the *feel* of a portfolio with funky scroll, bold typography and dark theming, the strongest current references are **Lusion**, **Active Theory**, **basement.studio**, **Cyd Stumpel**, **Robin Mastromarino**, **Henri Heymans**, **Jesper Landberg**, and **Resn** — all Awwwards Site/Studio/Developer-of-the-Year–caliber work that leans dark, typographic, or aggressively interactive.
- Most of these sites are built on the same modern stack (GSAP, Lenis/Locomotive Scroll, Three.js/WebGL, Next.js), so referencing them in a brief is also implicitly pointing your developer to a known, achievable technical pattern rather than an impossible one-off.
- Pick references by *intent*: **Lusion / Active Theory / Resn** for "blow-the-doors-off WebGL," **basement.studio / Obys / Henri Heymans** for "loud typographic brutalism," **Cyd Stumpel / Robin Mastromarino / Jesper Landberg** for "smooth scroll-driven motion that still feels like a portfolio, not a tech demo."

---

## Key Findings

The list below is curated from Awwwards Site of the Day / Site of the Year / Developer Award winners and nominees, plus FWA/CSSDA-recognized work, weighted toward dark themes and bold typography as requested. Each entry has the URL, a one-sentence "what makes it stand out," and the dominant scroll/animation technique.

### 1. Lusion — `lusion.co`
- **Why it stands out:** Lusion's portfolio is the gold standard of clean dark-mode minimalism wrapped around extremely high-fidelity real-time 3D — every scroll triggers a cinematic, GPU-accelerated scene that frames their work without shouting over it. Their site won FWA, Awwwards and CSSDA Site of the Year and they're a multi-year Awwwards Developer Site of the Year holder.
- **Technique:** Scroll-triggered WebGL scenes (Three.js + custom shaders), real-time reflections/volumetric lighting, and scroll-synced 3D camera moves; mouse-reactive interactive 3D type.
- **Read it as:** "We want the polish of Lusion, but scaled down to a personal portfolio."

### 2. Active Theory — `activetheory.net`
- **Why it stands out:** Each iteration (v4–v6) reinvents the agency portfolio as a fully navigable real-time environment — neo-Tokyo alleys, Venice-Beach-to-Amsterdam canals, AI chat and multiplayer in v6 — all rendered in WebGL with confident dark color palettes and large typographic overlays. Multiple Awwwards Sites of the Day and Site of the Month (Feb 2024).
- **Technique:** Endless/looping scroll through real-time 3D worlds (WebGL/GLSL), scroll-driven camera traversal, and unconventional menu/navigation that replaces conventional pages with spatial wayfinding.
- **Read it as:** "I want my work to live inside a world, not in a grid."

### 3. basement.studio — `basement.studio`
- **Why it stands out:** Aggressively dark + brutalist typographic identity built around their own bespoke Basement Grotesque typeface; the studio site, KidSuper World and Basement Chronicles all push oversized type, GSAP-driven loaders and snappy section transitions. Awwwards SOTD multiple times (most recently April 2025) with developer awards.
- **Technique:** GSAP timelines + Locomotive Scroll/Lenis for inertia smooth-scroll, scroll-triggered typographic reveals, marquee/ticker text, and Three.js 3D accents — all on Next.js.
- **Read it as:** "Dark, opinionated, type-as-hero — performance-first, not gratuitous 3D."

### 4. Cyd Stumpel — `cydstumpel.nl`
- **Why it stands out:** Independent creative-developer portfolio that's repeatedly won Awwwards SOTD (2022 and 2025 versions) and is consistently held up as a benchmark of *purposeful* motion — page transitions and scroll behavior feel like turning pages in a designed object, not show-off animation. The 2022 version uses a confident black-and-cream palette; the 2025 uses View Transitions + lavender/cream.
- **Technique:** GSAP + GLSL shaders, Locomotive Scroll for smooth inertia scrolling, Three.js for canvas elements, plus the new CSS View Transitions API for page-to-page morphs.
- **Read it as:** "What a senior IC's portfolio should feel like: motion that supports content, not replaces it."

### 5. Robin Mastromarino — `robin-mastromarino.com` (also archived on Awwwards SOTD)
- **Why it stands out:** A designer's portfolio (built with developer Patrick Heng) that's become a reference for *velocity-aware* scroll — image edges deform, displace and round based on how fast the user scrolls or drags, giving the homepage slider a tactile, almost rubbery feel. Pure black/white palette, large type, fully WebGL-rendered. Awwwards SOTD + SOTM winner.
- **Technique:** WebGL/Three.js with displacement and rounded-edge shaders driven by scroll/drag velocity (GSAP), plus drag-as-scroll horizontal slider on the homepage.
- **Read it as:** "Funky, but with restraint — the funkiness comes from physics, not decoration."

### 6. Henri Heymans — `henriheymans.com`
- **Why it stands out:** Two consecutive Awwwards SOTDs (2021 and 2025) for a creative-front-end portfolio that pairs an unapologetically dark/high-contrast palette (the 2021 version uses near-black `#0B0B0B` against acid lime `#bfff07`) with horizontal-layout navigation and oversized typography pushed to the edge of the viewport.
- **Technique:** Horizontal scroll layout, WebGL/GLSL cursor-interactive accents, scroll-triggered marquee text, vanilla-JS smooth scrolling.
- **Read it as:** "Bold, loud type and unconventional axis of motion — but still readable."

### 7. Jesper Landberg — `jesperlandberg.com` / `jesperlandberg.dev`
- **Why it stands out:** Two-time Awwwards Independent of the Year (2022 and 2024), with 30 Awwwards SOTDs and 30 Developer Awards listed on his own site — his portfolio templates are textbook examples of horizontal drag-scroll project navigation and "pull-up to load next project" interactions, in a stark black-and-white frame.
- **Technique:** Horizontal scroll + drag navigation, WebGL sliders, GSAP-driven page transitions including a vertical "pull next project into view" gesture; built with WebGL + GSAP.
- **Read it as:** "If your portfolio is mostly case studies, this is the pattern to copy for navigation."

### 8. Resn — `resn.co.nz`
- **Why it stands out:** Twice-named Awwwards Agency of the Year and an FWA Hall of Fame inductee, Resn's site centers around a clickable, draggable revolving black crystal that explodes into interactive WebGL experiments — pure dark theme, sparse type, maximum strangeness. It won the inaugural FWA of the Day, Awwwards SOTD and CSSDA Website of the Day at launch.
- **Technique:** Centerpiece interactive 3D object with mouse/drag manipulation (WebGL), gestural exploration over conventional scrolling, and Easter-egg micro-interactions (e.g. resizing the browser triggers hidden states).
- **Read it as:** "Anti-portfolio: the homepage *is* the interaction." Useful as a stretch reference, not a literal blueprint.

### Honorable mentions worth showing in the brief
- **Obys Agency** (`obys.agency`) — Awwwards Studio of the Year, type-driven dark/cream sites; their **Typography Principles** microsite (Awwwards SOTD) is a horizontal scroll + scroll-triggered storytelling reference for editorial-feeling motion.
- **Immersive Garden** (`immersive-g.com`) — Awwwards 2024 Agency of the Year; bas-relief 3D, scroll-driven case studies, dark monochrome palette (`#000000` / `#c2c2c2`).
- **Locomotive** (`locomotive.ca`) — Awwwards 2024 Studio of the Year; the agency that *built* Locomotive Scroll/Lenis, so their site is the canonical "smooth scroll + parallax" demo, set against editorial typography (Editorial New + Helvetica Now).
- **Igloo Inc** (`iglooinc.io`) — Awwwards Site of the Year 2024 by abeto; not a portfolio, but the current benchmark for "immersive 3D experience that's still easy to navigate via scroll."

---

## Details: How to use these as references

**Pattern map (what each technique looks like in practice):**

| Want to evoke… | Best reference | Specific pattern |
| --- | --- | --- |
| Dark, type-led, brutalist energy | basement.studio, Obys, Henri Heymans | Oversized custom grotesque type, scroll-triggered marquees, GSAP timelines |
| Smooth, cinematic scroll without 3D overload | Cyd Stumpel, Locomotive | Lenis/Locomotive smooth-scroll + GSAP ScrollTrigger reveals + page-to-page View Transitions |
| Tactile, velocity-reactive interactions | Robin Mastromarino | WebGL displacement shaders driven by `scroll-velocity` / drag delta |
| Horizontal-axis case-study navigation | Jesper Landberg, Patrick Heng, Henri Heymans (2021) | Horizontal scroll layout + drag, "pull up for next project" gesture |
| 3D worlds you traverse by scrolling | Active Theory, Lusion, Igloo Inc | Three.js scenes with the camera bound to scroll position |
| "Anti-site" weirdness | Resn | Single hero interactive object replacing scroll |

**Common stack across these references** (useful to flag to your dev partner so the brief feels feasible): Next.js or Nuxt, **GSAP + ScrollTrigger** for animation, **Lenis** (or Locomotive Scroll, which now wraps Lenis) for smooth scroll, **Three.js / OGL / React Three Fiber + GLSL** for WebGL, and **CSS View Transitions** for page transitions on newer builds.

**On dark theming specifically:** Lusion, Active Theory v4–v6, Resn, basement.studio, Henri Heymans 2021, and Robin Mastromarino are essentially pure black (`#000` / `#0D0D0D` / `#0B0B0B`) with a single high-saturation accent (orange `#ff4d00` for basement.studio, lime `#bfff07` for Heymans, cyan/pink for Active Theory v4). That `near-black + 1 punchy accent + 1 grotesque display face` formula is the throughline.

---

## Recommendations

**If you can only show 3 references in the brief**, choose:
1. **Cyd Stumpel** — the realistic target ("an individual senior designer's portfolio that won SOTD")
2. **basement.studio** — the *vibe* target (dark, typographic, performant, opinionated)
3. **Robin Mastromarino** — the *interaction* target (one signature scroll/drag interaction, not ten)

**If you want to push harder**, add **Lusion** as the stretch goal and **Jesper Landberg** as the "structural navigation" reference for case-study pages.

**Avoid as primary references:**
- **Resn** and **Igloo Inc** are spectacular but are not portfolio sites — citing them risks scope creep into a 6-month WebGL build. Use them only as "this is the *energy* I want, scaled way down."
- **Active Theory v4–v6** is similarly aspirational; it's an in-house team of 20+ specialists. Reference for mood, not for build estimate.

**Benchmarks that would change this recommendation:**
- If your build budget is < 2 weeks of dev → drop WebGL references entirely; keep Cyd Stumpel, Jesper Landberg, Henri Heymans as templates.
- If you want recruiter-friendly clarity over wow → drop Resn/Active Theory; lean on Cyd Stumpel + Locomotive's editorial feel.
- If you want to *win an Awwwards* yourself → study basement.studio's case study on Codrops and Lusion's "Where Digital Craft Meets Ambitious Experimentation" piece, both of which document the exact stack and tradeoffs.

---

## Caveats

- Sites in this category change frequently — Cyd Stumpel, Active Theory, Lusion and Resn all version their portfolios (v2/v3/v4…), so the live URL today may differ from the Awwwards-archived version. The Awwwards "Sites of the Day" pages preserve the awarded version with thumbnails and tech stack.
- "Funky scroll" and accessibility are genuinely in tension. Locomotive themselves note in their own essays that scroll-hijacking can break native browser search (Cmd+F position), affect screen-reader behavior, and conflict with third-party plugins, and recommend reserving it for "experiential" sites — exactly the portfolio-as-showcase use case here. Plan to honor `prefers-reduced-motion` and provide keyboard navigation, especially since Cyd Stumpel — one of the strongest references on this list — is also a vocal Awwwards-jury advocate for accessible creative development.
- Several of the most-cited sites (Lusion v3, Active Theory v6) require a high-end GPU to feel as smooth as the demo videos suggest; on mid-range laptops they degrade. If your audience is recruiters opening 30 portfolios on a work laptop, optimize aggressively or your "funky scroll" reads as "broken site."
- A few inspiration aggregator pages cited in the research (Wix Studio, Eleken, Really Good Designs) describe sites using marketing/promotional language; their characterizations of "interaction" can be more flattering than the live experience. The Awwwards Sites of the Day entries — which include jury and community scores out of 10 — are more reliable for evaluating the actual quality of motion design.
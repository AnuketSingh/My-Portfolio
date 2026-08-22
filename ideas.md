# Anuket Singh Portfolio — Design Direction

## Three Possible Directions

### Theme Name: Dark Editorial Data Lab
Very Brief Intro: A tactile, high-contrast portfolio that treats analytics, code, and problem solving as a visual research practice. Graphite surfaces, bone-white type, and controlled cyan/coral accents create a confident technical identity without defaulting to cyberpunk.
Probability: 0.07

### Theme Name: Quiet Systems Journal
Very Brief Intro: A warm, paper-led portfolio inspired by print journals and research notebooks, using cream, ink, and muted blue to make projects feel considered and human. The tone is calm, precise, and reflective.
Probability: 0.04

### Theme Name: Signal / Interface
Very Brief Intro: A crisp light-mode portfolio built around modular panels, sharp typographic contrast, and visual signals borrowed from dashboards and browser interfaces. It would feel direct, fast, and product-minded.
Probability: 0.08

## Selected Direction: Dark Editorial Data Lab

### Design Movement
Contemporary editorial technology design with influences from Swiss information design, independent research publications, and modern data-lab interfaces.

### Core Principles
1. **Evidence over decoration:** every visual flourish should reinforce analysis, craft, or a clear narrative.
2. **Asymmetry with control:** use offset columns, oversized numerals, and anchored side notes instead of repetitive centered sections.
3. **Tactile precision:** pair graphite surfaces with subtle grain, hairline rules, paper-like panels, and restrained shadows.
4. **Quiet confidence:** keep the accent colors rare and intentional so the content—not a gradient—creates the energy.

### Color Philosophy
The foundation is near-black graphite, chosen to make dense technical work feel focused and to provide an exhibition-like backdrop for projects. Bone white softens the contrast so long reading remains comfortable. Electric cyan signals clarity, systems, and data movement; coral signals human judgment and creative intervention. Amber appears sparingly for status and emphasis, creating warmth without turning the interface playful.

### Layout Paradigm
A single scrolling narrative with a persistent narrow side rail on desktop and a compact top bar on mobile. Sections use editorial offsets: the hero holds a large left-aligned statement against a right-weighted visual; skill groups sit in a staggered two-column field; projects alternate media and copy; the about section reads like an annotated profile rather than a centered biography card.

### Signature Elements
- A thin cyan “signal line” that connects section labels and becomes a progress indicator as the user scrolls.
- Oversized coral section numerals, treated like catalog coordinates: 01, 02, 03, 04.
- Small monospace metadata labels and pill-shaped technology tags with squared-off corners, echoing lab notes and chart annotations.

### Interaction Philosophy
Interactions should feel like inspection rather than gamification. Hover states reveal metadata, links slide by a few pixels, project cards expose their GitHub action, and the navigation highlights the current section. Buttons should respond immediately with a slight press scale and a clear color shift. No interaction is ornamental if it does not help a visitor understand the work.

### Animation
Use a restrained reveal sequence on first load: label, headline, supporting copy, then action group, each staggered by 50–70ms. Project media enters with a small upward translate and opacity transition. The signal line draws in only once, while skill chips use minimal 150–180ms hover transitions. Avoid perpetual motion; reserve ambient motion for a faint grid texture and a very slow chart-line drift in the hero. Respect `prefers-reduced-motion` by disabling non-essential transforms and entrance animation.

### Typography System
Use **Space Grotesk** for display and UI headings, with strong weight contrast between 500 and 700. Use **DM Sans** for readable body copy and supporting descriptions. Use **IBM Plex Mono** for labels, stats, URLs, section coordinates, and technical metadata. Headlines are compact, left-aligned, and allowed to break into deliberate lines; body copy stays around 65–75 characters per line.

### Brand Essence
Anuket Singh is a BTech undergraduate who turns raw data, interfaces, and algorithms into clear systems people can understand and use. Personality: **curious, methodical, inventive**.

### Brand Voice
Headlines should be direct, specific, and slightly editorial. CTAs should describe the next action rather than make generic promises. Microcopy should sound observant and quietly ambitious.

Example headline: “I build clarity from messy systems.”

Example CTA: “Inspect the project trail”

### Wordmark & Logo
Use the generated angular chart-path mark as the visual symbol: a rising bar silhouette crossed by a single path that suggests both an algorithm and a data stream. Pair it with a custom-spaced uppercase wordmark, `ANUKET SINGH`, using Space Grotesk with deliberate tracking rather than a default logo lockup.

### Signature Brand Color
**Signal Cyan — #68E0D3**. It is bright enough to guide attention on graphite, calm enough to feel analytical, and distinctive when paired with coral rather than the usual electric blue/purple technology palette.

### Implementation Reminder
Keep this direction visible at the top of each edited page/component/CSS file. When choosing a new layout, color, interaction, or asset, ask: “Does this reinforce or dilute the Dark Editorial Data Lab philosophy?”

# CHANGELOG

## v2 (2026-04-14) — Full rebuild from ionq-ebc-content.md

### Structure
- Replaced v1's 9-section layout with 14-section structure from content file
- Sections now follow content file order: Hero, What We Heard, Disclaimer, Concepts (floor plan + 3 zones), Video Content (4 tabs), Extra Ordinary Experiences (3 tabs), Content Architecture, Process (6-phase scroller), Technical Scope, Capabilities (6 cards), Pricing (4 expandable tiers), Team (4 cards), Portfolio (3 lightbox tiles), Footer

### New components
- **ZoneModule** — zone header + overview + tabbed ideas (Zones 1 and 2)
- **Tab system** — shared across zone modules, video content, and experiences sections; keyboard accessible (arrow keys), ARIA roles
- **ProcessScroller** — sticky 6-phase diagram with scroll-driven active phase highlighting; mobile fallback collapses to compact label
- **TierCard** — 4 expandable pricing cards (Micro/Small/Medium/Large) with included/not-included lists
- **TeamCard** — placeholder avatar + name + role + TBD bio
- **PortfolioTile** — click-to-lightbox with Escape/click-outside close
- **Tier chips** — every idea tab carries its pricing tier tag as a visible chip

### Retained from v1
- Three.js hero shader (same code, new headline/copy)
- Floor plan image (floorplan-level3.png) with inverted filter treatment
- All design tokens (--bg, --text, --accent, --copper, --muted, --ionq, --card-bg, --card-border)
- Typography: Cormorant Garamond + Inter
- Fade-in intersection observer
- Sticky nav pattern (updated section links)
- Logo assets (logos/futureman-logo.png, logos/24sa-logo.png)

### Removed from v1
- Six Pillars grid
- Persona journey tabs
- Architectural render gallery
- Design language / mood board section
- Credentials cards
- Timeline
- Three-tier investment grid (replaced by four-tier expandable cards)
- Closing section (replaced by footer)

### Interaction changes
- Floor plan hotspots now scroll to and highlight corresponding zone modules (was inline expand)
- Sticky nav updated: Hero, Concepts, Video, Experiences, Process, Capabilities, Pricing, Team, Portfolio
- All sections have stable anchor IDs with scroll-margin-top for clean nav targeting
- Process diagram nodes are clickable (scroll to phase detail)
- Pricing tiers expand inline (click header to toggle)
- Portfolio tiles open a lightbox overlay

### Content
- All copy pulled verbatim from ionq-ebc-content.md
- Team bios flagged TBD; Derek and Conrad last names marked TBD
- Portfolio content placeholder only

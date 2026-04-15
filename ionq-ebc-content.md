# IonQ EBC Proposal — Web Page Content

> **For the Claude Code build session:** This file is the authoritative content source for the v2 proposal website. It is organized as a sequence of top-level `## Section` blocks. Each section has a `meta` block describing the **intended UI pattern** (hero, tabbed module, scroll-driven stepper, expandable cards, etc.). Keep the visual style from v1. Replace the page structure. Preserve the clickable floor-plan concept in the Concepts section.
>
> **Structural primitives used below (build these once, reuse):**
> - `HeroBlock` — headline + supporting paragraphs
> - `FloorPlanMap` — SVG/image of the IonQ space with clickable zone hotspots. Clicking a zone scrolls to / highlights the corresponding `ZoneModule`.
> - `ZoneModule` — a zone header + overview paragraph, containing a set of **tabs** (one tab per idea). Each tab shows the idea title, tier tag, and body copy.
> - `ProcessScroller` — sticky 6-phase diagram at top of viewport; each phase's details reveal below in sequence as the user scrolls.
> - `TierCard` — compact card (tier name, price, one-line pitch). Click expands full detail (included / not included / rationale).
> - `TeamCard` — portrait + name + role + short bio.
> - `PortfolioTile` — lightbox tile with media carousel + short story.

---

## 1. Hero / Executive Summary

**meta:** `HeroBlock` — full-viewport hero. Headline large and confident. Three short paragraphs below. No bullets. Scroll cue at bottom.

**headline:** Make visitors feel the shift.

**subhead:** A content and interactive system for IonQ's Washington DC Executive Business Center.

**paragraph 1 — the scenario:**
IonQ's DC EBC will host Members of Congress, enterprise buyers, and quantum PhDs in the same room. The content has to land for all of them.

**paragraph 2 — who Futureman is:**
Futureman is a creative and production studio built for spaces like this — CGI, 3D, motion, interactive systems, and AV integration under one roof. Partnered with SketchDeck (via 24 Seven Agencies) for this engagement.

**paragraph 3 — what we're proposing:**
Four tiers, $250k to $1.5m. Evergreen spine, swappable skin. Built to last, built to update.

---

## 2. What We Heard

**meta:** Short three-column or three-row block. Simple. Three framing statements, each with a short caption. No interactivity.

- **What this project is:** on-screen and interactive content for the DC EBC.
- **What it isn't:** interior design, architecture, or AV hardware procurement.
- **What success looks like for IonQ:** every visitor — Congress to PhD — leaves understanding what IonQ does, why it matters, and why IonQ specifically.

---

## 3. General Disclaimer (Our Approach to Discovery)

**meta:** Single text block. Bordered callout or muted background treatment. Reads as a framing note before the Concepts section.

**body:**
The concepts, frameworks, and approaches that follow are directional. They exist to demonstrate how we think about IonQ's story — not to replace the discovery work required to tell it accurately.

Every engagement we take on at this scale begins with a structured Content Strategy and Discovery phase: deep dives with technical SMEs and Marketing leads, a full audit of existing materials, and a narrative framework session that aligns on audience registers, use case hierarchy, and content architecture before a single frame gets designed. What we develop in that phase becomes the foundation everything else is built on.

The ideas you see here are proof we know how to think about the problem. Discovery is how we make sure we're solving the right one.

---

## 4. Concept Ideas

**meta:** This is the most visually distinctive section of the page. It opens with framing copy, then presents the `FloorPlanMap` (the existing v1 floor plan image, with clickable hotspots for each zone). Clicking a zone on the map scrolls/snaps to the corresponding `ZoneModule` below. Each `ZoneModule` presents zone-specific ideas as **tabs** inside the module so the user can flip between ideas without leaving the zone.

### 4.0 Framing copy (above the floor plan)

IonQ is selling a fundamental shift in what's computationally possible. The EBC should make visitors *feel* that shift — not just understand it.

What follows are directional concepts organized by zone. Each is tagged to indicate which pricing tier it falls within. Concepts without a tier tag are foundational to the experience at every level.

### 4.1 FloorPlanMap

**meta:** Re-use the v1 floor plan image. Overlay three clickable hotspots mapped to the three zones below.

- **Hotspot 1 →** Zone 1: Lobby LED Wall
- **Hotspot 2 →** Zone 2: Dome Experience
- **Hotspot 3 →** Zone 3: Experience Center

### 4.2 ZoneModule — Zone 1: Lobby LED Wall

**zone overview:**
The lobby is the first moment. It needs to do something before anyone opens their mouth. Our instinct is to make it immediately personal — and to turn the act of walking in the door into a demonstration of quantum thinking.

**tabs (2):**

**Tab 1 — Quantum Shadow Wall** · *tier: Small / All Tiers*
Cameras track visitors as they enter. Their silhouettes are captured, processed through a visual representation of a quantum algorithm, and transformed in real time on the LED wall — their likeness becomes data, gets superposed, and collapses into something new. It's immediate, personal, and a conversation starter before anyone says a word. No explanation needed.

At the Small tier, this is achievable through real-time camera processing using TensorFlow or similar video processing libraries — visitor presence directly influences the content playing on the LED without the complexity of full sensor integration.

**Tab 2 — Live Quantum Pulse Feed** · *tier: Small / All Tiers*
A persistent ambient visualization drawn from IonQ's actual processing activity — anonymized job queues, gate fidelity, error correction events. Not a dashboard. Something closer to a heartbeat. The machine is always running. Visitors walk in and the first thing they see is proof.

### 4.3 ZoneModule — Zone 2: Dome Experience

**zone overview:**
The dome is the moment the EBC earns its existence. It should be the thing visitors describe when they leave. Our concepts here start from IonQ's actual technology — the trapped ion — because it's genuinely extraordinary and most visitors have never encountered it.

**tabs (2):**

**Tab 1 — The Ion Trap** · *tier: Medium / Large*
IonQ traps individual ytterbium ions using laser fields. The dome becomes a scaled-up, immersive recreation of that process: individual ions rendered as floating light points, held in place by visualized electromagnetic geometry. Spatial audio hums with the resonant frequencies of the trap. Visitors are standing inside the machine.

A touch or motion event triggers a measurement — the superposition collapses, the system reconfigures, the ions settle. The core concept of quantum measurement, taught without a single word of explanation.

At the Medium tier, visitor presence and movement trigger state changes in the dome environment through sensor detection — transforming the space from ambient display to reactive experience. At the Large tier, this expands into Minority Report-style gesture interactions: visitors controlling content with their hands, multiple visitors influencing different sections of the visualization simultaneously. Think Flight of Passage at Animal Kingdom — the environment responds to you.

**Tab 2 — Entanglement Across Distance** · *tier: Medium / Large*
Split the dome into two zones. Two visitors interact with opposite particles — one touches a point of light, the other sees it respond instantly, regardless of where they're standing in the space. Simple to experience. Philosophically disorienting in the best way. You can narrate quantum entanglement all day. Feeling it is different.

### 4.4 ZoneModule — Zone 3: Experience Center

**zone overview:**
The Experience Center is where the EBC earns credibility. The lobby creates wonder; the dome creates feeling; this space creates understanding. Our recommendation is a combination of one powerful passive video and one or two interactive installations that reward curiosity without requiring a guide. Details in the two sections that follow.

**meta:** Zone 3 module is intentionally brief — no tabs. Its purpose is to orient the visitor on the floor plan and hand off to the two standalone sections below (Video Content and Extra Ordinary Experiences). The floor plan hotspot for this zone scrolls here; the user then continues to sections 5 and 6.

---

## 5. Video Content

**meta:** Standalone section. Not a zone. `ZoneModule`-style tab pattern (4 tabs, one per concept) but without the zone-header framing. Treat this as its own top-level section.

**section intro:**
This is the piece that plays on a loop and still stops people mid-stride on their fifth pass through the space. Below are four directional concepts. The right answer depends on what we learn in Discovery — specifically which register resonates most with IonQ's primary visitor profile and which narrative the brand is most ready to own.

**tier tag:** *All Tiers*

**tabs (4):**

**Tab 1 — The Universe Running Its Own Code**
The premise: quantum computing didn't come from nowhere — it came from observing how nature already computes. The video moves through natural systems that are, in a literal sense, solving optimization problems in real time. A murmuration of starlings. A slime mold finding the shortest path through a maze. Protein chains folding into their lowest-energy configuration. Ice crystals forming. Ant colonies routing. Each sequence is visually extraordinary and scientifically accurate — and each one is a quantum phenomenon. The back half of the video introduces IonQ's ion trap: a single atom, suspended. The implicit argument: *we didn't invent this. We learned to harness it.* No voiceover needed. The edit does the work.

**Tab 2 — One Problem. Two Clocks.**
Split-screen, but not gimmicky — more like a diptych. On one side, a classical computer working through a combinatorial problem in real time: numbers cascading, the branching decision tree expanding, the clock running. On the other side: the same problem, quantum. The visual language of the two sides is deliberately different. The classical side is mechanical, grid-based, almost anxious. The quantum side is fluid, probabilistic, almost biological. They both start at the same moment. The quantum side resolves. The classical side is still running when the screen fades. No text needed except, at the end: the problem. And how long each would take. The problems rotate as IonQ's use case library evolves — drug discovery one quarter, logistics optimization the next. Evergreen format, updateable content.

**Tab 3 — Inside the Trap**
This one is almost purely aesthetic but grounded in IonQ's actual technology. IonQ traps individual ytterbium ions using laser fields — it's one of the most visually singular things in all of computing if you render it properly. The video is a slow, cinematic journey into the ion trap itself. Starting from the outside — the lab, the hardware, the cooling systems — then moving inward, scale shifting, until you're floating alongside individual atoms suspended in light. The atoms are real. The scale is real. The physics is accurate. What's invented is the cinematography and the sound design. It ends on a single ion, perfectly still, holding a qubit in superposition. Tagline: *This is where the future is held.*

**Tab 4 — The Weight of Unsolved Problems**
The most emotionally ambitious option. Opens on a patient waiting for a drug that doesn't exist yet. A logistics network failing during a humanitarian crisis. A financial model that can't process the variables fast enough to prevent collapse. These aren't dramatized — they're rendered almost journalistically, quietly. Each unsolved problem is then translated into its computational form: the scale of what classical computing can't resolve. Then IonQ. Not as a savior — as a tool. A powerful, precise, available tool. The video ends not with a solution but with the suggestion of one: the ion trap, running. *The work is already happening.*

---

## 6. Extra Ordinary Experiences

**meta:** Standalone section. Not a zone. Tab pattern (3 tabs, one per installation concept). Top-level section, visually distinct from the zone modules above.

**section intro:**
Three installation concepts that extend the interactive layer beyond any single zone. Large-tier additions — these ride on top of the foundational content and sensor systems already in scope at lower tiers.

**tier tag:** *Large / Upgrade*

**tabs (3):**

**Tab 1 — The Decoherence Room**
An installation where visitors become the noise. Microphones, motion sensors, and thermal cameras feed into a live quantum circuit visualization on screen. When visitors are still and quiet, the circuit runs cleanly. When they move and speak, errors cascade — the system degrades in real time. IonQ's differentiation is that they've solved decoherence better than anyone. This installation makes visitors feel the problem before they hear the solution.

**Tab 2 — Use Case Portals**
The visitor isn't selecting an industry from a menu — they're stepping into one. Floor projection, surround screens, and spatial audio collapse the space around a single real-world problem: a supply chain that can't resolve, a molecule that won't fold, a financial model running out of time. The problem builds visually until it hits its classical ceiling. Then quantum runs. The resolution is the pitch.

Each portal is a self-contained environment, swappable by IonQ without a rebuild, triggerable by a presenter mid-tour or surfaced automatically in a self-guided flow. At the Large tier, tabletop projections and gesture-based interactions extend this into the broader Experience Center floor, giving visitors direct physical engagement with the content. The specific use cases (which industries, which problems, which moments of classical failure) are exactly what we'd excavate in Discovery. IonQ's SMEs and solutions team will know which scenarios land hardest with the visitor profiles walking through that door. We build the vessel. Discovery tells us what to put in it.

**Tab 3 — The Complexity Wall**
A large-format tactile display built around a real optimization problem — nodes and edges representing drug interaction modeling, supply chain routing, or whichever use case is most resonant for IonQ's audience. Visitors drag and attempt to solve it classically, watching the compute time explode exponentially. Then IonQ runs it.

---

## 7. Content Architecture Approach

**meta:** Single text block. Distinct visual treatment — a callout or "principle" card. This is a POV statement, not a list.

**headline:** Evergreen spine. Swappable skin.

**body:**
Regardless of tier, the content system is built on one structural principle.

The **spine** — the physics, the core value proposition, the technology differentiation — doesn't change. The **skin** — use cases, customer stories, partner logos, government milestones — does. IonQ's business is moving fast; the content architecture needs to move with it. The spine is built once and built to last. The skin is designed for low-lift refresh. This also answers IonQ's scalability question: other EBCs pull the spine and localize the skin without requiring a full rebuild.

---

## 8. Process

**meta:** `ProcessScroller`. The six-phase diagram from v1 sticks to the top of the viewport. As the user scrolls, each phase's details reveal in sequence below. The active phase gets highlighted in the sticky diagram. This section is long — each phase has multiple sub-beats.

**intro paragraph (above the sticky diagram):**
Every engagement begins with Discovery and ends with a commissioned, signed-off experience. Below is the six-phase process Futureman uses for a project of this scope. Each phase has defined deliverables and a formal sign-off gate — not because we like paperwork, but because clear gates protect IonQ's investment and keep scope from drifting.

**sticky diagram nodes:**
1. Discovery — *SME interviews*
2. Content & Design — *Scripts + boards*
3. Production — *3D, CGI, motion*
4. QA & Review — *Client review rounds*
5. Installation — *AV + on-site*
6. Commissioning — *Live test + sign-off*

### Phase 1 — Discovery
Before we write a word or render a frame, we spend dedicated time with IonQ's scientists, marketers, and space. The most compelling content IonQ can show the world is the story only IonQ can tell. Discovery is how we find it.

- **Technical SME interviews.** IonQ specifically said they want the agency to "mine the valuable content in collaboration with technical SMEs and Marketing." That's a green light to treat Discovery as a structured excavation. Futureman would run focused sessions with 3–5 SMEs — quantum scientists, product leads, solutions engineers — not to get a lecture on quantum computing, but to extract the *stories*: the problems customers actually bring to IonQ, the moments where classical computing fails and quantum succeeds, the use cases already working versus the ones that are a year out. The goal is finding the content that's genuinely IonQ's and no one else's.
- **Audience mapping.** IonQ's visitor mix is unusually wide — Members of Congress to quantum PhDs. Discovery includes building a concrete audience profile matrix: who comes in, what they already know, what they need to leave believing, and what a successful visit looks like for each type. This is what makes the three-register content architecture possible — you can't design for multiple audiences without first defining them precisely.
- **Narrative framework session.** A working session with IonQ's Marketing team to align on the core story spine: what's the single thing every visitor should feel when they leave? What's the hierarchy of messages — what's the lead, what's the supporting proof, what's the credibility layer? This is where the content architecture gets decided, not assumed.
- **Content audit.** IonQ said they have existing technical materials and sales resources. Discovery includes a structured review of all of it — not to reuse it, but to understand what's been said, what register it's been said in, and where the gaps are.
- **Site + AV alignment.** Given that Futureman will be coordinating with Seneca Group, Perkins Will, and facilities vendors, Discovery includes an early alignment session to understand screen specs, spatial flow, and any technical constraints that affect content design. You don't want to design a dome experience and find out the ceiling height changed.

### Phase 2 — Content & Design
Discovery outputs become creative direction. Narrative becomes script. Audience matrix becomes content hierarchy. Site alignment becomes a spatial content map.

- **Scriptwriting and narrative development.** Every piece of content — whether video, ambient loop, interactive sequence, or use case module — starts with a script or written brief. Scripts go through IonQ Marketing and at least one technical SME before anything gets visualized.
- **Storyboarding and visual language definition.** Before any 3D gets rendered or motion gets designed, Futureman develops a visual language document: the aesthetic system that governs how IonQ's quantum story looks and moves. Color, typography, spatial metaphors, the visual treatment of data and abstraction. For a brand operating at the intersection of hard science and national-scale ambition, the design is all about credibility. A visual language that feels too commercial undermines the technology. Too academic and it loses the room.
- **Content architecture mapping.** A master document that maps every piece of content to every surface in the EBC. Which screen plays what, in what mode (ambient vs. presenter-led vs. self-guided), and how content modules connect to each other. At the Large tier this includes the visitor personalization logic — which content tracks surface for which audience profiles and how IonQ Marketing queues them.
- **Client alignment checkpoint.** Design phase ends with a structured presentation to IonQ: scripts, storyboards, visual language, and content map. This is not a soft check-in — it's a formal sign-off gate. Nothing moves to production until this is approved. Changes after this point have scope implications.

### Phase 3 — Production
The longest phase. Everything approved in Phase 2 gets built.

- **3D and CGI development.** The visual heavy lifting. For IonQ this likely means: the ion trap visualization, quantum circuit animations, use case environment builds, large-format ambient loops. All custom developed — not stock, not templated. The visual language document from Phase 2 governs every render decision.
- **Motion design.** How things move matters as much as how they look. Motion design covers the kinetic logic of the content — how visuals transition, how data animates, how the experience responds to time and presence. For ambient content especially, motion has to sustain extended loops without becoming irritating or predictable.
- **Interactive development.** *(Medium and Large tiers.)* The sensor-triggered and visitor-responsive content layers get built here — the dome experience logic, the presence-detection triggers, the visitor personalization system at Large tier. This involves both software development and coordination with AV integration vendors to ensure the content system talks correctly to the hardware it will run on.
- **AI-assisted and existing footage integration.** Where b-roll and AI-generated content supplement custom CGI, it gets integrated and graded here to match the overall visual language. The goal is a seamless content system, not a patchwork.
- **Internal milestone reviews.** Production runs on a milestone cadence — typically at 30%, 60%, and 90% completion — with IonQ review built in at each gate. This prevents a full production pass going in a wrong direction before anyone catches it.

### Phase 4 — QA & Review
The phase most agencies underscope. For an EBC with multiple surfaces, interactive systems, sensor triggers, and personalization logic, QA is a critical phase in the process.

- **Internal Futureman QA.** Before anything goes to IonQ, every content piece goes through internal review: visual quality, technical accuracy, motion integrity, cross-surface consistency. For interactive content this includes functional testing of triggers, state changes, and edge cases. What happens if two visitors interact simultaneously? What happens if a presenter skips a module? What happens if the sensor loses a signal?
- **Client review rounds.** Structured rounds with IonQ Marketing and technical SMEs. Content accuracy is reviewed by people who understand the science — this is non-negotiable for a quantum computing company whose visitors include PhDs. A factually imprecise animation in an EBC is worse than no animation.
- **Cross-surface review.** Content is reviewed in context — how it looks on the actual screen formats and aspect ratios, how the ambient loops hold up at extended play, how transitions read at scale. File formats, color profiles, and playback specifications are confirmed against the AV integration requirements.
- **Revision cycles.** Built into the scope explicitly. The proposal defines how many revision rounds are included per tier — typically two structured rounds — and what constitutes a revision vs. a scope change. Clear revision language protects both Futureman and IonQ from a spiral.

### Phase 5 — Installation
The work leaves Futureman's systems and enters the physical space. Coordination-heavy and time-sensitive.

- **AV vendor coordination.** Futureman works directly with IonQ's facilities and AV integration vendors (Seneca Group and others) to hand off content in the correct formats, at the correct specs, mapped to the correct screens. This includes media server configuration guidance, playback system setup, and content management framework delivery at the Large tier.
- **On-site presence.** At least one Futureman lead is on-site during installation. Not to supervise construction — to catch content issues in the real environment that didn't surface in testing. A render that looked correct on a calibrated monitor may read differently on a large-format LED in a specific lighting condition. On-site presence is the insurance policy against that.
- **Content loading and initial configuration.** All content assets are loaded, organized, and verified on the playback system. At the Large tier, the visitor personalization framework gets configured and the content queue logic gets tested in the actual space with IonQ Marketing present.
- **Presenter training.** If IonQ staff will be running presenter-led tours, Futureman conducts a working session on how to use the content system — how to trigger modules, how to navigate between tracks, how to recover from a technical hiccup mid-tour. This is often overlooked and almost always needed.

### Phase 6 — Commissioning & Sign Off
The space is built, the content is loaded. Everything gets tested together as a complete system for the first time.

- **End-to-end live testing.** Full walkthroughs of the EBC in every tour mode: self-guided, presenter-led, and for the Large tier, the personalized visitor tracks. Every sensor trigger, every content transition, every interactive state gets tested in sequence and in isolation. Edge cases get stress-tested. The dome experience runs at length to confirm loop integrity.
- **Technical calibration.** Screen brightness, color calibration, audio levels, sensor sensitivity — all tuned to the actual space conditions. What was configured in a lab or during installation will almost always need adjustment once the space is lit, furnished, and occupied.
- **IonQ sign-off walkthrough.** A formal walkthrough with IonQ stakeholders — Marketing, facilities, and at least one executive sponsor. This is the moment the EBC is handed to its owners. Futureman walks them through every system, every content piece, every control. Questions get answered. Final adjustments get made.
- **Handoff documentation.** A complete handoff package: content asset library with naming conventions, playback system documentation, content update protocols (how IonQ refreshes a use case module without agency involvement), and technical contact list for AV vendor support. The goal is that IonQ Marketing can operate and update the EBC independently from day one.
- **Defined post-launch support window.** Commissioning doesn't mean Futureman disappears. The proposal includes a defined support window — typically 30 days — during which Futureman is available for issues that emerge once the space opens to real visitors. After that, a retainer or refresh engagement can be scoped separately.

---

## 9. Technical Scope & Vendor Coordination

**meta:** Text block, two-column treatment if desired. Three small sub-headings. No interactivity.

**intro:**
The content and interactive systems Futureman designs must integrate with the physical AV infrastructure IonQ's facilities vendors procure and install. The range of what "infrastructure" means on a project like this is wide: a well-configured media server and show controller at one end; a full Disguise or Pixera server with a dedicated sensor processing rack at the other. These are not the same project. The content architecture, the interactive logic, the sensor integration — all of it has to be designed around what's actually getting installed.

Until screen hardware, controllers, network topology, and sensor systems are confirmed, some scope elements carry technical dependencies that affect final delivery. This is not a caveat — it's the nature of building a first-of-kind space in a building that doesn't exist yet.

**What Futureman provides:**
Full technical consulting as part of every tier. We sit at the table with Seneca Group, Perkins Will, and AV integration vendors — not just at handoff, but from the moment we're engaged. We help specify the right equipment for the experience, ensure procurement decisions support the creative vision, and flag conflicts between the architectural plan and the content requirements before they become expensive. That consulting is included in scope.

**What we need early:**
The sooner Futureman is in the room with facilities vendors, the better the outcome. We'd recommend technical alignment meetings begin in the first two weeks after award — concurrent with Discovery, not after it.

---

## 10. Technical Capabilities

**meta:** Six grouped capability cards (or a 2x3 grid). Each group has a short heading and a bulleted list. This section is a recap / credibility layer — the *how* behind everything above.

**intro paragraph:**
Every concept, tier, and phase above is backed by a production capability set Futureman operates in-house. This is what enables the scope — from a single ambient video to a fully sensor-driven, visitor-personalized environment.

### Group 1 — Content Production

- Custom CGI and 3D development (ion trap visualization, quantum circuit animation, use case environments, large-format ambient loops)
- Motion design for extended loop and transition systems
- Scriptwriting and narrative development for multi-register audiences
- Storyboarding and visual language development
- AI-assisted content integration, b-roll grading, and footage integration
- Cinematic and spatial sound design

### Group 2 — Interactive & Sensor Systems

- Real-time camera-based visitor processing (TensorFlow and equivalent video processing libraries)
- Motion, thermal, and acoustic sensor integration
- Gesture recognition and multi-user gesture interaction (Minority Report-style)
- Presence detection and reactive content triggering
- Digital twin and biometric feedback layers
- Simultaneous multi-visitor state management across shared surfaces

### Group 3 — Content Delivery Infrastructure

- Media server configuration and show control (Disguise, Pixera, and equivalent pro-AV platforms)
- Large-format LED calibration and color management
- Floor projection and tabletop projection mapping
- Surround screen and dome-scale playback systems
- Spatial audio design and multi-zone audio routing
- Playback queue logic and module sequencing

### Group 4 — Content Architecture & Management

- Evergreen spine / swappable skin content system design
- Visitor personalization logic and audience-profile content queuing
- Content management framework built for low-lift IonQ-side updates
- Module swap architecture enabling content refresh without rebuild
- Multi-EBC portability (spine reusable across sites, skin localized per site)

### Group 5 — AV & Site Coordination

- Direct integration with AV and facilities vendors (Seneca Group, Perkins Will, and equivalents)
- Equipment specification and procurement consultation
- Architectural and spatial constraint resolution (ceiling heights, sightlines, ambient light)
- Network topology, file format, and playback spec alignment
- Early-stage technical alignment (concurrent with Discovery)

### Group 6 — QA, Commissioning & Handoff

- Functional testing of sensor triggers, state changes, and edge cases
- Cross-surface visual and audio review in context
- On-site calibration (brightness, color, audio, sensor sensitivity)
- Presenter training and content system walkthroughs
- Full handoff documentation (asset library, update protocols, vendor contact map)
- Defined 30-day post-launch support window

---

## 11. Pricing Tiers

**meta:** Four `TierCard`s in a row (responsive — 4 across on desktop, 2x2 on tablet, stacked on mobile). Each card shows: tier name, price, one-line pitch. Clicking expands the card (inline or modal) to show: full scope paragraph, what's included, what's not included, rationale.

**intro paragraph (above cards):**
The right tier depends on the depth of experience IonQ wants to deliver and the infrastructure that will be in place to support it.

### Card 1 — Micro · $250k
**one-liner:** You're getting screens. Let's make sure they're worth looking at.

**expanded — overview:**
IonQ is installing large-format displays regardless of what agency is selected. This tier is a focused content engagement built around that reality — no interactive systems, no sensor integration, no dome experience. Just world-class passive content, developed to the quality standard IonQ's audience expects, ready to play from day one.

Futureman works from IonQ's existing sales materials, technical resources, and a compressed strategy session with Marketing to develop a core suite of screen-ready assets: one large-format ambient hero video for the 1st floor lobby LED and a supporting graphic asset suite scaled for 3rd floor screens. The visual language and asset architecture established here are built to be compatible with higher tiers — so if IonQ expands the experience down the road, nothing gets replaced. It gets built on.

**expanded — included:**
- Compressed content strategy and discovery session with IonQ Marketing
- One large-format ambient hero video, custom CGI and 3D
- Evergreen static graphic asset suite scaled for all available screen formats
- Basic content documentation enabling IonQ to self-manage updates independently
- Footage-based elements leveraging existing b-roll and AI-assisted production

**expanded — not included:**
- Full SME interview series
- Interactive or sensor-driven content of any kind
- Dome experience
- Custom narrative framework workshop
- On-site commissioning support
- Additional video production beyond the hero piece

### Card 2 — Small · $320k–$450k
**one-liner:** Ambient video content + evergreen static graphics.

**expanded — overview:**
Large-format video production for the 1st floor lobby LED and 3rd floor screens — designed for ambient, looping playback that sustains repeated exposure without fatigue. Content developed in direct collaboration with IonQ technical SMEs and Marketing, translating quantum capabilities into education-first storytelling that works for a mixed-expertise audience, from PhDs to Members of Congress.

Deliverables include a core narrative video, a suite of evergreen static graphic assets scaled for all available screen formats across the EBC, and a modular asset structure that enables IonQ to transfer select screen content to existing EBCs independently. Real-time camera-based processing — using TensorFlow or similar libraries — can be incorporated to allow visitor presence in the lobby to influence the LED content dynamically, adding a layer of responsiveness without the full sensor integration of higher tiers.

All content is custom developed using CGI and 3D. Footage-based elements leverage existing b-roll and AI-assisted production.

**expanded — included:**
- Full SME interview series and narrative framework session
- Core narrative video (custom CGI + 3D)
- Evergreen static graphic asset suite across all screen formats
- Modular asset structure for multi-EBC transfer
- Optional real-time camera overlays in the lobby (TensorFlow-based presence response)

**expanded — not included:**
- Dome sensor system
- Gesture-based interactions
- Visitor personalization system
- Experience Center interactive installations

### Card 3 — Medium · $675k–$750k
**one-liner:** Everything in Small, plus sensor-driven content in the dome.

**expanded — overview:**
The dome transforms from a display into an environment. A sensor-activated content system responds to visitor presence and movement — visitors trigger state changes in the dome through where they stand, how they move, and how they interact with the space. The experience is designed to support both self-guided and presenter-led tour modes, with the presenter able to trigger specific states and sequences on demand.

Advanced camera systems enable gesture-based interaction — visitors influencing content through movement rather than touch, with multiple visitors able to affect different sections of the visualization simultaneously. A digital twin layer adds biometric feedback, giving visitors a sense of their own presence within the quantum environment. Think Flight of Passage at Animal Kingdom.

Content architecture is built to accommodate future refreshes as IonQ's use case library and business context evolve. Full AV coordination and handoff documentation for IonQ's facilities and integration vendors is included.

All content is custom developed using CGI and 3D. Footage-based elements leverage existing b-roll, AI-assisted production, and an optional additional production shoot if needed.

**expanded — included:**
- Everything in Small
- Dome sensor integration (presence, motion, gesture)
- Multi-visitor simultaneous interaction logic
- Digital twin / biometric feedback layer
- Self-guided and presenter-led mode support
- Full AV coordination and handoff documentation
- Optional additional production shoot

**expanded — not included:**
- Interactive content beyond the dome
- Visitor personalization system
- Experience Center floor-wide sensor integration

### Card 4 — Large · $1.15m–$1.5m
**one-liner:** Everything in Medium, plus interactive content throughout the Experience Center and a visitor-personalized content system.

**expanded — overview:**
Sensor and interactive content extends beyond the dome into key zones across the Experience Center floor — including tabletop projections and gesture-based interactions that give visitors direct physical engagement with the content. Additional screens are integrated across activation areas on the 3rd floor, coordinated with facilities vendors.

The defining feature of the Large tier is the visitor personalization system: the ability to surface tailored content tracks based on audience profile configured in advance of each visit. Tracks might include frameworks like *Quantum is Now*, *National Security Through Innovation*, or *Healthcare and Life Sciences* — the specific tracks are determined in Discovery based on IonQ's primary visitor profiles. IonQ Marketing configures and queues audience-specific modules before each visit through a custom content management framework built for low-lift operation.

The full content suite is paired with a defined refresh model: evergreen architecture designed for longevity, with an update process that IonQ's team can execute without agency involvement for routine changes.

All content is custom developed using CGI and 3D. Footage-based elements leverage existing b-roll, AI-assisted production, and additional production shoot(s) as needed.

**expanded — included:**
- Everything in Medium
- Experience Center floor sensor and interactive integration
- Tabletop and floor projection systems
- Multi-zone gesture-based interaction
- Visitor personalization system (audience-profile-driven content tracks)
- Custom content management framework for IonQ Marketing
- Evergreen refresh architecture and update protocols
- Extended production (additional shoots as needed)

**expanded — not included:**
- Post-launch retainer beyond the 30-day support window (available as a separate engagement)
- Hardware procurement (that sits with IonQ's AV vendors)

---

## 12. Team

**meta:** Four `TeamCard`s in a row. Photo (placeholder until headshots delivered), name, role, 1–2 sentence bio. Responsive grid.

**intro paragraph:**
The team leading this engagement for IonQ.

**cards:**

**Tate Stafford** — VP and Creative Director, Futureman
*Bio: TBD. Placeholder until final copy delivered.*

**Derek [Last Name]** — Executive Producer, Futureman
*Bio: TBD. Placeholder until final copy delivered.*

**Conrad [Last Name]** — CTO, Futureman
*Bio: TBD. Placeholder until final copy delivered.*

**Elliot Miller** — Senior Director, 24 Seven Agency Partnerships (SketchDeck)
*Bio: TBD. Placeholder until final copy delivered.*

---

## 13. Portfolio

**meta:** Three `PortfolioTile`s. Click opens a lightbox with a scrollable media carousel (images / short video) and a short written story under the media. All placeholder content for now.

**intro:** A selection of work from the Futureman studio.

- **Tile 1 —** [Placeholder project name] · [1-line description] · *media + story TBD*
- **Tile 2 —** [Placeholder project name] · [1-line description] · *media + story TBD*
- **Tile 3 —** [Placeholder project name] · [1-line description] · *media + story TBD*

---

## 14. Footer

**meta:** Simple footer. Logos left. Contact block right.

**logos:**
- Futureman
- 24 Seven Agencies

**contact:**
- Elliot Miller — Senior Director, 24 Seven Agency Partnerships — elliot.miller@sketchdeck.com
- Tate Stafford — VP, Futureman — tate@futuremandigital.com

---

## Content Style Notes for the Build

- Voice across the page is confident, direct, and slightly restrained. IonQ's aesthetic preference is institutional / high-brow (think Jaeger-LeCoultre, UN) — NOT flashy or techy (think LifeWave). Typography and layout decisions should track that register.
- Em-dashes and short declarative sentences are intentional. Don't "smooth them out."
- No stock startup language ("revolutionary," "game-changing," "cutting-edge"). The writing is proof, not pitch.
- Italics are used sparingly and deliberately for emphasis or in-universe quotes ("*we didn't invent this. We learned to harness it.*"). Preserve them.
- "IonQ" is always "IonQ" — never "Ion Q" or "IONQ."

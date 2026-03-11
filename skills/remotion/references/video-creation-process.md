# Remotion Video Creation Process

A structured process for creating programmatic videos with Remotion. Follow these steps sequentially. Step 2 generates 5 video brief variants. Steps 4 and 5 require approval before implementation begins.

---

## Step 0: Brand Identification

Before any creative work, identify the brand. Ask the user: **"What brand is this video for?"**

**If the brand has a preset** (see Step 5), use it directly. No further brand questions needed.

**If the brand is not listed**, ask the user to provide a brand website URL or brand guidelines document. Extract from the website/guidelines: background color, primary accent, secondary accent, text colors, font family, and theme (light/dark). If no guidelines exist, ask for at minimum: primary color, background color, and font preference.

---

## Step 1: Creative Brief

Gather and lock the following before any creative work begins.

| Field | Description | Example |
|-------|-------------|---------|
| **Purpose** | Why does this video exist? What problem does it solve? | "Explain the Agentic Loop Framework for prospects who land on the homepage" |
| **Audience** | Who is watching? What do they already know? | "B2B marketing leaders evaluating growth partners" |
| **Core message** | One sentence. If the viewer remembers one thing, what is it? | "GrowthNode runs a continuous insight-hypothesis-action loop that compounds over time" |
| **Content type** | What kind of asset is this video promoting? | blog-post, case-study, tool-launch, webinar, etc. |
| **Distribution channels** | Where will this video live? List all intended placements | Website embed, LinkedIn post, sales deck |
| **CTA** | What should the viewer do after watching? | Visit growthnode.ai |
| **Source assets** | Existing brand components, website sections, design files to reference | `LoopFramework.astro`, brand color palette |
| **Tone** | Technical, conversational, bold, minimal, playful? | "Minimal, confident, technical but accessible" |
| **Brand** | Brand identified in Step 0 | FunnelEnvy, Reform, GrowthNode, MIA, or custom |

### Brief Template

```
Purpose: [Why this video exists]
Audience: [Who is watching]
Core message: [One sentence]
Content type: [blog-post, case-study, webinar, podcast, lead-magnet, product-update, tool-launch, industry-report, event-recap, client-testimonial, playbook, template, ai-demo, custom-gpt]
Channels: [Where it will be distributed]
CTA: [What the viewer should do next]
Source assets: [Files, components, or URLs to reference]
Tone: [Descriptive words for the feel]
Brand: [Brand name from Step 0]
```

---

## Step 2: Generate 5 Video Brief Variants

After locking the creative brief, generate all 5 variants as one-page briefs. Present them to the user for selection before proceeding to specs.

### Variant A: Problem → Solution Story

A narrative arc that names the audience's pain, then reveals the solution. Motion graphics with text animation.

**Scene-by-scene template:**

| # | Time | Visual | Overlay Text | Transition |
|---|------|--------|-------------|------------|
| 1 | 0-4s | Bold text on brand background, subtle pulse/shake animation | Problem statement (1-2 lines) | Fade in |
| 2 | 4-8s | Pain amplification — icons, red/warning accents, visual tension | Why the problem persists (1 line) | Cut or slide |
| 3 | 8-14s | Transition to solution — brand accent color takes over, clean layout | Solution introduction + key benefit | Color wipe |
| 4 | 14-18s | Feature/capability highlight with supporting visual | Second benefit or proof point | Slide |
| 5 | Last 3s | Brand card | Logo + tagline + URL + CTA | Fade |

**Best for**: Blog posts, playbooks, lead magnets, product updates, tool launches.

**Animation style**: Spring (smooth) for entrances, ease-out for exits. Problem scenes use slightly faster timing to create tension. Solution scenes use slower, more confident pacing.

### Variant B: Asset Demo (Conditional)

The visual approach depends on the content type.

#### B1: Animated Terminal Demo (CLI tools, terminal-based tools, GitHub repos with CLI)

| # | Time | Visual | Overlay Text | Transition |
|---|------|--------|-------------|------------|
| 1 | 0-3s | Dark terminal background (`#1a1a2e` or brand terminal bg), cursor blink | Hook: what the tool does (one line) | Fade in |
| 2 | 3-7s | Command typed character by character with cursor | The command being run | Typewriter |
| 3 | 7-12s | Output renders line by line with syntax highlighting, callout annotation on key output | Key output with annotation | Line-by-line reveal |
| 4 | 12-16s | Second command or output section, new callout annotation | Second capability or result | Cut |
| 5 | Last 3s | Brand card (matches terminal theme) | Logo + tagline + URL | Fade |

**Animation style**: Typewriter for commands (40-60 chars/sec). Line-by-line reveal for output (150ms per line). Spring (snappy) for callout annotations.

#### B2: Content Preview Scroll-Through (everything else)

| # | Time | Visual | Overlay Text | Transition |
|---|------|--------|-------------|------------|
| 1 | 0-3s | Title card / asset cover with brand background | Hook from editorial angle | Fade in |
| 2 | 3-8s | Simulated scroll through the asset. Callout annotation (box/arrow in brand accent color) highlights a key section | Plain-language benefit | Pan / scroll |
| 3 | 8-13s | Zoom into a specific chart, result, framework, or quote. Callout annotation on focal point | Second benefit or proof point | Scroll / zoom |
| 4 | 13-18s | Additional section preview. Callout annotation on a different high-value element | Third key takeaway | Scroll / zoom |
| 5 | Last 3s | Brand card | Logo + tagline + URL | Fade |

**Visual mapping by content type:**

| Asset Type | What the Scroll Shows | Callout Focus |
|---|---|---|
| Blog post | Article scrolling with highlighted paragraphs | Pull quotes, key data points, frameworks |
| Case study | Results page, before/after metrics | The headline metric, client quote |
| Webinar | Slide deck highlights, speaker screen | Key insight slide, data visualization |
| Podcast | Episode art, guest photo, quote cards | Key quote, episode topic card |
| Lead magnet / playbook | Table of contents, featured pages | Framework diagrams, actionable sections |
| Product update | UI screenshots showing the new feature | Before/after UI, new capability |
| Industry report | Key charts, data tables, findings | Headline stat, trend visualization |
| Template | Filled-in example showing the template in use | Key formulas, sample data, output section |
| Custom GPT | Prompt/response exchange in chat UI | The most impressive response |
| Event recap | Photos, speaker moments, key slides | Highlight moment |
| Client testimonial | Quote card design, results metrics | Client quote, key result number |

**Animation style**: Smooth vertical scroll (linear interpolation). Callout annotations use spring (bouncy) entrance. Zoom uses ease-in-out.

### Variant C: Stats/Impact Kinetic Typography

Pure motion graphics. Animated numbers, bold typography, no UI or screenshots. Each scene is one stat or impact statement.

| # | Time | Visual | Overlay Text | Transition |
|---|------|--------|-------------|------------|
| 1 | 0-4s | Large animated number counting up (e.g., 147%) on brand background | Metric label below the number | Scale up + fade |
| 2 | 4-8s | Second stat with different animation (scale, slide, typewriter) | Context line | Slide from right |
| 3 | 8-12s | Third stat or key quote in large type | Attribution or source | Fade + scale |
| 4 | 12-16s | Summary statement, all key numbers visible simultaneously | Synthesis line | Staggered fade-in |
| 5 | Last 3s | Brand card | Logo + tagline + URL | Fade |

**Best for**: Case studies, industry reports, event recaps, client testimonials, any asset with strong numbers.

**Animation style**: Mixed — each stat uses a different entrance animation for variety. Number counting uses linear interpolation. Text uses spring (snappy).

### Variant D: Before/After Split Screen

Side-by-side or sequential comparison showing transformation. The screen splits to contrast the "before" state with the "after" state.

| # | Time | Visual | Overlay Text | Transition |
|---|------|--------|-------------|------------|
| 1 | 0-3s | Full-screen "Before" label with problem visual (cluttered dashboard, manual process, old workflow) | "Before [Product/Asset]" | Fade in |
| 2 | 3-7s | Before state details — pain points highlighted with red/warning accents, icons for friction | 1-2 specific problems (e.g., "Manual reporting. 4 hours/week.") | Slide in elements |
| 3 | 7-8s | Split-screen wipe transition — brand accent color divider slides across | (transition moment) | Horizontal wipe |
| 4 | 8-13s | "After" state — clean, optimized, brand-colored visuals | Key result (e.g., "Automated. 12 minutes.") | Wipe reveal |
| 5 | 13-17s | After state details — metrics, improvements, green/success accents | 1-2 proof points | Slide in elements |
| 6 | Last 3s | Brand card | Logo + tagline + URL | Fade |

**Best for**: Case studies, product updates, client testimonials, tool launches, playbooks, any asset with a clear transformation narrative.

**Animation style**: Before scenes use slightly desaturated colors and heavier weight. After scenes use brand accent colors and lighter, more confident animation. The wipe transition should be satisfying and decisive (300-500ms).

**Layout options:**
- **Horizontal split**: Before on left, After on right (works best at 1080x1080 and 1920x1080)
- **Vertical split**: Before on top, After on bottom (works best at 1080x1920)
- **Sequential**: Full-screen Before → wipe → full-screen After (works at all dimensions)

### Variant E: Social Proof Montage

Cycles through testimonials, client quotes, logos, and metrics in a rhythm-driven sequence.

| # | Time | Visual | Overlay Text | Transition |
|---|------|--------|-------------|------------|
| 1 | 0-3s | Hook stat or headline claim on brand background | Bold claim (e.g., "Trusted by 200+ B2B SaaS teams") | Fade in |
| 2 | 3-7s | First testimonial card — quote + name + company logo | Client quote (1-2 lines) | Slide in from right |
| 3 | 7-11s | Second testimonial card with different animation | Second client quote | Scale up + fade |
| 4 | 11-15s | Metrics bar — animated counters showing 2-3 aggregate results | Key numbers (e.g., "147% avg MQL increase") | Counter animation |
| 5 | 15-17s | Logo wall — 6-12 client/partner logos fade in on grid | "Join [X]+ companies" | Staggered grid fade |
| 6 | Last 3s | Brand card | Logo + tagline + URL + CTA | Fade |

**Best for**: Client testimonials, case studies, event recaps, industry reports, any asset that benefits from third-party credibility.

**Animation style**: Each testimonial card uses a different entrance for visual variety. Metric counters use linear interpolation for the counting effect. Logo grid uses staggered spring (smooth) entrances.

### Variant F: Framework/Process Visualization

Progressive build of a conceptual framework or process diagram. Each scene adds a node/step to the visual, building the full picture before the viewer's eyes. Use cases ground the abstract framework in concrete applications.

| # | Time | Visual | Overlay Text | Transition |
|---|------|--------|-------------|------------|
| 1 | 0-3.5s | Bold text on brand background, staggered line reveals | Hook: name the tension (e.g., "You have the data. You have the tools. You're missing the loop.") | Staggered fade + Y-translate |
| 2 | 3.5-6s | Logo/wordmark spring entrance, optional logomark | Brand identification + tagline | Spring scale |
| 3 | 6-8s | Tagline (uppercase, small, accent color) + headline (large) | Framework title (e.g., "The Agentic Loop Framework") | Fade + spring |
| 4 | 8-10s | First node springs in with icon. Connector path starts drawing. Description text swaps. | Node 1 name + description | Blur-to-sharp + spring |
| 5 | 10-13s | Second node springs in from incoming path direction. Path draws to next node. | Node 2 name + description | Directional slide + blur |
| 6 | 13-16s | Third node springs in. Path draws. If loop structure, path draws back to first node. | Node 3 name + description | Directional slide + blur |
| 7 | 16-19s | Optional additional nodes. Loop closes with path flash. Center label appears. Pulse dot begins traveling. | "Execute, measure, repeat" or similar | Path flash + pulse start |
| 8 | 19-22s | All nodes visible. Pulse accelerates (4s → 2s cycle). Node glows intensify. Background breathes. | Compounding message (e.g., "Results feed back. The loop compounds.") | Acceleration + glow |
| 9 | 22-28s | Framework dims to ~10% opacity. Use cases cycle: each fades in, holds ~1.5s, fades out. Optional colored pill/badge per use case. | 3-5 concrete applications (e.g., "Paid Media / Reallocate budget from performance signals") | Crossfade with slight horizontal slide |
| 10 | Last 2-3s | Brand card | URL + closing tagline + CTA | Spring + optional flourish |

**Best for**: Proprietary frameworks, methodologies, process explanations, "how it works" content, strategy documents, approach overviews.

**Animation style**: Spring entrances for nodes, SVG `stroke-dashoffset` path drawing for connectors, pulse/comet animation for loops. V2-level polish: blur-to-sharp materializations (`filter: blur` → clear), glow trails on paths (SVG `feGaussianBlur` filter), comet tail pulse (3-dot trail with trailing opacity), accent-bar descriptions, use case pills with colored badges, dot grid background for depth.

**Key characteristics that distinguish this from other variants:**
- The visual is built progressively (not revealed all at once)
- Each scene adds a component to a persistent diagram that stays visible across scenes
- Connector paths draw on with animated dash-offset
- Use cases ground the abstract framework in real applications
- Closing restates the framework's name/concept
- Works for any node-and-edge structure: triangles, loops, funnels, linear flows, concentric rings

**Reference implementations:** `GrowthNodeAgenticLoop.tsx` (V1) and `GrowthNodeAgenticLoopV2.tsx` (V2) in the remotion-videos project.

### Variant Selection Guide

| Content Type | Recommended Variants (in order of fit) |
|---|---|
| Blog post | A, C, D |
| Case study | C, D, E |
| Webinar / Podcast | A, B2 (scroll-through), C |
| Lead magnet / Playbook / Guide | A, B2 (scroll-through), D, F |
| Product update | A, D, C |
| Tool launch (CLI) | B1 (terminal), A, C |
| Tool launch (non-CLI) | B2 (scroll-through), A, D |
| Industry report | C, A, B2 (scroll-through) |
| Event recap | C, E, A |
| Client testimonial | E, C, D |
| Template | B2 (scroll-through), A, D |
| AI demo / Custom GPT | B1 or B2, A, C |
| Framework / Methodology | F, A, C |
| Strategy document | F, A, C |
| "How it works" content | F, A, D |

### Presenting Variants

When presenting variants to the user:
1. Generate all 6 as one-paragraph summaries with the scene-by-scene table
2. Highlight the recommended variant(s) based on the content type
3. The user selects one variant or requests a hybrid of two
4. Lock the selected variant before proceeding to Step 3

---

## Step 3: Format and Specs

Specs are derived from the brief and selected variant. Use the decision matrix below.

### Format Decision Matrix

| Distribution Channel | Recommended Dimensions | Duration Range | Notes |
|---------------------|----------------------|----------------|-------|
| LinkedIn feed post | 1080x1080 (1:1) | 15-30s | Square performs best in feed |
| LinkedIn carousel/article | 1920x1080 (16:9) | 30-60s | Widescreen for embedded context |
| Twitter/X feed | 1080x1080 (1:1) or 1920x1080 (16:9) | 15-45s | Under 2:20 total limit |
| Instagram Reels / TikTok | 1080x1920 (9:16) | 15-60s | Vertical, full-screen |
| Instagram feed | 1080x1080 (1:1) | 15-30s | Square |
| Website embed | 1920x1080 (16:9) | 15-60s | Widescreen, can be longer |
| Sales deck / presentation | 1920x1080 (16:9) | 15-45s | Match slide dimensions |
| Email embed (GIF) | 600x600 or 800x450 | 5-10s | Must be lightweight |

### Specs Template

```
Dimensions: [width]x[height]
Duration: [X] seconds ([X * fps] frames)
FPS: 30 (default)
Composition ID: [PascalCase identifier]
Loop: [yes/no - does last frame connect to first?]
Output formats: [mp4, gif, webm]
```

### Multi-Channel Adaptation

If the video targets multiple channels with different formats, define a **primary format** and list **adaptations**:

```
Primary: 1080x1080 (LinkedIn + Twitter feed)
Adaptations:
  - 1920x1080 (website embed, sales deck)
  - 1080x1920 (Instagram Reels)
```

Adaptations may require layout adjustments, not just cropping. Flag these during scene breakdown.

---

## Step 4: Scene Breakdown

This is the most critical step. Every scene must be defined before code is written. Changes to scenes after implementation are expensive. Use the selected variant's scene template as the starting structure, then customize.

### Narrative Arc

Short-form video follows a consistent structure:

```
Hook (stop the scroll)
  → Context (who/what, brand identification)
    → Core Content (the thing itself, built progressively)
      → Proof/Application (why it matters, use cases)
        → CTA (what to do next)
```

Not every video needs all five stages. A 10-second GIF might only have Hook + Core + CTA.

### Scene Definition Template

For each scene, define:

| Field | Description |
|-------|-------------|
| **Scene number and name** | Sequential identifier (e.g., "Scene 3: Framework Title") |
| **Timing** | Start and end in seconds (frames are calculated from fps) |
| **Copy** | Exact text that appears on screen. Bold key words. Indicate hierarchy (headline, description, label) |
| **Animation description** | What moves, in what order, how it enters/exits. Use plain language, not code |
| **Visual elements** | Icons, shapes, diagrams, images, or UI components in the scene |
| **Transitions** | How this scene enters and how it exits (fade, slide, cut, overlap) |
| **Purpose** | Why this scene exists in the narrative. One sentence |

### Scene Table Format

| # | Name | Time | Copy | Animation | Purpose |
|---|------|------|------|-----------|---------|
| 1 | Hook | 0-3.5s | "You have the data." / "You have the tools." / "You're missing **the loop**." | Lines fade up sequentially, 0.7s apart. "the loop" highlighted in accent color. All fade out together | Stop the scroll. Name the tension |
| 2 | Brand | 3.5-6s | "GrowthNode" / "AI Native Growth Engineers" | Logo springs in with bounce. Description fades in below | Brand identification |
| ... | ... | ... | ... | ... | ... |

### Timing Guidelines

| Video Duration | Recommended Scene Count | Avg Scene Duration |
|---------------|------------------------|-------------------|
| 10s | 3-4 | 2.5-3.3s |
| 15s | 4-6 | 2.5-3.75s |
| 30s | 8-12 | 2.5-3.75s |
| 60s | 12-20 | 3-5s |

Rules of thumb:
- Hook scene: 2-4 seconds maximum
- CTA scene: 2-3 seconds (should hold, not rush)
- Core content scenes can be longer if building progressively
- Transition overlaps reduce total duration (account for this)

### Approval Gate

Present the complete scene table to the user for approval. Lock copy, timing, and narrative structure before proceeding. Animation details can be refined during implementation, but the scene list and copy should not change.

---

## Step 5: Visual Design

### Brand Theme Presets

Use these for known brands. Skip color questions if the brand matches a preset.

| Brand | Background | Primary Accent | Secondary Accent | Text Primary | Text Muted | Font | Theme |
|-------|-----------|---------------|-----------------|-------------|-----------|------|-------|
| FunnelEnvy | `#FFFFFF` / `#1a1a2e` (terminal) | `#3B82F6` (Blue) | `#8B5CF6` (Purple) | `#000000` | `#6B7280` | Inter, system | Light |
| Reform | `#FFFFFF` / `#1a1a2e` (terminal) | `#48EC80` (Green) | `#EDE630` (Yellow) | `#000000` | `#6B7280` | Inter, system | Light |
| GrowthNode | `#0f0a1a` (all scenes) | `#8B5CF6` (Purple) | `#3B82F6` (Blue) | `#FFFFFF` | `#a1a1aa` | Inter, system | Dark |
| MIA | `#F7F4FA` / `#1c1422` (dark) | `#F1DE71` (Yellow) | `#7184F1` (Purple) | `#1c1422` / `#f7f4fa` (dark) | `rgba(28,20,34,0.62)` | system-ui, -apple-system, Segoe UI | Light |

**MIA accent palette**: Blue `#71C4F1`, Purple `#7184F1`, Pink `#F171C4`, Green `#71F19E`

**Custom brands**: If the brand is not listed above, extract colors from the brand website or guidelines provided in Step 0. Fill the same roles below.

### Color Palette

Define the full palette before implementation. Minimum required:

| Role | Purpose | Example |
|------|---------|---------|
| **Background** | Main background color | `#09090b` |
| **Primary accent** | Key highlights, important elements | `rgba(139, 92, 246, 1)` (purple) |
| **Secondary accent** | Supporting elements, secondary nodes | `rgba(59, 130, 246, 1)` (blue) |
| **Tertiary accent** | Additional differentiation (if needed) | `rgba(236, 72, 153, 1)` (pink) |
| **Text primary** | Headlines, labels | `#fafafa` |
| **Text secondary** | Descriptions, body text | `#a1a1aa` |
| **Text tertiary** | Subtle labels, de-emphasized text | `#71717a` |
| **Border/divider** | Subtle separators | `rgba(255, 255, 255, 0.08)` |

### Typography

| Element | Font | Weight | Size (at 1080px) |
|---------|------|--------|-------------------|
| Headline | [Font family] | Bold (700) | 48-64px |
| Subheadline | [Font family] | Semi-bold (600) | 32-40px |
| Body/description | [Font family] | Regular (400) | 24-28px |
| Label/tagline | [Font family] | Medium (500) uppercase | 16-20px |

### Animation Style

Choose the dominant motion style:

| Style | When to Use | Remotion Implementation |
|-------|-------------|------------------------|
| **Spring (bouncy)** | Entrances, playful brand, emphasis | `spring({ damping: 12, mass: 0.5 })` |
| **Spring (smooth)** | Professional, subtle entrances | `spring({ damping: 200 })` |
| **Spring (snappy)** | Quick, confident transitions | `spring({ damping: 20, stiffness: 300 })` |
| **Linear** | Progress bars, path drawing, mechanical motion | `interpolate()` with no easing |
| **Ease out** | Exits, elements leaving the scene | `interpolate()` with `Easing.out(Easing.quad)` |

### Source of Truth

If the video must match an existing design (website, app, brand guide):

```
Source file: [path to component or design file]
Elements to match: [colors, layout, icons, typography]
Last verified: [date]
```

---

## Step 6: Architecture Decision

This step is deterministic based on scene complexity. The agent resolves this, not the user.

### File Structure Decision

| Condition | Approach |
|-----------|----------|
| Under 15 scenes, no reusable components | Single file (all scenes in one `.tsx`) |
| 15+ scenes or reusable scene components | Multi-file (scene components in `scenes/` directory) |
| Shared visual elements across scenes | Persistent layer with opacity envelope |
| Multiple compositions sharing components | Shared `components/` directory |

### Timing System

Always use a centralized timing constant:

```typescript
const T = {
  hookStart: 0,        hookEnd: 105,
  brandStart: 105,     brandEnd: 185,
  // ... all scene boundaries
};
```

This makes timing adjustments propagate automatically.

### Composition Registration

Register in `Root.tsx` with proper folder organization:

```typescript
<Folder name="ProjectName">
  <Composition
    id="CompositionId"
    component={VideoComponent}
    durationInFrames={totalFrames}
    fps={30}
    width={1080}
    height={1080}
  />
</Folder>
```

---

## Step 7: Implementation

With scenes, design, and architecture locked, write the code.

### Implementation Checklist

- [ ] Create timing constants from scene breakdown
- [ ] Set up color and typography constants from design decisions
- [ ] Build scene-by-scene, previewing each in Remotion Studio
- [ ] All animation driven by `useCurrentFrame()` (no CSS transitions)
- [ ] Use Remotion components (`<Img>`, `<Video>`, `<Audio>`) not native HTML
- [ ] Use `staticFile()` for all public folder assets
- [ ] Test transitions between scenes for smooth flow
- [ ] Verify total duration matches spec
- [ ] Preview at 1x speed for pacing check

### Common Patterns

| Pattern | Implementation |
|---------|---------------|
| Sequential text lines | `interpolate()` with staggered `inputRange` offsets |
| Element entrance | `spring()` with scale from 0 to 1 |
| Fade in/out | `interpolate()` on opacity, 0 to 1 |
| Path drawing | SVG `stroke-dashoffset` animated via `interpolate()` |
| Persistent background element | Single opacity envelope wrapping shared layer |
| Cycling content | Array of items with calculated frame ranges per item |

---

## Step 8: Output Documentation

Generate an output document for every completed video. This serves as the reference for future edits, adaptations, and handoffs.

### Output Document Template

```markdown
# [Video Title]

[One sentence description of what this video is and what it's for.]

## Specs

| Property | Value |
|----------|-------|
| Format | [dimensions] |
| Duration | [X] seconds ([frames] frames) |
| FPS | [fps] |
| Composition ID | `[ID]` |
| Source file | `src/[filename].tsx` |

## How to Preview

[Commands to preview in Remotion Studio]

## How to Render

[Commands for each output format: mp4, gif, webm]

## Distribution

[List of intended placements and channels]

## Scene Breakdown

[Full scene table from Step 3, updated with final timing]

## Color Palette

[Final palette table from Step 4]

## Timing Configuration

[The T constant or timing system used]

## Architecture Notes

[File structure, key decisions, shared layers]

## Source of Truth

[Reference files for design consistency]

## Iteration Guide

[Table of common changes and where to make them]
```

---

## Process Summary

```
Step 0: Brand Identification      → Identify brand, use preset or extract from website/guidelines
Step 1: Creative Brief            → Lock purpose, audience, message, content type, channels, CTA, brand
Step 2: Generate 6 Variants       → Present A/B/C/D/E/F video brief variants for selection
Step 3: Format and Specs          → Resolve dimensions, duration, fps from brief + selected variant
Step 4: Scene Breakdown           → Define every scene with copy, timing, animation  ← APPROVAL GATE
Step 5: Visual Design             → Lock colors, typography, animation style         ← APPROVAL GATE
Step 6: Architecture Decision     → Agent resolves file structure and timing system
Step 7: Implementation            → Write code against locked decisions
Step 8: Output Documentation      → Generate reference doc for the completed video
```

Steps 4 and 5 are approval gates. Everything before them is input gathering and variant selection. Everything after them is execution.

**Content rule**: Every variant must be self-explanatory. A viewer scrolling with zero context should understand the value from the video alone. No scene should depend on external knowledge. Copy must carry the full message independently.

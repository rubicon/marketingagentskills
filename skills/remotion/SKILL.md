---
name: remotion
version: 3.0.0
description: Remotion video creation in React - process workflow, 5 video brief variants, and technical best practices
metadata:
  tags: remotion, video, react, animation, composition, programmatic-video
---

## When to Use

Use this skill when:
- Creating a new Remotion video from scratch
- Generating video brief variants for a content asset
- Modifying an existing Remotion composition
- Debugging Remotion animation or rendering issues
- Working with any Remotion-specific APIs or components

## Video Creation Process

When creating a new Remotion video, follow this 8-step process. Step 2 generates 5 video brief variants for selection. Steps 4 and 5 are approval gates. Do not write code until both are approved.

For the full process document with templates and decision matrices, read [references/video-creation-process.md](references/video-creation-process.md).

### Step 1: Creative Brief

Gather and lock before any creative work:

```
Purpose: [Why this video exists]
Audience: [Who is watching]
Core message: [One sentence]
Content type: [blog-post, case-study, webinar, podcast, lead-magnet, product-update, tool-launch, industry-report, event-recap, client-testimonial, playbook, template, ai-demo, custom-gpt]
Channels: [Where it will be distributed]
CTA: [What the viewer should do next]
Source assets: [Files, components, or URLs to reference]
Tone: [Descriptive words for the feel]
Brand: [FunnelEnvy, Reform, GrowthNode, or custom — determines color theme]
```

### Step 2: Generate 5 Video Brief Variants

Present all 5 variants as one-page briefs. The user selects one (or a hybrid) before proceeding to specs.

#### Variant A: Problem → Solution Story

A narrative arc that names the audience's pain, then reveals the solution. Motion graphics with text animation.

| # | Time | Visual | Overlay Text |
|---|------|--------|-------------|
| 1 | 0-4s | Bold text on brand background, subtle pulse/shake animation | Problem statement (1-2 lines) |
| 2 | 4-8s | Pain amplification — icons, red/warning accents, visual tension | Why the problem persists (1 line) |
| 3 | 8-14s | Transition to solution — brand accent color takes over, clean layout | Solution introduction + key benefit |
| 4 | 14-18s | Feature/capability highlight with supporting visual | Second benefit or proof point |
| 5 | Last 3s | Brand card | Logo + tagline + URL + CTA |

**Best for**: Blog posts, playbooks, lead magnets, product updates, tool launches.

#### Variant B: Asset Demo (Conditional)

**If content type is CLI tool, terminal-based tool, or GitHub repo with CLI** → Animated Terminal Demo:

| # | Time | Visual | Overlay Text |
|---|------|--------|-------------|
| 1 | 0-3s | Dark terminal background, cursor blink | Hook: what the tool does (one line) |
| 2 | 3-7s | Command typed character by character | The command being run |
| 3 | 7-12s | Output renders line by line with syntax highlighting | Key output with annotation callout |
| 4 | 12-16s | Second command or output section | Second capability or result |
| 5 | Last 3s | Brand card (matches terminal theme) | Logo + tagline + URL |

**If content type is anything else** → Content Preview Scroll-Through:

| # | Time | Visual | Overlay Text |
|---|------|--------|-------------|
| 1 | 0-3s | Title card / asset cover with brand background | Hook from editorial angle |
| 2 | 3-8s | Simulated scroll through the asset. Callout annotation highlights a key section | Plain-language benefit |
| 3 | 8-13s | Zoom into a specific chart, result, framework, or quote | Second benefit or proof point |
| 4 | 13-18s | Additional section preview with callout annotation | Third key takeaway |
| 5 | Last 3s | Brand card | Logo + tagline + URL |

**Best for**: Tool launches (terminal), case studies, industry reports, templates, webinars (scroll-through).

#### Variant C: Stats/Impact Kinetic Typography

Pure motion graphics. Animated numbers, bold typography, no UI or screenshots. Each scene is one stat or impact statement.

| # | Time | Visual | Overlay Text |
|---|------|--------|-------------|
| 1 | 0-4s | Large animated number counting up (e.g., 147%) on brand background | Metric label below the number |
| 2 | 4-8s | Second stat with different animation (scale, slide, typewriter) | Context line |
| 3 | 8-12s | Third stat or key quote in large type | Attribution or source |
| 4 | 12-16s | Summary statement, all key numbers visible | Synthesis line |
| 5 | Last 3s | Brand card | Logo + tagline + URL |

**Best for**: Case studies, industry reports, event recaps, client testimonials, any asset with strong numbers.

#### Variant D: Before/After Split Screen

Side-by-side or sequential comparison showing transformation. The screen splits (vertically or horizontally) to contrast the "before" state with the "after" state.

| # | Time | Visual | Overlay Text |
|---|------|--------|-------------|
| 1 | 0-3s | Full-screen "Before" label with problem visual (cluttered dashboard, manual process, old workflow) | "Before [Product/Asset]" |
| 2 | 3-7s | Before state details — pain points highlighted with red/warning accents | 1-2 specific problems (e.g., "Manual reporting. 4 hours/week.") |
| 3 | 7-8s | Split-screen wipe transition — brand accent color divider slides across | Transition moment |
| 4 | 8-13s | "After" state — clean, optimized, brand-colored visuals showing the outcome | Key result (e.g., "Automated. 12 minutes.") |
| 5 | 13-17s | After state details — metrics, improvements, green/success accents | 1-2 proof points |
| 6 | Last 3s | Brand card | Logo + tagline + URL |

**Best for**: Case studies, product updates, client testimonials, tool launches, playbooks, any asset with a clear transformation narrative.

#### Variant E: Social Proof Montage

Cycles through testimonials, client quotes, logos, and metrics in a rhythm-driven sequence. Each "card" animates in, holds, and exits.

| # | Time | Visual | Overlay Text |
|---|------|--------|-------------|
| 1 | 0-3s | Hook stat or headline claim on brand background | Bold claim (e.g., "Trusted by 200+ B2B SaaS teams") |
| 2 | 3-7s | First testimonial card — quote + name + company logo, slides in | Client quote (1-2 lines) |
| 3 | 7-11s | Second testimonial card with different animation (scale, fade, flip) | Second client quote |
| 4 | 11-15s | Metrics bar — animated counters showing 2-3 aggregate results | Key numbers (e.g., "147% avg MQL increase") |
| 5 | 15-17s | Logo wall — 6-12 client/partner logos fade in on grid | "Join [X]+ companies" |
| 6 | Last 3s | Brand card | Logo + tagline + URL + CTA |

**Best for**: Client testimonials, case studies, event recaps, industry reports, any asset that benefits from third-party credibility.

### Variant Selection Guide

| Content Type | Recommended Variants (in order) |
|---|---|
| Blog post | A, C, D |
| Case study | C, D, E |
| Webinar / Podcast | A, B (scroll-through), C |
| Lead magnet / Playbook / Guide | A, B (scroll-through), D |
| Product update | A, D, C |
| Tool launch (CLI) | B (terminal), A, C |
| Tool launch (non-CLI) | B (scroll-through), A, D |
| Industry report | C, A, B (scroll-through) |
| Event recap | C, E, A |
| Client testimonial | E, C, D |
| Template | B (scroll-through), A, D |
| AI demo / Custom GPT | B (terminal or scroll-through), A, C |

### Step 3: Format and Specs

Resolve from the brief and selected variant using the format decision matrix:

| Channel | Dimensions | Duration |
|---------|-----------|----------|
| LinkedIn/Instagram feed | 1080x1080 | 15-30s |
| Website/presentation | 1920x1080 | 15-60s |
| Reels/TikTok/Stories | 1080x1920 | 15-60s |
| Email (GIF) | 600x600 or 800x450 | 5-10s |

Default FPS: 30. Only use 60 if smooth motion is critical.

```
Dimensions: [width]x[height]
Duration: [X] seconds ([X * fps] frames)
FPS: 30
Composition ID: [PascalCase]
Loop: [yes/no]
Output formats: [mp4, gif, webm]
Selected variant: [A/B/C/D/E or hybrid]
```

### Step 4: Scene Breakdown (APPROVAL GATE)

Define every scene before writing code. Use the selected variant's scene template as the starting structure, then customize for the specific content.

Present the scene table for approval.

**Scene table format:**

| # | Name | Time | Copy | Animation | Purpose |
|---|------|------|------|-----------|---------|
| 1 | Hook | 0-3s | Exact text | Motion description | Why it exists |

**Timing guidelines:**

| Duration | Scene Count | Avg Per Scene |
|----------|-------------|---------------|
| 10s | 3-4 | 2.5-3.3s |
| 15s | 4-6 | 2.5-3.75s |
| 30s | 8-12 | 2.5-3.75s |
| 60s | 12-20 | 3-5s |

Lock copy, timing, and narrative structure before proceeding.

### Step 5: Visual Design (APPROVAL GATE)

Lock before implementation:

**Color palette** (minimum required roles):
- Background, Primary accent, Secondary accent
- Text primary, Text secondary, Text tertiary
- Border/divider

**Brand theme presets** (use when working with Celerius brands):

| Brand | Background | Primary Accent | Text | Theme |
|-------|-----------|---------------|------|-------|
| FunnelEnvy | `#FFFFFF` (non-terminal) / `#1a1a2e` (terminal) | `#3B82F6` (Blue) | `#000000` / `#FFFFFF` | Light |
| Reform | `#FFFFFF` (non-terminal) / `#1a1a2e` (terminal) | `#48EC80` (Green) | `#000000` / `#FFFFFF` | Light |
| GrowthNode | `#0f0a1a` (all scenes) | `#8B5CF6` (Purple) | `#FFFFFF` | Dark |

**Typography**: Font family, weight hierarchy, sizes at target resolution.

**Animation style**: Spring (bouncy/smooth/snappy), linear, or ease-based. Pick a dominant style.

**Source of truth**: If matching an existing design, reference the source file.

### Step 6: Architecture Decision

Agent resolves this based on scene complexity:

| Condition | Approach |
|-----------|----------|
| Under 15 scenes | Single file |
| 15+ scenes or reusable parts | Multi-file with `scenes/` directory |
| Shared elements across scenes | Persistent layer with opacity envelope |

Always use a centralized timing constant (`const T = { ... }`).

### Step 7: Implementation

Write code against locked decisions. All animation must follow Remotion rules (see Technical Reference below).

### Step 8: Output Documentation

Generate a reference doc covering: specs, selected variant, preview/render commands, scene breakdown, color palette, timing config, architecture notes, iteration guide.

---

## Technical Reference

Read individual rule files for API details and code examples.

### Core Animation and Timing

- [rules/animations.md](rules/animations.md) - Animation fundamentals. All motion via `useCurrentFrame()`. No CSS transitions
- [rules/timing.md](rules/timing.md) - `interpolate()`, `spring()`, easing functions, spring configs
- [rules/sequencing.md](rules/sequencing.md) - `<Sequence>` and `<Series>` for timing, delay, and duration control
- [rules/trimming.md](rules/trimming.md) - Trim beginnings (negative `from`) and ends (`durationInFrames`)
- [rules/transitions.md](rules/transitions.md) - `<TransitionSeries>` with fade, slide, wipe, flip, clockWipe

### Media

- [rules/assets.md](rules/assets.md) - `staticFile()` for public folder assets
- [rules/videos.md](rules/videos.md) - `<Video>` with trimming, volume, speed, looping, pitch
- [rules/audio.md](rules/audio.md) - `<Audio>` with trimming, volume, speed, pitch
- [rules/images.md](rules/images.md) - `<Img>` component (ensures load before render)
- [rules/gifs.md](rules/gifs.md) - `<AnimatedImage>` for GIF/APNG/AVIF/WebP
- [rules/fonts.md](rules/fonts.md) - Google Fonts via `@remotion/google-fonts`, local fonts via `@remotion/fonts`

### Text and Captions

- [rules/text-animations.md](rules/text-animations.md) - Typewriter, word highlighting patterns
- [rules/measuring-text.md](rules/measuring-text.md) - `measureText()`, `fitText()`, `fillTextBox()`
- [rules/display-captions.md](rules/display-captions.md) - TikTok-style captions, word-by-word highlighting
- [rules/import-srt-captions.md](rules/import-srt-captions.md) - Parse `.srt` files with `parseSrt()`
- [rules/transcribe-captions.md](rules/transcribe-captions.md) - Whisper.cpp, Whisper Web, OpenAI API

### Composition and Metadata

- [rules/compositions.md](rules/compositions.md) - `<Composition>`, `<Still>`, `<Folder>`, `defaultProps`
- [rules/calculate-metadata.md](rules/calculate-metadata.md) - Dynamic duration, dimensions, and props

### Advanced

- [rules/3d.md](rules/3d.md) - `<ThreeCanvas>` with React Three Fiber
- [rules/charts.md](rules/charts.md) - SVG/D3.js charts animated via `useCurrentFrame()`
- [rules/lottie.md](rules/lottie.md) - `<Lottie>` component with `@remotion/lottie`
- [rules/tailwind.md](rules/tailwind.md) - TailwindCSS (no `transition-*` or `animate-*` classes)

### Media Utilities (Mediabunny)

- [rules/extract-frames.md](rules/extract-frames.md) - Extract video frames at timestamps
- [rules/can-decode.md](rules/can-decode.md) - Check video/audio decodability
- [rules/get-video-duration.md](rules/get-video-duration.md) - Video duration in seconds
- [rules/get-video-dimensions.md](rules/get-video-dimensions.md) - Video width and height
- [rules/get-audio-duration.md](rules/get-audio-duration.md) - Audio duration in seconds

### Layout

- [rules/measuring-dom-nodes.md](rules/measuring-dom-nodes.md) - `useCurrentScale()` for accurate measurements

---

## References

- [references/video-creation-process.md](references/video-creation-process.md) - Full process document with templates, decision matrices, and detailed guidance

---

## Hard Rules

These apply to all Remotion code. Violations will produce incorrect output.

1. **All animation driven by `useCurrentFrame()`**. No CSS transitions, no Tailwind `animate-*` or `transition-*` classes, no React Three Fiber `useFrame()`
2. **Use Remotion components** (`<Img>`, `<Video>`, `<Audio>`) not native HTML elements
3. **Use `staticFile()`** for all assets in the `public/` folder
4. **Time in seconds**: multiply by `fps` from `useVideoConfig()` to get frames
5. **No third-party animation libraries** driving motion (disable their animations, use `useCurrentFrame()` instead)

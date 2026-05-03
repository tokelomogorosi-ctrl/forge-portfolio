---
version: 1.0
name: Conversion Forge
description: A light, playful, Ogilvy-inspired marketing-systems brand for UK small businesses. The system anchors on a clean white canvas, charcoal type, and a single bright teal accent. Voltage comes from the cream-charcoal-teal contrast, austere where most agency brands are loud, confident where most are corporate. Type voice runs Inter at heavy display weight (900) for headlines and standard (400) for body, with all-caps eyebrows in 0.15em tracking. The signature visual is the dark "live pipeline" card, a charcoal surface with traffic-light dots, status pills, and a pulsing dot that signals the system is awake while the operator sleeps.

colors:
  # Primary brand
  teal:               "#4DD9D5"
  teal-dark:          "#2BB8B4"
  teal-light:         "#F0FFFE"
  teal-mid:           "#E0FAF9"

  # Ink / surfaces
  charcoal:           "#1A1A1A"
  charcoal-deep:      "#111111"
  body:               "#2D2D2D"
  muted:              "#666666"
  muted-soft:         "#999999"
  hairline:           "#E8E8E8"

  # Canvas
  white:              "#FFFFFF"
  surface-soft:       "#F8F8F8"

  # Status / signals
  status-success:     "#34C759"
  status-warning:     "#FFCC00"
  status-error:       "#FF3B30"
  whatsapp:           "#25D366"
  whatsapp-active:    "#128C7E"

  # Semantic roles
  primary:            "#4DD9D5"
  primary-hover:      "#2BB8B4"
  primary-bg-soft:    "#E0FAF9"
  on-primary:         "#1A1A1A"
  on-dark:            "#FFFFFF"
  on-light:           "#1A1A1A"
  link:               "#4DD9D5"
  border:             "#E8E8E8"
  border-strong:      "#1A1A1A"

typography:
  font-family-primary:  "Inter, system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif"
  font-weights:         [400, 500, 600, 700, 900]

  display-xl:
    fontFamily: "Inter, sans-serif"
    fontSize: "clamp(2.4rem, 5vw, 3.6rem)"
    fontWeight: 900
    lineHeight: 1.08
    letterSpacing: "-0.032em"
  display-lg:
    fontFamily: "Inter, sans-serif"
    fontSize: "clamp(2rem, 4vw, 2.8rem)"
    fontWeight: 900
    lineHeight: 1.15
    letterSpacing: "-0.03em"
  display-md:
    fontFamily: "Inter, sans-serif"
    fontSize: "1.6rem"
    fontWeight: 900
    lineHeight: 1.2
    letterSpacing: "-0.02em"

  title-lg:
    fontFamily: "Inter, sans-serif"
    fontSize: "1.2rem"
    fontWeight: 700
    lineHeight: 1.3
    letterSpacing: 0
  title-md:
    fontFamily: "Inter, sans-serif"
    fontSize: "1.05rem"
    fontWeight: 700
    lineHeight: 1.25
    letterSpacing: 0
  title-sm:
    fontFamily: "Inter, sans-serif"
    fontSize: "1rem"
    fontWeight: 700
    lineHeight: 1.3

  body-lg:
    fontFamily: "Inter, sans-serif"
    fontSize: "1.1rem"
    fontWeight: 400
    lineHeight: 1.6
  body-md:
    fontFamily: "Inter, sans-serif"
    fontSize: "1rem"
    fontWeight: 400
    lineHeight: 1.6
  body-sm:
    fontFamily: "Inter, sans-serif"
    fontSize: "0.9rem"
    fontWeight: 400
    lineHeight: 1.55

  eyebrow:
    fontFamily: "Inter, sans-serif"
    fontSize: "0.8rem"
    fontWeight: 600
    lineHeight: 1.4
    letterSpacing: "0.12em"
    textTransform: "uppercase"
  eyebrow-strong:
    fontFamily: "Inter, sans-serif"
    fontSize: "0.75rem"
    fontWeight: 700
    lineHeight: 1.4
    letterSpacing: "0.15em"
    textTransform: "uppercase"
  caption:
    fontFamily: "Inter, sans-serif"
    fontSize: "0.85rem"
    fontWeight: 500
    lineHeight: 1.4

  stat:
    fontFamily: "Inter, sans-serif"
    fontSize: "clamp(2.5rem, 5vw, 4rem)"
    fontWeight: 900
    lineHeight: 1
    letterSpacing: "-0.02em"
  step-num:
    fontFamily: "Inter, sans-serif"
    fontSize: "3rem"
    fontWeight: 900
    lineHeight: 1
    opacity: 0.15

rounded:
  xs: 4px
  sm: 6px
  md: 8px
  lg: 12px
  xl: 16px
  pill: 999px

spacing:
  base: 8px
  scale: [4px, 8px, 12px, 16px, 20px, 24px, 32px, 40px, 48px, 64px, 96px, 128px]
  section-y-mobile: 4rem
  section-y-desktop: 6rem
  container-max: 1140px
  container-padding: 2rem

shadows:
  subtle:    "0 4px 24px rgba(0, 0, 0, 0.08)"
  raised:    "0 12px 48px rgba(0, 0, 0, 0.12)"
  card-dark: "0 12px 48px rgba(0, 0, 0, 0.4)"

motion:
  ease-default: "cubic-bezier(.22, 1, .36, 1)"
  duration-fast: "200ms"
  duration-base: "300ms"
  duration-slow: "500ms"
  hover-lift: "translateY(-4px)"
  pulse-keyframe: "0%,100%{opacity:1} 50%{opacity:0.4}"

components:
  button-primary:
    background: "var(--teal)"
    color: "var(--charcoal)"
    padding: "0.85rem 1.8rem"
    border-radius: 8px
    font-weight: 700
    font-size: "0.95rem"
    hover-background: "var(--teal-dark)"
    hover-transform: "translateY(-2px)"
    transition: "background 200ms, transform 100ms"
  button-ghost:
    background: "transparent"
    color: "var(--body)"
    padding: "0.85rem 1.8rem"
    border: "1.5px solid var(--hairline)"
    border-radius: 8px
    hover-border: "var(--teal)"
    hover-color: "var(--teal)"
  button-outline:
    background: "transparent"
    color: "var(--charcoal)"
    border: "2px solid var(--charcoal)"
    border-radius: 8px
    hover-background: "var(--charcoal)"
    hover-color: "var(--white)"
  button-whatsapp:
    background: "var(--whatsapp)"
    color: "var(--white)"
    padding: "1rem 2.2rem"
    hover-background: "var(--whatsapp-active)"

  card-light:
    background: "var(--white)"
    border: "1px solid var(--hairline)"
    border-radius: 12px
    padding: "2rem"
    shadow: "var(--shadow-subtle)"
    hover-transform: "translateY(-4px)"
    hover-shadow: "var(--shadow-raised)"
    hover-border: "var(--teal)"
  card-dark:
    background: "var(--charcoal)"
    color: "var(--white)"
    border-radius: 16px
    padding: "1.5rem"
    shadow: "var(--shadow-card-dark)"
  card-featured:
    border: "2px solid var(--teal)"
    badge:
      background: "var(--teal)"
      color: "var(--charcoal)"
      position: "absolute, top: -12px, left: 50%"
      padding: "0.25rem 0.75rem"
      border-radius: "20px"

  pipeline-card:
    description: "Signature charcoal card simulating a live system feed. Traffic-light dots top-left, monospace-feel pipeline rows, pulsing green dot footer."
    background: "var(--charcoal)"
    border-radius: 16px
    padding: "1.5rem"
    traffic-dots:
      green: "#34C759"
      yellow: "#FFCC00"
      red: "#FF3B30"
    pipeline-row:
      background: "rgba(255, 255, 255, 0.05)"
      border-radius: 8px
      padding: "0.75rem"
    status-pill:
      new:    { bg: "rgba(77, 217, 213, 0.2)",  fg: "var(--teal)" }
      follow: { bg: "rgba(255, 204, 0, 0.2)",   fg: "#FFCC00" }
      booked: { bg: "rgba(52, 199, 89, 0.2)",   fg: "#34C759" }
    footer-pulse-dot: "8px green, 2s ease-in-out infinite, opacity 1 → 0.4"

  eyebrow-with-dot:
    description: "Section opener: teal dot + uppercase eyebrow. Used to anchor every major section."
    dot: "8px circle, var(--teal)"
    text: "0.8rem, weight 600, tracking 0.12em, uppercase, var(--teal)"
    gap: "0.5rem"

  trust-strip:
    description: "Hero proof block: stat | divider | stat | divider | stat. Light grey background, hairline divider 1px x 36px."
    background: "var(--surface-soft)"
    border: "1px solid var(--hairline)"
    border-radius: 12px
    padding: "1.2rem 1.5rem"

  logo-bar:
    description: "Trust logos sit on a charcoal band, plain text, hover-to-teal."
    background: "var(--charcoal)"
    text-color: "#888"
    hover-color: "var(--teal)"
    weight: 700
    letter-spacing: "0.05em"

  testimonial:
    background: "rgba(255, 255, 255, 0.05)"
    border: "1px solid rgba(77, 217, 213, 0.2)"
    border-radius: 12px
    padding: "2.5rem"
    quote-mark:
      family: "Georgia, serif"
      size: "5rem"
      color: "var(--teal)"
      opacity: 0.3

layout:
  philosophy: "Maximum clarity, minimum density. White breathing room is a feature, not a void. Each section opens with eyebrow + headline, never with a paragraph."
  container-max: "1140px"
  container-padding: "0 2rem"
  section-pattern: ["section-white", "section-teal-light", "section-dark"]
  grid-default: "repeat(auto-fit, minmax(280px, 1fr))"
  hero-grid: "1fr 1fr (desktop) → 1fr (mobile, hide visual on <768px)"
  vertical-rhythm: "6rem section padding desktop, 4rem mobile"

depth:
  philosophy: "Two shadow tiers, never three. Subtle for resting cards, raised for hover. No drop-shadows on dark surfaces, use border + bg-tint instead."
  light-cards-resting: "0 4px 24px rgba(0, 0, 0, 0.08)"
  light-cards-hover:   "0 12px 48px rgba(0, 0, 0, 0.12)"
  dark-card-resting:   "0 12px 48px rgba(0, 0, 0, 0.4)"
  divider-hairline:    "1px solid var(--hairline)"

dos-and-donts:
  do:
    - "Use the teal accent surgically: one dot, one underline, one CTA per surface, no more"
    - "Lead every section with eyebrow + dot, then headline, then optional sub"
    - "Pair a charcoal pipeline-card with white surrounding space, the contrast is the brand"
    - "Use Inter 900 for display, never below 700 for headlines"
    - "Keep tracking tight: -0.03em on display, 0 on body, 0.12-0.15em on eyebrows"
    - "Numbers earn the page. Stats use Inter 900 at clamp(2.5rem, 5vw, 4rem)"
    - "Pulse the live dot. The brand promise is *running while you sleep*. The dot proves it"
  dont:
    - "Do not introduce a second display font. Inter handles everything"
    - "Do not use teal on teal. Teal is always against white, charcoal, or hairline"
    - "Do not use orange, gold, or warm tones, they belong to the prior identity, not this one"
    - "Do not use serif anywhere except the testimonial quote-mark glyph"
    - "Do not crowd cards. Padding never below 1.5rem, never above 2.5rem"
    - "Do not pair shadow with bright border. Either raise or outline, never both"
    - "Do not use em-dashes (, ) or en-dashes (-) anywhere in copy. Cardinal humanizer rule"
    - "Do not write hype words: revolutionary, game-changing, world-class, unleash, leverage, navigate the landscape"

responsive:
  breakpoints:
    sm: 480px
    md: 768px
    lg: 1024px
    xl: 1280px
  mobile-rules:
    - "Hide hero pipeline-card under 768px"
    - "Collapse two-column hero to single column"
    - "Hide nav links except primary CTA under 768px"
    - "Wrap trust-strip stats, justify-content: center"
    - "Section padding 4rem (mobile) → 6rem (desktop)"
  touch-targets: "Minimum 44px x 44px for any interactive element"

voice:
  philosophy: "Ogilvy-inspired. The hero line is borrowed structure from the Rolls-Royce 1959 ad ('At 60 miles an hour, the loudest noise…'). Specific over abstract. Numbers over adjectives. Tradesperson voice over agency voice."
  taglines:
    - "While you're on the tools, our system is finding your next client."
    - "Zero ad spend. Zero effort. Just a full pipeline."
    - "Four steps. One system. Clients while you sleep."
    - "Not promises. Proof."
    - "Everything you need. Nothing you don't."
  forbidden-words: ["delve", "tapestry", "underscore", "leverage", "revolutionary", "game-changing", "world-class", "navigate the landscape", "elevate", "unleash", "premier"]
  forbidden-chars: [", ", "-"]
  preferred-structures: ["tricolon (three beats)", "anaphora (repeat opener)", "chiasmus (reversal)", "specific number + comma + verb"]

agent-prompt-guide: |
  When generating UI for Conversion Forge:

  • Single accent: teal #4DD9D5, used surgically. One per surface.
  • Type stack: Inter only. Display 900, headlines 700, body 400.
  • Eyebrow + dot pattern opens every major section.
  • Sections alternate: white → teal-light → dark → white.
  • The signature card is the charcoal pipeline card with traffic-light dots and pulsing green status. If asked for a "system feels alive" moment, this is the move.
  • Numbers earn the page. Use Inter 900 at clamp(2.5rem, 5vw, 4rem) for any stat that matters.
  • Cards: 12px radius, white bg, hairline border, subtle shadow, hover-lift translateY(-4px).
  • Buttons: btn-primary (teal bg, charcoal text, 8px radius). btn-ghost for secondary. btn-whatsapp #25D366 for direct contact.
  • Voice: Ogilvy. Specific, tradesperson-grade, numbers-led. Never use em-dashes. Never use AI hype words.
  • Container width: 1140px max, 2rem padding.
  • Vertical rhythm: 6rem section padding desktop, 4rem mobile.

  Quick CSS variables to scaffold any new page:

  ```css
  :root {
    --teal: #4DD9D5; --teal-dark: #2BB8B4; --teal-mid: #E0FAF9;
    --charcoal: #1A1A1A; --body: #2D2D2D; --muted: #666;
    --white: #FFFFFF; --light: #F8F8F8; --hairline: #E8E8E8;
    --shadow: 0 4px 24px rgba(0,0,0,0.08);
    --shadow-lg: 0 12px 48px rgba(0,0,0,0.12);
    --radius: 12px; --font: 'Inter', sans-serif;
  }
  ```

provenance:
  source-url: "https://conversionforge.co.uk"
  extracted-from: "~/conversionforge-site/style.css + index.html"
  extracted-on: "2026-05-03"
  authored-by: "Tokelo Mogorosi (operator) · Claude Opus (agentic CLI)"
  governs: ["forge-portfolio", "conversionforge.co.uk", "CF Studio T1-T5 client demos", "Engine 6 character sheets when CF is the parent brand", "all CF-branded PDFs and pitch decks"]
  related-files: ["AGENTS.md (project build guide)", "CLAUDE.md (operator brain)", "humanizer rule (cardinal)"]
---

# Conversion Forge, Design System

> A plain-text design system document. Drop in any project where the Conversion Forge brand applies. Any AI agent that reads it should generate UI matching the live site at `conversionforge.co.uk`.

## Visual Theme & Atmosphere

**Light. Playful. Ogilvy-inspired.** The system is austere where most agency brands are loud and confident where most are corporate. White canvas does the heavy lifting. Charcoal type sets the weight. The teal accent is the spark, used once or twice per surface, never more.

Voltage comes from three places:
1. **The white-charcoal-teal three-tone system.** No fourth colour earns the page.
2. **The signature dark "live pipeline" card.** A charcoal panel sitting on a white section, with traffic-light dots and a pulsing status indicator. The brand promise is *the system runs while you sleep*, the pulsing dot is that promise made visible.
3. **The Ogilvy headline structure.** Specific over abstract, numbers over adjectives, tradesperson voice over agency voice.

## Why This System

The audience is UK small-business owners on the tools. Plumbers, electricians, builders, restaurant owners, barbers. They have seen agency websites. They distrust them. The Conversion Forge brand earns trust by *not* looking like an agency, minimal photography, no stock illustrations, no gradient overlays. The proof is in the numbers, the case studies, and the live pipeline card. Everything else gets cut.

## Component Inventory

See the YAML frontmatter for the canonical token set. Components covered:
- Buttons (primary, ghost, outline, whatsapp)
- Cards (light, dark, featured, pipeline)
- Eyebrow-with-dot section opener
- Trust strip (hero proof block)
- Logo bar (charcoal trust band)
- Testimonial (dark surface with teal-tinted quote mark)

## Layout Philosophy

Section padding stays at 6rem desktop, 4rem mobile. The grid is `repeat(auto-fit, minmax(280px, 1fr))` for cards. Container caps at 1140px. White breathing room is a feature.

## Typography

Inter does everything. Display weights are 900 with tight tracking. Body is 400 at 1.6 line-height. Eyebrows are 0.75-0.8rem at 0.12-0.15em tracking, all-caps, weight 600-700. There is no second font. There is no serif (except the Georgia quote-mark glyph in the testimonial, that is the only exception).

## Voice

Ogilvy. The hero line on the live site borrows structure from the Rolls-Royce 1959 ad ("At 60 miles an hour, the loudest noise…"). The structure is *specific physical truth + product claim*. Use it. Specific numbers, tradesperson voice, no agency hype.

The cardinal humanizer rule applies to every word that ships under this brand: no em-dashes, no AI hype vocabulary. The full prohibited list lives in the `forbidden-words` key of the frontmatter above. Never. The list is not negotiable.

## How to Use This File

1. Copy `DESIGN.md` to your project root.
2. Tell your AI agent: *"Use the design system in DESIGN.md to generate this page."*
3. Verify against live site at conversionforge.co.uk before shipping.

End of `DESIGN.md`.

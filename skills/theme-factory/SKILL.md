---
name: theme-factory
description: Toolkit for styling artifacts with an oOh!media brand theme. These artifacts can be slides, docs, reports, HTML landing pages, etc. There are 3 oOh! brand weight variants — Touch of Orange (default), Mid-weight Orange, and Majority Orange — that can be applied to any artifact.
license: Complete terms in LICENSE.txt
---

# Theme Factory Skill

This skill provides the three oOh!media brand theme weight variants, each calibrated for a different presentation context. All themes use the oOh! brand colour palette and Century Gothic typography exclusively.

## Purpose

To apply consistent, on-brand oOh!media styling to presentation slide decks and other artifacts. Each theme uses the same brand palette — what varies is the orange density and slide weight.

## Usage Instructions

To apply an oOh! brand theme to a slide deck or other artifact:

1. **Show the theme reference PDF**: Display the relevant PDF from the `themes/` directory to let the user see the brand implementation visually. Do not modify it — show it for reference only.
   - `themes/touch-of-orange.pdf` — white-dominant, orange accents
   - `themes/mid-weight-orange.pdf` — balanced orange panels + white
   - `themes/majority-orange.pdf` — bold orange throughout
2. **Default to Touch of Orange** if no preference is stated
3. **Ask for their choice** if the context isn't clear
4. **Apply the theme**: Once selected, apply the theme's colours, typography, and slide patterns throughout the deck

## Themes Available

### 1. Touch of Orange (default)

White-dominant with oOh! Orange used selectively for accents, stats, and headings.

**Best for:** Corporate reports, text-heavy decks, detailed proposals, investor materials.

**Key patterns:**
- Most slides: white background, orange accent elements and headings
- Cover slide: oOh! Orange background, white oOh! logo centred
- Key Statement slide: Moonlight Purple background, white CG Bold text
- Section breaker: Moonlight Purple background, large white "02." number 60pt, orange section title
- Stats/metrics: white background, large orange CG Bold numbers (48–72pt), Urban Grey dividers
- No full-orange panels (except cover) — orange appears only as accents and typography

### 2. Mid-weight Orange

Balanced approach with more orange panels alongside white content slides.

**Best for:** Standard brand presentations, pitches, proposals, agency decks.

**Key patterns:**
- Content slides: white background, orange subheadings CG Bold
- Hero statement slides: full-bleed photo + left-third orange overlay panel, white text on orange
- Key Statement slide: Moonlight Purple background, white CG Bold text (same as Touch)
- Section divider: full orange background, white "02. Section" CG Bold
- Dashboard slides: white background, orange metrics, Twilight Purple for secondary stat accents
- Stats: same large orange numbers pattern as Touch, but more orange panels throughout

### 3. Majority Orange

Maximum oOh! brand energy. Bold orange throughout.

**Best for:** Cover slides, section breakers, events, pull-up banners, bespoke/campaign presentations, high-impact moments.

**Key patterns:**
- Cover: orange background with oOh! circular crop shapes as decorative background elements
- Brand statement slides: full orange background, enormous white CG Regular (80–100pt), typographic only
- Statement on white: large orange CG Bold (~36pt) on white/near-white — maximum typographic punch
- Section dividers: orange background, large "02." in CG Bold
- Big numbers on white: same stats pattern, but bolder visual impact from surrounding high-energy slides
- Stats with Twilight Purple: large orange primary metric, Twilight Purple secondary panel

## Theme Details

Each theme is defined in the `themes/` directory with complete colour and typography specifications.

## Application Process

After a preferred theme is selected:
1. Read the corresponding theme file from the `themes/` directory
2. Apply the specified colours and fonts consistently throughout the deck
3. Ensure proper contrast using only the approved colour & type pairings
4. Maintain the theme's visual identity across all slides — commit fully or keep it consistent
5. Every slide must have the oOh! logo bottom-right

## Universal oOh! Brand Rules (all themes)

- **Font:** Century Gothic only — Regular (body, headings) and Bold (subheadings, stats, CTAs)
- **Cover slide:** Always oOh! Orange background
- **Key Statement slide:** Always Moonlight Purple background + white text
- **oOh! logo:** Always present, bottom-right, every slide
- **Photography:** Always full-bleed — no borders, no cropped frames
- **Sentence case:** All headings and titles — no ALL CAPS, no title case
- **No decorative lines under titles**

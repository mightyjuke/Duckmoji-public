---
name: Duckmoji Public Site
description: A cheerful sticker-sheet help desk built from sunny color, warm paper, bold type, and real Duckmoji characters.
colors:
  sun: "#ffcb21"
  sun-soft: "#ffe58b"
  cream: "#fff8df"
  paper: "#fffdf7"
  ink: "#3f2618"
  ink-soft: "#75513a"
  pink: "#ff7878"
  sky: "#7cc9ff"
  line: "rgba(63, 38, 24, 0.18)"
  paper-glass: "rgba(255, 255, 255, 0.55)"
typography:
  display:
    fontFamily: "Bricolage Grotesque, sans-serif"
    fontSize: "clamp(3.5rem, 7.8vw, 6rem)"
    fontWeight: 790
    lineHeight: 0.98
    letterSpacing: "-0.035em"
  headline:
    fontFamily: "Bricolage Grotesque, sans-serif"
    fontSize: "clamp(2.4rem, 5vw, 4.4rem)"
    fontWeight: 760
    lineHeight: 0.98
    letterSpacing: "-0.035em"
  title:
    fontFamily: "Bricolage Grotesque, sans-serif"
    fontSize: "clamp(1.45rem, 2.5vw, 2rem)"
    fontWeight: 740
    lineHeight: 1.08
    letterSpacing: "-0.035em"
  body:
    fontFamily: "Atkinson Hyperlegible, sans-serif"
    fontSize: "1.125rem"
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: "normal"
  label:
    fontFamily: "Bricolage Grotesque, sans-serif"
    fontSize: "1rem"
    fontWeight: 720
    lineHeight: 1.1
    letterSpacing: "normal"
rounded:
  nav: "10px"
  stamp: "12px"
  action: "13px"
  panel: "16px"
  hero-compact: "24px"
  contact: "30px"
  hero: "32px"
  full: "50%"
spacing:
  compact: "0.5rem"
  control: "0.75rem"
  inset: "1rem"
  cluster: "1.5rem"
  card: "2rem"
  section: "clamp(5rem, 10vw, 8.5rem)"
components:
  button-primary:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.paper}"
    typography: "{typography.label}"
    rounded: "{rounded.action}"
    padding: "0.75rem 1.15rem"
    height: "50px"
  button-secondary:
    backgroundColor: "{colors.paper-glass}"
    textColor: "{colors.ink}"
    typography: "{typography.label}"
    rounded: "{rounded.action}"
    padding: "0.75rem 1.15rem"
    height: "50px"
  topic-chip:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    typography: "{typography.label}"
    rounded: "{rounded.nav}"
    padding: "0.6rem 0.85rem"
  content-card:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    rounded: "{rounded.panel}"
    padding: "2rem"
  support-band:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.paper}"
    rounded: "{rounded.contact}"
    padding: "clamp(3rem, 7vw, 5.5rem)"
---

# Design System: Duckmoji Public Site

## Overview

**Creative North Star: "The Sticker-Sheet Help Desk"**

Duckmoji support should feel like opening a cheerful sticker sheet, not entering a corporate help center. The system pairs sunny fields, warm cream paper, thick chocolate ink, and expressive shipping Duckmoji artwork with direct editorial structure. It is playful on sight and trustworthy in use.

Personality comes from scale, color, gentle asymmetry, and real sticker cutouts—not from decorative clutter. Oversized display type makes each promise immediate; ruled lists and generous reading measures make practical and privacy content calm. The result is warm, legible, fast, and suitable for an App Store-facing support destination.

**Key Characteristics:**

- Bold sun-yellow fields against warm cream paper.
- Oversized, tightly set editorial headlines with highly legible body copy.
- Real Duckmoji cutouts used as expressive wayfinding and proof of character.
- Rounded, high-contrast panels balanced by crisp chocolate rules.
- Restrained lift, tactile states, and a single responsive mobile stack.

## Colors

The palette behaves like printed sticker stock: warm and high-contrast, with blush and sky accents adding small moments of expression.

### Primary

- **Sticker Sun** (`#ffcb21`): Owns the hero field, numbered proof marks, contact action, selection color, and other moments that should feel unmistakably Duckmoji.
- **Soft Sun** (`#ffe58b`): Provides the quieter yellow used for topic-hover feedback and supporting rings without competing with the primary field.

### Secondary

- **Blush Pop** (`#ff7878`): Adds a sparing warm accent to links, scroll affordances, and small calls for attention.
- **Sky Glint** (`#7cc9ff`): Appears as an atmospheric background wash; it cools the warm palette without becoming an interface accent.

### Neutral

- **Warm Cream** (`#fff8df`): The default page canvas and the dominant quiet surface.
- **Clean Paper** (`#fffdf7`): The lifted sheet and card surface, kept just brighter than the canvas.
- **Chocolate Ink** (`#3f2618`): The primary text, rule, button, and focus color; it replaces generic black throughout.
- **Soft Chocolate** (`#75513a`): Supports long-form and secondary copy while preserving warmth.
- **Chocolate Rule** (`rgba(63, 38, 24, 0.18)`): Separates steps, answers, ledger rows, and footer content without turning the page into a grid.
- **Paper Glass** (`rgba(255, 255, 255, 0.55)`): Creates the translucent secondary action on yellow.

### Named Rules

**The Sun Owns the Greeting Rule.** Use Sticker Sun for high-emotion brand moments and compact wayfinding marks; do not flood long reading surfaces with it.

**The No Generic Black Rule.** Chocolate Ink carries text, focus, rules, and dark surfaces so every high-contrast moment stays warm.

## Typography

**Display Font:** Bricolage Grotesque (with `sans-serif` fallback)

**Body Font:** Atkinson Hyperlegible (with `sans-serif` fallback)

**Character:** Bricolage Grotesque supplies chunky editorial confidence and friendly irregularity. Atkinson Hyperlegible keeps instructions, troubleshooting, and privacy copy effortless to scan.

### Hierarchy

- **Display** (weight `790`, `clamp(3.5rem, 7.8vw, 6rem)`, line-height `0.98`): Hero promises only; keep them short and balanced within roughly 10–12 characters per line.
- **Headline** (weight `760`, `clamp(2.4rem, 5vw, 4.4rem)`, line-height `0.98`): Major section openings and destination-card headlines.
- **Title** (weight `740`, `clamp(1.45rem, 2.5vw, 2rem)`, line-height `1.08`): Step titles, answer titles, and other compact content labels.
- **Body** (weight `400`, `1.125rem`, line-height `1.6`): Instructions and policy prose, generally constrained to 48–70 characters per line.
- **Label** (weight `720`, `1rem`, line-height `1.1`): Buttons, navigation, chips, stamps, and strong action text.

### Named Rules

**The Big Feeling, Clear Reading Rule.** Let Bricolage make the emotional promise; hand every explanation to Atkinson Hyperlegible.

**The Tight Headline Rule.** Display headings use compact line-height and negative tracking, while body copy stays open and uncompressed.

## Layout

The system uses a centered two-width frame: broad brand moments sit within `1120px`, while reading and navigation content stays within `960px`; both preserve a one-rem desktop gutter. Hero and contact fields are intentionally broad, while steps, FAQs, and privacy rows return to the narrower reading rail.

Spacing is generous and editorial. Major sections begin after a fluid `clamp(5rem, 10vw, 8.5rem)` interval; cards use two-rem interiors; compact controls cluster in half- to one-rem increments. Overlap is reserved for sheet-like navigation or destination cards that bridge a bold field and the paper canvas.

At the `760px` breakpoint, multi-column steps, answers, privacy rows, destination cards, and footer groups collapse to a single column. Outer gutters tighten to `0.625–0.75rem` per side, hero and contact radii reduce to `24px`, action rows wrap, and sticker artwork moves below the main copy while remaining visible in the first viewport.

**The One Reading Rail Rule.** Practical content aligns to the same `960px` rail even when adjacent brand moments use the broader frame.

## Elevation & Depth

Depth is a restrained hybrid of paper layering and sticker drop shadows. Large panels use a broad warm ambient shadow (`0 18px 48px rgba(106, 67, 16, 0.15)`), primary actions use a tighter contact shadow (`0 8px 24px rgba(63, 38, 24, 0.2)`), and sticker art receives soft drop shadows that preserve the cutout illusion. Ruled content remains flat.

### Shadow Vocabulary

- **Paper Lift** (`0 18px 48px rgba(106, 67, 16, 0.15)`): Broad hero, topic sheet, and destination-card elevation.
- **Action Lift** (`0 8px 24px rgba(63, 38, 24, 0.2)`): Default dark-button elevation.
- **Action Hover** (`0 12px 28px rgba(63, 38, 24, 0.28)`): Reinforces the two-pixel hover rise.
- **Sticker Lift** (`drop-shadow(0 18px 16px rgba(100, 59, 16, 0.2))`): Separates real sticker cutouts from the yellow field.

### Named Rules

**The Paper, Ink, Sticker Rule.** Use ambient shadow for sheets, firm shadow for actions, and drop shadow for cutout artwork; never apply card shadow to ruled reading rows.

## Shapes

Corners are friendly but disciplined. Navigation targets use `10px`, stamps use `12px`, buttons use `13px`, cards and floating sheets use `16px`, and broad brand fields use `30–32px`; the large fields tighten to `24px` on mobile. Circles are reserved for numbered steps, FAQ toggles, and atmospheric rings. One slight rotation is acceptable for stamp-like proof marks or stickers, not for core reading containers.

Borders are chocolate and functional: two-pixel rules begin sections or define stamps, while one-pixel translucent rules separate repeated content. Real sticker images keep their native cutout silhouette and must never be cropped into generic rectangles.

**The Scale With Importance Rule.** Larger radii belong to larger brand fields; compact controls stay tighter so the interface remains deliberate rather than bubbly.

## Components

### Buttons

- **Shape:** Compact tactile rectangle with gently rounded corners (`13px`) and a minimum height of `50px`.
- **Primary:** Chocolate Ink background, Clean Paper text, display-label typography, and `0.75rem 1.15rem` padding.
- **Hover / Focus:** Hover rises `2px` over `180ms` with a stronger action shadow. Keyboard focus uses a four-pixel Chocolate Ink outline with a four-pixel offset; on dark surfaces the outline changes to Warm Cream.
- **Secondary:** Paper Glass background, Chocolate Ink text, and a two-pixel translucent chocolate border; it stays flat at rest.
- **Contact Variant:** Sticker Sun background with Chocolate Ink text on the dark support band.

### Chips

- **Style:** Topic links use bold label type, `10px` corners, and `0.6rem 0.85rem` padding on a Clean Paper sheet.
- **State:** Hover fills with Soft Sun. Active page navigation uses a translucent Sticker Sun field rather than an underline.

### Cards / Containers

- **Corner Style:** `16px` for reading-adjacent cards and floating sheets; `30–32px` for brand fields.
- **Background:** Clean Paper for cards, Sticker Sun for hero fields, and Chocolate Ink for direct support moments.
- **Shadow Strategy:** Apply Paper Lift to self-contained sheets; keep ruled content flat.
- **Border:** Use one- or two-pixel chocolate rules when sequence and comparison matter more than enclosure.
- **Internal Padding:** Two rems for standard cards; broad brand fields use fluid `clamp()` padding.

### Inputs / Fields

The public site has no text inputs. Its only expandable field-like control is the native FAQ disclosure row.

- **Style:** FAQ summaries are full-width ruled rows with bold display type and a circular Sticker Sun plus/minus marker.
- **Focus:** Use the global four-pixel Chocolate Ink focus outline with a four-pixel offset.
- **State:** Opening the native disclosure changes the marker from plus to minus; no scripted animation is required.

### Navigation

The header pairs a `44px` rounded app icon with a bold wordmark, then places compact Support and Privacy links opposite it. Links use `10px` corners; hover and current-page states share a translucent yellow fill. On mobile, preserve the same row and tighten link padding rather than replacing it with a menu.

### Numbered Steps

Each step begins with a circular Sticker Sun marker (`2.6rem`) and tabular Bricolage numeral. Desktop steps share one ruled three-column strip; mobile steps stack and exchange vertical dividers for horizontal rules.

### Privacy Stamp

The effective-date stamp uses a two-pixel Chocolate Ink border, `12px` corners, bold display-label type, and a restrained `-1.5deg` rotation. It should feel hand-applied while remaining crisp and fully readable.

## Do's and Don'ts

### Do:

- **Do** lead major moments with Sticker Sun, Chocolate Ink, and a real Duckmoji cutout.
- **Do** keep instructions and policy copy on warm, quiet paper with generous reading measures.
- **Do** use thick display type for promises and Atkinson Hyperlegible for every explanatory passage.
- **Do** preserve visible four-pixel keyboard focus and reduced-motion behavior.
- **Do** collapse multi-column structures into one clear mobile stack at `760px`.

### Don't:

- **Don't** turn the public site into a generic blue-and-white corporate help center.
- **Don't** substitute stock illustration, emoji, or abstract mascot shapes for real Duckmoji artwork.
- **Don't** add shadow to every row; rules and tonal contrast carry most structure.
- **Don't** introduce tiny legal copy, dense card grids, hidden mobile navigation, or low-contrast controls.
- **Don't** crop sticker art into rectangular thumbnails or let decoration obscure practical content.

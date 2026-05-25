---

# Care, Made Simple — Scrolling Hero Section

A self-contained embeddable hero section for HealthHub. Features a two-column vertical scrolling treatment card marquee alongside a headline, bullet points, and a CTA button.

## Usage

Drop `healthhub-hero.html` directly into any page. No build step, no dependencies.

```html
<!-- paste the contents of scrolling-howcase.html wherever you need it -->
```

The Google Font is loaded via a `<link>` tag inside the file. If Plus Jakarta Sans is already loaded on the host page, remove the duplicate link at the top.

## Scoping

All styles are scoped under `.hh-pch` and all keyframe names are prefixed `hh-` — safe to embed alongside any existing CSS without conflicts.

## Customisation

Tokens live on `.hh-pch` — edit these to retheme:

| Token | Default | Purpose |
|---|---|---|
| `--accent` | `#fe491a` | Brand orange — CTA, bullets, dot |
| `--accent-dk` | `#d63a0f` | Hover state |
| `--ink` | `#2f354e` | Primary text |
| `--bg` | `#fff4ec` | Section background |
| `--canvas` | `#fffbf7` | Gradient start |

## CTA

The button is intentionally a dead link (`pointer-events: none`). Replace `href="#"` with the live URL when ready.

## Breakpoints

| | Layout |
|---|---|
| `< 768px` | Single column, marquee hidden |
| `≥ 768px` | Two column, marquee visible |
| `≥ 1024px` | Larger padding and card sizes |

---

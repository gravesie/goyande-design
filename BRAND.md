# Goyande brand definition

Machine-readable brand spec for Goyande. Every value here is the source of
truth, extracted from `Goyande-Brand-Guidelines-V0-3.html`. If you are an agent
styling something for Goyande, read this file first, then pull the matching
asset from `assets/` (SVG source) or `exports/` (PNG).

Status: Version 0-3, working draft. Subject to sign-off before the website and
LinkedIn build.

---

## What Goyande is

A practical agentic AI agency. It helps companies start with AI in a practical
way and get better automation and efficiency, by putting human-like judgement
into autonomous agents so processes get smarter, not just faster.

The name comes from two Apache words meaning **wise** and **human**. Those are
the two brand values, not just a translation:

- **Wise** — judgement over raw automation. Agents that reason about the work
  and make good calls, not just fast ones.
- **Human** — built around the people who use them. Plain language, humans kept
  in the loop, the final say stays with the client.

These values guide messaging and copy. They are not a strapline and not part of
the logo.

---

## Colour

| Token | Name | Hex | Use |
|---|---|---|---|
| `navy` | Deep Navy | `#102A4C` | Primary. Text, dark grounds. Carries the brand. |
| `teal` | Agent Teal | `#10B981` | The single accent. Growth, action, the live part. Use sparingly, on the one thing you want noticed. |
| `steel` | Steel | `#475569` | Secondary text. |
| `paper` | Paper | `#F8FAFC` | Off-white light background. |

Supporting UI tokens (from the guidelines stylesheet):

| Token | Hex | Use |
|---|---|---|
| `line` | `#E2E8F0` | Hairline borders, dividers. |
| `muted` | `#64748B` | Muted captions, fine print. |
| `muted-on-dark` | `#94A3B8` | Secondary text on navy. |
| `teal-light` | `#5EEAD4` | Teal label text on dark grounds. |
| `negative` | `#E11D48` | "Don't" / error markers only. Not a brand colour. |

**Accessibility.** Navy on white and white on navy both clear WCAG AA for body
text. Teal on white is fine for large text, graphic shapes and the mark — but
do not set small body text in teal on white.

---

## The brand gradient

A teal-to-navy gradient for high-impact moments only: website hero, LinkedIn
banner, social and link-preview cards, deck title/divider slides, app splash.
It is a **background surface only**.

| Variant | When | CSS |
|---|---|---|
| **Balanced** (default) | Any impact surface, including ones with text | `linear-gradient(135deg, #10B981 0%, #102A4C 68%)` |
| **Vivid** | Only where there is no text on the surface (app splash, divider) | `linear-gradient(135deg, #10B981 0%, #102A4C 96%)` |

Rules:

- Green sweeps in from the top-left corner. Text and the wordmark always sit
  over the navy side.
- The lotus on the gradient is **white at graded opacity**: outer petals 40%,
  inner petals 85%, centre petal 100%.
- Balanced is the default. Use Vivid only when there is no text on the surface.
- Use the gradient sparingly — it is the exception that makes the navy look
  richer, not a default background. Keep it off body text and one-colour print.
- **Never apply the gradient to the mark.** The mark on the gradient is flat
  white.

---

## Typography

One family does everything: **Manrope** (free, open-source, SIL Open Font
Licence). Geometric enough to feel technical, humanist enough to feel
approachable.

Font stack: `'Manrope', 'Segoe UI', system-ui, sans-serif`

| Weight | Value | Use |
|---|---|---|
| ExtraBold | 800 | Display |
| Bold | 700 | Headings |
| SemiBold | 600 | Wordmark, subheads |
| Medium | 500 | Emphasis |
| Regular | 400 | Body |

Body line-height ~1.55.

---

## Wordmark and logo

- The **wordmark** is "goyande", set **lowercase** in Manrope **SemiBold (600)**
  with tight tracking (about `-1px` letter-spacing).
- The **horizontal lockup is the default**. Use the **stacked** version where
  width is tight (square avatar, centred footer).
- The **mark** (lotus) may be used on its own once the brand is established — as
  app icon, favicon or social avatar.

**The mark.** A lotus of five petals: two faint outer petals, two solid mid
petals, one centre petal. In the colour version the centre petal is Agent Teal
`#10B981` and the rest are Deep Navy `#102A4C` (outer pair at ~50% opacity).

### Clear space and minimum size

- Keep clear space around the logo equal to the height of one petal cluster
  (roughly the height of the mark's centre petal). Nothing sits inside that
  margin. Do not place the logo on a busy photo without a solid holding shape.
- **Full lockup:** no smaller than **120px** wide on screen, or **28mm** in
  print.
- **Mark alone:** no smaller than **24px**. Below 24px, use the simplified
  favicon (three petals), which drops the two faint outer petals so it stays
  clean.

### Variants

- **Reversed** — for dark grounds (white petals, teal centre).
- **Mono navy** — one-colour print (all navy).
- **App icon** — navy rounded square with the white/teal lotus.
- **Favicon** — three petals only, for 16–24px.

---

## Straplines

- **Primary / brand line:** **"Go beyond automation."** Plays on the name
  (Goyande / go beyond). Short, active, sits under the logo and on the hero.
- **Secondary / explainer:** **"Practical AI. Automated efficiency."** Tells a
  sceptical operations buyer what they get, in plain terms. For the LinkedIn
  tagline, email footer, meta description, bios.

---

## Tone of voice

- **Plain English.** Say what the agent does and what the client gets. No
  jargon walls.
- **Practical over futuristic.** Lead with the outcome (hours saved, errors
  cut), not the technology.
- **Calm and certain.** The audience is wary of AI hype; understatement builds
  more trust than big claims.
- **Specific.** Name the process, the tool, the result. Avoid vague
  "transformation" language.
- **Human.** Sound like a sharp colleague, not a chatbot.

---

## Misuse — what not to do

- Don't stretch or distort the mark.
- Don't recolour it (the navy/teal split is fixed).
- Don't rotate it.
- Don't put the navy mark on the gradient — on the gradient the mark is flat
  white.
- Don't add drop shadows or outlines.
- Don't crowd it.
- Don't rebuild the wordmark in a different typeface.

---

## Asset index

SVG sources live in `assets/`; rendered PNGs in `exports/` (same base names).

| File (`assets/…`) | Use |
|---|---|
| `goyande-lockup-horizontal.svg` | Default logo, most places |
| `goyande-lockup-stacked.svg` | Square or narrow spaces |
| `goyande-mark.svg` | Mark only, colour |
| `goyande-mark-reversed.svg` | Mark on dark grounds |
| `goyande-mark-mono-navy.svg` | One-colour print |
| `goyande-mark-white.svg` | White knockout — use on the gradient |
| `goyande-icon.svg` | App icon / social avatar |
| `goyande-favicon.svg` | Favicon, 16–24px |
| `goyande-gradient-hero.svg` | Gradient hero surface |
| `goyande-logo-pggi-pair.svg`, `goyande-pggi-cobrand.svg` | PGGI co-branding |
| `goyande-proof-*.svg`, `goyande-card-*.svg` | Supporting proof/feature graphics |
| `goyande-slide-*.svg` | Deck headers/footers |
| `goyande-banner-linkedin.svg`, `goyande-social-card.svg`, `goyande-businesscard-back.svg` | Applied templates |

All sources are vector SVG and scale losslessly. PNG exports exist for places
that reject SVG (LinkedIn etc.). For final production, the lockup wordmark text
should be converted to outlines so files don't depend on Manrope being
installed.

The structured token values are also available as `brand-tokens.json`.

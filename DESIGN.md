# Design rules for matthewbairstow.dev

Every page follows these rules. If a change breaks one, change the rule here first or don't make the change.

## Why these rules exist

AI-generated ("vibe coded") sites converge on the same look: purple/blue gradients, Inter or system fonts,
dark mode with glowing accents, every block in a rounded card that lifts on hover, pill-shaped tags,
fade-in animations, coloured left borders, emoji icons, a centred "Hi, I'm ..." hero, and copy full of
"passionate", "robust", "leverage", "seamless". This site avoids all of them on purpose.

## Feel

One word: **printed**. Like a well-set CV on good paper, not an app dashboard.

## Colour

| Token      | Light     | Dark      | Use                                   |
|------------|-----------|-----------|---------------------------------------|
| `--paper`  | `#f5f2eb` | `#171614` | Page background                       |
| `--ink`    | `#1c1b19` | `#ebe7de` | Body text, headings                   |
| `--ink-2`  | `#5a564e` | `#a39e93` | Dates, secondary text                 |
| `--rule`   | `#d6cfc0` | `#34312c` | Hairline dividers                     |
| `--accent` | `#9b2c1d` | `#e0806a` | Links and the active nav item only    |

One accent colour. No gradients, no glows, no shadows.

## Type

- **Source Serif 4** for headings and body. Body 1.0625rem / 1.6.
- **IBM Plex Mono** for small metadata only: dates, nav, section labels, "Built with" lines.
- Heading scale: h1 2.75rem, h2 is a small mono label, h3 1.25rem. Nothing else.

## Layout

- Single left-aligned column, max 44rem of text. Nothing centred except nothing.
- Corner radius: 0. Containers: none. Group with whitespace and 1px rules.
- Experience, education and projects use a two-column CV row: date on the left (10rem), content on the right.
  Below 640px the date sits above the content.
- Skills are plain comma-separated lists, never pill tags.

## Motion

None. Link underlines change colour on hover; that's it.

## Copy

- First person, plain, specific. Say what was done and with what.
- Banned words: passionate, robust, leverage, seamless, empower, unlock, journey, cutting-edge, delve.
- No em-dashes in page copy. No emoji.

## Technical baseline

- Every page: unique `<title>`, meta description, Open Graph tags, favicon, skip link.
- Headings in order (one h1 per page, no skipped levels).
- Visible keyboard focus. Text contrast at least 4.5:1 in both themes.
- No JavaScript.

## Privacy

Email (`general@matthewbairstow.dev`) only. No home address, no phone number.

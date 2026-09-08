# Orivet Israel Design System

## Direction

**The Living Family Record** combines a bright, continuous veterinary health record with the intimacy of a contemporary family album. The page should feel human first and clinically credible throughout. It rejects dark genetic-tech spectacle, repeated card grids, decorative gradients, and templated section kickers.

## Palette

- Daylight white `#FFFFFF`: primary page field.
- Ink purple `#21152F`: primary text and footer.
- Orivet purple `#542080`: authority, selected states, and one major story field.
- Deep purple `#33134F`: expert profile field.
- Accessible orange `#C94612`: actions, annotations, emphasis, and icons.
- Pale peach `#FFF0E7`: consultation field.
- Pale lilac `#F2EAFA`: restrained informational support.
- Hairline `#E9E2EB`: continuous section and comparison rules.

Orange is functional and editorial, not a background for long reading. Purple carries large fields sparingly. Most of the page remains white and naturally lit.

## Typography

- Display: **Secular One**, used for large Hebrew promises and decisive section headings.
- Body and UI: **Noto Sans Hebrew**, weights 400–900.
- Display tracking is tight but never below `-0.04em`. Body copy uses generous line height and a readable measure.
- Headings carry their own hierarchy; do not add eyebrow labels above them.

## Composition

- Prefer continuous rules, flowing editorial sequences, and large photography over repeated rounded cards. Every section introduction uses a centered heading with its supporting copy directly beneath it; detailed lists and form fields retain reading-appropriate alignment. The animal portrait chapter uses a uniform square portrait grid.
- The opening pairs a decisive promise with overlapping candid dog and cat portraits.
- Product choice appears early as three detailed kit cards and later as a full three-column comparison.
- On mobile, layouts become a single clear reading path; product comparison stacks and a persistent consultation action appears at the bottom.
- Rounded corners are reserved for actions, photography, the video feature, and the consultation form rather than applied to every content group.

## Photography

Use close animal portraits to make dogs and cats feel individually seen, supplied packshots for product credibility, and the `resources/ofer/` collection to show Dr. Ofer Zadok in real clinical context. Mix young and adult animals and keep species representation balanced. Product images may float cleanly without rectangular photo frames. Do not present synthetic report data or imagery as a real customer result; label any visual approximation clearly.

## Interaction

- Primary action: orange pill button leading to package choice or consultation.
- Secondary action: white button with a purple defined edge.
- Product species filtering uses a compact segmented control.
- Mobile navigation uses an accessible disclosure button with Escape and link-close behavior.
- Consultation fields compose a prefilled WhatsApp message, show an in-page handoff status, and never send without the visitor confirming in WhatsApp.
- FAQ uses native disclosure behavior.
- Keyboard focus is a visible warm-orange outline.
- Respect reduced-motion preferences; motion is limited to small state transitions.

## Accessibility

Maintain WCAG AA contrast for body text and controls, semantic RTL order, descriptive alternative text, 44px minimum touch targets, clear focus states, and mobile body text near 16px or larger. Medical limitations must remain visible and understandable.

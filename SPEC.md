# Brand Studio decisions

This is the durable agreement between the learner and agent. Keep it concise and update it only with agreed choices or actual evidence. `Not chosen yet` is a valid status. Persona cards are hypotheses unless supported by real research.

[LEARNING.md](LEARNING.md) holds the short, reviewable record of learner explanations and help received. Keep the brand decisions and implementation evidence here; link rather than duplicate them.

## Current stage

- Stage: BRAND-001 implemented and merged into `main` (learner reported).
- Current feature: `BRAND-001` — first branded storefront and live style guide.
- Status: Storefront, style guide, explorations and persuasion interactions implemented; learner reports 10/10 Playwright tests passing and mobile appearance satisfactory.
- Next small step: Complete outstanding learner reflection fields in LEARNING.md; verify manual keyboard behavior and reference links if required.

## Product boundary

The product is the same white T-shirt throughout the comparison. The baseline offers a size selector and temporary demo bag. No real orders, payment, accounts, or persistence. Keep product facts stable between directions; do not add unsupported claims about materials, manufacturing, sustainability, fit, delivery, scarcity, reviews, or sales.

## Audience hypotheses

The primary need guides the page. Give the secondary card one contrasting need to check that same page; keep both cards brief.

| Tiny card                             | Primary audience           | Secondary audience          |
| ------------------------------------- | -------------------------- | --------------------------- |
| Person in a concrete situation        | Yoga and wellness practice | Hiking and travel lifestyle |
| Goal or meaning they seek             | Not chosen yet             | Not chosen yet              |
| Concern before choosing               | Not chosen yet             | Not chosen yet              |
| What the page should help them decide | Not chosen yet             | Not chosen yet              |
| Evidence or assumption                | Assumption; not validated  | Assumption; not validated   |

## Early brand brief

| Decision                                 | Agreement                                                      |
| ---------------------------------------- | -------------------------------------------------------------- |
| Brand name                               | ånde                                                           |
| One-sentence promise                     | For slow mornings and open horizons.                           |
| Primary archetype: the brand's character | Explorer with Everyman influences                              |
| Three voice traits                       | Soft, poetic, carefree (working interpretation of agreed mood) |
| One example line in this voice           | A little yoga, a little sunshine, and nowhere you need to be.  |
| Learner's predicted audience effect      | Not chosen yet                                                 |

## Visual decision

Compare two small hero previews before building the whole page. Hold the product, headline, supporting copy, and action identical. Use specific real design references and annotate visual choices, intended effect, and risk.

A simple original SVG wordmark is enough. Show small-size and one-color presentations; they may use the same asset when it works.

| Item                                              | Agreement or evidence                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| ------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Shared headline / support / action                | Headline and supporting line above; CTA working proposal: Shop the tee (must match in both previews)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| Modernist preview, reference, and annotations     | Implemented in `public/explorations/modernist.html`; reference URL and visual presentation require verification                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| Postmodernist preview, reference, and annotations | Implemented in `public/explorations/postmodernist.html`; reference URL and visual presentation require verification                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| Chosen direction and reason                       | Refined postmodernist: layered botanical/forest imagery, without torn-paper edges or handwritten category labels. Learner's exact reasoning: “I chose postmodernism over modernism for my brand because Ande is about being carefree, spontaneous, and free-spirited, and it is geared to women who enjoy yoga, adventure, the outdoors, and travel. Postmodernism felt more fitting than modernism because design-wise, it is all over the place and doesn't play by the rules of clean lines or minimalism. The collage-like aesthetic and fullness of postmodern design is what makes sense for a yoga brand that leans into the Explorer archetype.” |
| Original SVG logo                                 | Lowercase ånde serif wordmark only, no separate symbol; SVG implemented at `public/assets/ande-wordmark.svg`                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| Monochrome and small-size variants                | Displayed in `public/styleguide.html`; visual review pending                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| Logo review at actual use size                    | Not checked yet                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| Shared palette, typography, spacing, and assets   | Misty forest greens, soft ivory, delicate elegant serif; shared in `public/styles.css` and used across storefront, style guide, and Yoga to Travel                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |

## Ethical persuasion

Choose two applications that help the visitor make a voluntary, informed decision. Record their real implementation and mechanism rather than a principle name alone. Required size selection or validation alone does not establish consistency. Do not invent social proof, scarcity, authority, or product facts.

| Principle                | Actual copy or interaction                                                                                                                             | Visitor benefit / factual support                                                                                |
| ------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------- |
| Reciprocity              | Free `Yoga to Travel` tab with three practical outfit/packing ideas; explicitly says no purchase necessary                                             | Visitors get useful suggestions without signup or purchase; no unsupported product claims                        |
| Commitment & Consistency | Optional `Slow Morning` or `Open Horizons` buttons on `public/yoga-to-travel.html` reveal a corresponding styling suggestion and optional product link | Visitors make a voluntary preference choice and see relevant guidance; no data collection or purchase obligation |

## BRAND-001 — first branded storefront and live style guide

**Scope:** turn the working neutral storefront into the chosen brand's first coherent page. Keep the existing size selector and demo bag usable. Do not add checkout or all future features.

Keep when:

- The learner has chosen the audience hypotheses, brief, visual direction, and logo; the page visibly expresses those choices.
- Two annotated hero directions compare modernist/postmodernist thinking with the same content and real source links.
- The selected SVG logo works at small size and in one color; the presentations may share one asset.
- The storefront and live style guide share CSS variables, typography, components, and assets; they do not drift into separate identities.
- Two ethical persuasion applications are visible and their claims are supportable.
- Prepared checks pass, the agent has reviewed the slice and discussed one actual check, and the learner has reported a browser impression plus keyboard/mobile observations.
- The issue, branch, commit, and PR explain this feature in the learner's repository; agreed decisions and actual evidence are saved here. The learner has approved keeping and merging the change, and the merge into `main` is verified. Publishing is a separate choice.

## Evidence

Write a short result and link only evidence that exists. A passing browser check is evidence for its assertions, not customer research or proof of full accessibility.

| Spec ID   | Files                                                                                                                            | Issue / PR                                                                         | Actual checks and observations                                                             |
| --------- | -------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------ |
| BRAND-001 | `public/index.html`, `public/styleguide.html`, `public/yoga-to-travel.html`, `public/explorations/*.html`, shared CSS and assets | [Issue #1](https://github.com/cs0759/IS-117_Brand-Studio/issues/1), feature branch | Learner reports 10/10 Playwright tests passing; mobile layout looks good; automated keyboard test passed; manual Tab navigation not confirmed; PR merged per learner |

## Later

No follow-up is selected. After keeping `BRAND-001`, choose one next cycle: perhaps a brand story, a supported fit guide, or richer demo-bag behavior. Agree its scope and add one new spec ID at that time.

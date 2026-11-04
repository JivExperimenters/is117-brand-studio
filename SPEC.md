# Brand Studio decisions

This is the durable agreement between the learner and agent. Keep it concise and update it only with agreed choices or actual evidence. `Not chosen yet` is a valid status. Persona cards are hypotheses unless supported by real research.

[LEARNING.md](LEARNING.md) holds the short, reviewable record of learner explanations and help received. Keep the brand decisions and implementation evidence here; link rather than duplicate them.

## Current stage

- Stage: Baseline tried; BRAND-001 scope agreed; brand decisions pending.
- Current feature: `BRAND-001` — first branded storefront and live style guide.
- Status: Scope agreed. Issue [#1](https://github.com/JivExperimenters/is117-brand-studio/issues/1) exists; its body still needs the agreed scope. Local branch: `feature/brand-001`.
- Next small decision: Choose one contrasting secondary need to check against the same page.

## Product boundary

The product is the same white T-shirt throughout the comparison. The baseline offers a size selector and temporary demo bag. No real orders, payment, accounts, or persistence. Keep product facts stable between directions; do not add unsupported claims about materials, manufacturing, sustainability, fit, delivery, scarcity, reviews, or sales.

## Audience hypotheses

The primary need guides the page. Give the secondary card one contrasting need to check that same page; keep both cards brief.

| Tiny card                             | Primary audience                                                          | Secondary audience                                                                       |
| ------------------------------------- | ------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- |
| Person in a concrete situation        | Someone on a day when they only have classes | Not chosen yet; learner mentioned liking a fancy coat or stylized flannel |
| Goal or meaning they seek             | Wants comfort and simplicity | Not chosen yet |
| Concern before choosing               | Does not want heavy-feeling clothes | Not chosen yet |
| What the page should help them decide | Whether a plain white tee suits the simple look they want for a class-only day (AI proposal accepted) | Not chosen yet |
| Evidence or assumption                | Learner's initial hypothesis; not validated; product comfort/weight not established | Early idea only; the contrasting need and page decision remain to be clarified |

## Early brand brief

| Decision                                 | Agreement                                                       |
| ---------------------------------------- | --------------------------------------------------------------- |
| Brand name                               | ComfyCloth |
| One-sentence promise                     | Not chosen yet                                                  |
| Primary archetype: the brand's character | Not chosen yet                                                  |
| Three voice traits                       | Calm, easy, softly confident; low-stress mood, not overworked   |
| One example line in this voice           | Not chosen yet                                                  |
| Learner's predicted audience effect      | Not chosen yet |

## Visual decision

Compare two small hero previews before building the whole page. Hold the product, headline, supporting copy, and action identical. Use specific real design references and annotate visual choices, intended effect, and risk.

A simple original SVG wordmark is enough. Show small-size and one-color presentations; they may use the same asset when it works.

| Item                                              | Agreement or evidence |
| ------------------------------------------------- | --------------------- |
| Shared headline / support / action                | Not chosen yet        |
| Modernist preview, reference, and annotations     | Not chosen yet        |
| Postmodernist preview, reference, and annotations | Not chosen yet        |
| Chosen direction and reason                       | Not chosen yet        |
| Original SVG logo                                 | Not chosen yet        |
| Monochrome and small-size variants                | Not chosen yet        |
| Logo review at actual use size                    | Not checked yet       |
| Shared palette, typography, spacing, and assets   | Not chosen yet        |

## Ethical persuasion

Choose two applications that help the visitor make a voluntary, informed decision. Record their real implementation and mechanism rather than a principle name alone. Required size selection or validation alone does not establish consistency. Do not invent social proof, scarcity, authority, or product facts.

| Principle      | Actual copy or interaction | Visitor benefit / factual support |
| -------------- | -------------------------- | --------------------------------- |
| Not chosen yet | Not chosen yet             | Not chosen yet                    |
| Not chosen yet | Not chosen yet             | Not chosen yet                    |

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

| Spec ID   | Files                                      | Issue / PR | Actual checks and observations |
| --------- | ------------------------------------------ | ---------- | ------------------------------ |
| BRAND-001 | No feature files changed yet; setup only   | [#1](https://github.com/JivExperimenters/is117-brand-studio/issues/1) | Baseline: `npm test` 7/7 and `npm run test:e2e` 10/10 passed; explicit HTML/CSS lint passed. `npm run check` stopped at formatting (32 files flagged); `npm run lint` did not match its quoted HTML glob on Windows. Learner reports size L was added and the bag showed one item, quantity 1. |

## Later

No follow-up is selected. After keeping `BRAND-001`, choose one next cycle: perhaps a brand story, a supported fit guide, or richer demo-bag behavior. Agree its scope and add one new spec ID at that time.

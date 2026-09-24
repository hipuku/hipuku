# hipuku

Software engineer in Sydney, working on design systems, testing and the tools around them, in
React and TypeScript with accessibility built in. Open to roles in design systems, design
engineering and frontend.

Case studies, essays and motion snippets are at [hipuku.dev](https://www.hipuku.dev).

## Systems

- **[haus](https://github.com/hipuku/haus)**: a token-first React design system. W3C DTCG tokens
  in OKLCH, 20 accessible components and five packages on npm.
  [Storybook](https://haus.hipuku.dev) · [case study](https://www.hipuku.dev/work/haus)
- **[drift](https://github.com/hipuku/drift)**: crawls a website and reports the design values it
  ships (colour, type, spacing, radius, shadow), deduplicated with CIEDE2000 and attributed to the
  pages that use them. Playwright, BullMQ, WebSockets. The public demo replays one captured audit;
  the tool runs locally against any site. Its HTTP API is covered by
  [drift-tests](https://github.com/hipuku/drift-tests), a black-box BDD suite that drives a real
  crawl queue in CI. [Demo](https://drift.hipuku.dev) ·
  [case study](https://www.hipuku.dev/work/drift)
- **[core](https://github.com/hipuku/core)**: a team decision log. Architecture decision records
  with a permission-gated lifecycle, two audit trails, and citations to GitHub line ranges that
  report when the cited code changes. Next.js, Postgres, Drizzle.
  [Demo](https://core.hipuku.dev) · [case study](https://www.hipuku.dev/work/core)
- **[vault](https://github.com/hipuku/vault)**: an offline Mac app for colours, fonts, palettes and
  type scales. Electron, React, SQLite, with a typed IPC boundary.
  [Download](https://github.com/hipuku/vault/releases/latest) ·
  [case study](https://www.hipuku.dev/work/vault)
- **[kern](https://github.com/hipuku/kern)**: the component library and tokens behind the tools
  below, distributed as TypeScript source at a pinned git tag.
  [Storybook](https://kern.hipuku.dev) · [case study](https://www.hipuku.dev/work/kern)

## Tools

Free, in the browser, no sign-up, MIT licensed.

- **[tokenise](https://tokenise.hipuku.dev)**: converts design tokens between DTCG, Figma
  variables, Tokens Studio and Tailwind v4, and reports every token each format changes or drops.
- **[specifi](https://specifi.hipuku.dev)**: CSS specificity, token by token, on a from-scratch
  Selectors Level 4 parser.
- **[hexicon](https://hexicon.hipuku.dev)**: names any hex by CIEDE2000, maps a palette in OKLCH
  and draws a WCAG contrast matrix for every pair.
- **[gray-scott](https://gray-scott.hipuku.dev)**: real-time reaction-diffusion, simulated in a
  Web Worker.

## On npm

[haus-tokens](https://www.npmjs.com/package/haus-tokens) ·
[haus-components](https://www.npmjs.com/package/haus-components) ·
[haus-colour-utils](https://www.npmjs.com/package/haus-colour-utils) ·
[haus-colour-names](https://www.npmjs.com/package/haus-colour-names) ·
[haus-style-probe](https://www.npmjs.com/package/haus-style-probe)

## Work

- **Pendula**, 2023 to 2025. Software engineer on a workflow-automation and messaging platform:
  features in the React and TypeScript front end, a Cucumber BDD regression suite, a K6 canary
  and load-testing suite, and the GitHub Actions workflows that run them.
  [Case study](https://www.hipuku.dev/work/pendula)
- **three55 studio**, co-founder. Custom websites, and maple, the studio's app for its clients'
  brand assets (Next.js, Postgres with row-level security). The source is private; a read-only
  [demo](https://maple-demo.hipuku.dev) is open to anyone.

Design and development work has won Indigo Awards Gold for Website Design (2024, 2026) and Mobile
App (2025).

## Writing

- [The Language We Never Agreed On](https://www.hipuku.dev/writing/the-language-we-never-agreed-on)
- [The Default Is Not a Design Decision](https://www.hipuku.dev/writing/the-default-is-not-a-design-decision)
- [Motion Deserves Better Than a Prop](https://www.hipuku.dev/writing/motion-deserves-better-than-a-prop)

## Contact

[hipuku.dev@gmail.com](mailto:hipuku.dev@gmail.com) · [hipuku.dev](https://www.hipuku.dev) ·
[Figma](https://www.figma.com/@hipuku)

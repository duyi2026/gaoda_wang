# Owner Handoff: Gundam Future Hangar Showcase

## Role

You are the owner subagent for the first substantive artifact. Create only the allowed product artifacts listed below. Do not write testing reports, gate reports, release decisions, or unrelated project files.

## Allowed Artifacts

- `index.html`
- Project-local visual assets under `assets/`

## Goal

Build a mobile-first, high-end, technology-heavy, future-war single-page showcase website named `高达未来机库`.

## Required Content

Models must appear exactly as page content:

- 沙扎比
- 牛高达
- Z高达
- ZZ高达
- 独角兽高达
- 报丧女妖高达
- 元祖高达

Accessory/tool content must include:

- 各种水贴
- 展示架
- 补件/扩展装备, with unknown facts kept as `to-be-confirmed`
- 新手七件套装

## Design Direction

- Mobile-first static single-page HTML.
- Dark metal base, cold white/cyan HUD lighting, with limited warning red or metallic gold accents.
- First viewport must clearly show `高达未来机库` and a hangar/war-readiness visual signal.
- Avoid official logos, official posters, or unauthorized official imagery.
- Use original project-local visuals. If bitmap generation is unavailable, create original code-native/SVG assets that read as futuristic hangar/mecha silhouettes without copying official product art.
- Cards must use border radius no larger than `8px`.
- Avoid a generic marketing template. The page should feel like a premium model war-room inventory interface.
- Mobile layout should be immersive vertical browsing; desktop can expand into an organized grid.
- Do not use a purple-dominant, beige, brown/orange, or one-note palette.

## CTA Requirements

Include strong CTA actions using these exact Chinese phrases:

- `咨询战备配置`
- `查看模型阵列`
- `获取入门套装`

All real contact, purchase, price, inventory, brand ownership, and asset licensing details must remain `to-be-confirmed`.

## Technical Requirements

- Static HTML only unless absolutely necessary; no package manager setup.
- Keep all CSS and minimal JavaScript inside `index.html` unless a local asset file is clearly better.
- Must work by opening `index.html` directly.
- No backend, payment, cart, analytics, or real form submission.
- Use accessible semantic structure where practical.
- Avoid external network dependencies for runtime rendering.

## Completion Criteria

- `index.html` exists and renders without external runtime dependencies.
- `assets/` contains at least one original visual asset referenced by the page.
- All required model, accessory, tool, and CTA text appears in the page.
- Unknown project facts are written as `to-be-confirmed`, not guessed.

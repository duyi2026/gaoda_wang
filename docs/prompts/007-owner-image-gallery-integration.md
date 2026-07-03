# Owner Handoff: Image Gallery Integration

## Role

You are the owner subagent for this substantive product/media update. Create only the allowed artifact changes listed below. Do not write testing reports, gate reports, release decisions, or unrelated project files.

## Allowed Artifacts

- `index.html`
- Project-local image assets under `assets/`

## Source Image Folder

Use images from:

- `D:\ai_xiangmu\gaoda_tupian`

Do not move or delete source images. Copy usable images into project-local `assets/` paths before referencing them from `index.html`.

## Current Source Inventory

Model source images:

- `沙扎比`: 3 images
- `牛高达`: 10 images
- `Z高达`: 3 images
- `ZZ高达`: 2 images
- `独角兽高达`: 3 images
- `强袭自由高达`: 8 images
- `元祖高达`: 3 images
- `命运高达`: 5 images

Equipment/tool source images:

- `模型工具_01_新手七件套.png`
- `模型工具_02_水口钳与打磨板.png`
- `模型工具_03_模型记号笔.png`
- `模型工具_04_水口钳.png`

## Required Changes

1. Adapt images from `D:\ai_xiangmu\gaoda_tupian` into the model array.
2. Every Gundam model card must expose at least 4 project-local images:
   - `沙扎比`
   - `牛高达`
   - `Z高达`
   - `ZZ高达`
   - `独角兽高达`
   - `强袭自由高达`
   - `元祖高达`
   - `命运高达`
3. For source folders/models with fewer than 4 images, generate the missing images with image2 based on the existing images:
   - `沙扎比`: generate 1
   - `Z高达`: generate 1
   - `ZZ高达`: generate 2
   - `元祖高达`: generate 1
   - `独角兽高达`: generate 1
4. Adapt available tool images into the equipment/tools area.
5. If any equipment/tool category lacks a source image, generate or add project-local visual assets so the equipment/tools area has image-backed presentation for:
   - `各种水贴`
   - `展示架`
   - `补件/扩展装备`
   - `新手七件套装`

## Image Generation Rules

- Use image2/GPT-Image-2 style generation only for missing images.
- Generated images must be project-local and saved under `assets/`.
- When using generated images, keep them visually consistent with the existing high-end, technology-heavy, future-war page style.
- Do not use official logos, official posters, copyrighted official product images from the web, real contact details, prices, inventory promises, or purchase claims.
- Unknown product facts must remain `to-be-confirmed`.
- If image2 tooling is unavailable, produce the best project-local adaptation from available source images and clearly preserve missing/generated status in the page as `to-be-confirmed`; do not invent facts.

## Page Integration Requirements

- Preserve the existing static single-page HTML approach; no package manager or runtime external dependencies.
- Preserve current model names and order:
  - `沙扎比`
  - `牛高达`
  - `Z高达`
  - `ZZ高达`
  - `独角兽高达`
  - `强袭自由高达`
  - `元祖高达`
  - `命运高达`
- Preserve existing CTA text:
  - `咨询战备配置`
  - `查看模型阵列`
  - `获取入门套装`
- Keep the page mobile-first and high-end/future-war in tone.
- Avoid horizontal overflow at mobile widths.
- All referenced image paths in `index.html` must be relative project-local paths.

## Completion Criteria

- Each of the 8 model cards references at least 4 project-local images.
- The equipment/tools section references project-local images for water decals, display stand, expansion equipment, and starter tool kit.
- No `D:\...` absolute image references remain in `index.html`.
- No new external runtime URLs are required by `index.html`.
- `报丧女妖高达` remains absent.

# SportNear

A portrait-first sports discovery prototype inspired by the three supplied visual references: cinematic sports photography, grey translucent glass, emerald controls and bold native system typography.

## Open

Extract the entire ZIP and open index.html. Keep the assets folder beside it. Core navigation and filtering work offline without installation, CDN libraries or font downloads. A local HTTP server can also serve this folder.

## Features

- Home → Training or Play & Clubs → six sports → results → details.
- Manual selection of all seven UAE emirates; Dubai is the default.
- Area, age, skill and per-session AED budget filters; ascending/descending prices; clear and empty states.
- Saved shortlist stored locally when browser storage is available.
- Hash URLs support browser history and shareable filter state.
- Keyboard controls, visible focus, labelled native selects, reduced motion and transparency fallbacks.

All 252 listings, schedules, venue names, locations and prices are fictional examples. Photographs are generated illustrations and do not depict the listed providers. No bookings, real contacts or live availability are provided.

## Typography and layout

Apple devices use the native San Francisco system font through -apple-system. Windows uses Segoe UI Variable/Segoe UI. No Apple font files are bundled. The app stays in a narrow vertical frame on desktop and fills a phone viewport.

## Edit

CSS, data and JavaScript are embedded in index.html. The script begins with EMIRATES, SPORTS, AREAS, SEEDS and LISTINGS. Update those definitions to change sample content. Photographic assets are local PNG sheets positioned with CSS.

## Verification

Browser checks covered Home/sport/detail navigation, budget filtering and an empty state, clearing filters, saving/removing a session, persistence after reload, and the 390px portrait layout without horizontal overflow. No console errors were observed during these checks. JavaScript syntax was checked separately.

See DESIGN-PLAN.md for reference mapping and ASSET-NOTES.txt for image generation prompts.

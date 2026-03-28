# GFPorders

Static menu + ordering page for Gluten For Punishment.

Live data source
- Public CSV export of `GFP_MENU_PUBLIC` → Menu tab: `https://docs.google.com/spreadsheets/d/1MWFZPYVNo-rZjZAIAmy4oIHTqetraa6LVh9ixvHHUfE/export?format=csv&gid=449861824`

Deploy (Cloudflare Pages)
- Framework: None / static
- Build command: none
- Output directory: `/`
- Allow external fetch to the CSV URL above

CTAs
- Order Now → `https://forms.gle/kGhKH1TPKtXiFV4M9`
- Instagram → `https://www.instagram.com/Gluten4Punishment.co`

Site root
- `index.html` only; no build step required.

Notes
- Public sheet must stay “Anyone with link: Viewer” and Published to web (Menu tab) so the menu loads.
- Menu shows only active items from `Menu Active` and uses the highest number found in each price string.

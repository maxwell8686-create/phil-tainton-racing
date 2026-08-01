# Phil Tainton Racing Redesign

## Project

- Client/site: Phil Tainton Racing, https://www.ptr.com.au/
- Local workspace: `C:\Users\maxwe\OneDrive\Desktop\website`
- Target repo supplied by user: `maxwell8686-create/phil-tainton-racing.git`
- Deployment target: Vercel

## Current Environment Notes

- `git` is not currently available in this shell.
- `node` and `npm` are not currently available in this shell.
- First pass is a static Vercel-compatible site using `index.html`, `styles.css`, and local assets.

## Source Content Captured

- PTR prepares and tunes performance motorcycles for road racing, motocross, drag racing, and speedway.
- Existing site states PTR has more than 30 years of experience.
- Racing history includes Steve Martin, Grant Hodson, factory Suzuki GSX-R750 superbikes, and riders including Peter Goddard, Troy Baylis, Shawn Giles, Craig Coxhell, Josh Waters, Wayne Maxwell, and Troy Herfoss.
- Contact:
  - Factory 1/45 Gilbert Park Drive, Knoxfield VIC 3180
  - Phone: (03) 9764 2621
  - Fax: (03) 9764 9196
  - Email: info@ptr.com.au

## Initial Design Direction

- Visual tone: performance workshop, race heritage, premium but direct.
- Homepage should immediately show PTR as the first-viewport signal.
- Avoid generic marketing-card layout; prioritize a strong hero, service clarity, project credibility, and direct contact actions.
- Color direction: high-contrast black/white with PTR red and warm neutral workshop backgrounds.

## Local Assets

- `assets/ptr-logo.png`
- `assets/ptr-white.png`
- `assets/clients.png`
- `assets/workshop-bike.jpg`
- `assets/race-bike.jpg`

## First-Pass Files

- `index.html`: static homepage
- `styles.css`: responsive styling
- `CODEX.md`: working project memory

## Next Adjustments

- Connect real internal links once service/project pages are created.
- Decide whether to keep this as a static site or move to Next.js once Node is installed.
- Add GitHub/Vercel setup once `git` and a deploy path are available.
- Review copy with PTR for accuracy before production launch.

## 2026-08-01 Racing Feel Pass

- Added a red racing discipline ticker below the hero.
- Darkened the header and trust band to feel more like a race workshop/pit lane.
- Added angled red buttons, speed-line overlays, sharper project links, and track-inspired CSS texture.
- Updated homepage copy toward race preparation, lap speed, throttle response, and hard performance numbers.

## 2026-08-01 Sitemap Pull

- Downloaded `https://www.ptr.com.au/sitemap.xml` to `ptr-sitemap.xml`.
- Parsed sitemap to `ptr-sitemap-pages.csv`.
- Total URLs found: 194.
- Core rebuild candidates:
  - `/about/`
  - `/services/`
  - `/road-bike-services/`
  - `/offroad-bike-services/`
  - `/dyno-tuning/`
  - `/motorcycle-dyno-tuning/`
  - `/motorbike-tuning/`
  - `/cylinder-heads/`
  - `/engine-packages/`
  - `/machine-shop/`
  - `/suspension-packages/`
  - `/chassis/`
  - `/gearboxes/`
  - `/crankshaft-modification/`
  - `/contact/`
- Project rebuild candidates:
  - `/gsx-s1000-katana/`
  - `/bandit-1250/`
  - `/gsx-1300r-1650cc-hayabusa-290hp/`
  - `/gsx-1400-1620cc-160hp/`
- Shop/product URLs exist in the sitemap but should be handled separately because static pages will not replace WooCommerce cart/checkout behavior without ecommerce implementation.

## 2026-08-01 Social/Project Image Pass

- Tried to pull public images directly from the PTR Facebook page and individual Facebook photo URLs.
- Facebook returned only shell/static assets to automated fetches, so original post images were not directly available.
- Added usable public PTR Katana project imagery from a Phil Tainton Racing feature article as a temporary social/project image source.
- New local files:
  - `assets/social/katana-action.jpg`
  - `assets/social/katana-detail.jpg`
  - `assets/social/katana-front.jpg`
  - `assets/social/katana-road.jpg`
  - `assets/social/katana-side.jpg`
- Added a homepage "From the feed" gallery and updated the project feature image.

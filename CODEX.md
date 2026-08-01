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

## 2026-08-01 Facebook Details Block

- Added a homepage Facebook details/social proof section based on the user's Facebook page screenshot.
- Included:
  - 94% recommend from 13 reviews
  - `$$$` pricing indicator
  - Knoxfield address
  - Phone, email, and Facebook message link
- Used existing local workshop/project imagery beside the details block.

## 2026-08-01 Dyno Facebook Post

- Added a homepage dyno post highlight from the user's Facebook screenshot.
- Visible post details:
  - Phil Tainton Racing
  - April 20, 2024
  - Facebook photo URL: `https://www.facebook.com/photo/?fbid=923237098892032&set=pcb.923237125558696`
- Facebook did not expose the original full-size photo file through HTTP fetch or window capture, so the section currently uses existing local workshop imagery and links to the source post.
- Swap target when available: replace the image in `.dyno-post-media` with a downloaded local dyno-room photo.

## 2026-08-01 Facebook Photo Highlights

- Added a homepage Facebook photo highlights section based on the user's screenshots of the PTR Facebook photos area.
- Highlight subjects:
  - SuperFlow dyno room / April 2024
  - Machine shop precision components
  - Suzuki race bike setup / February 2019
  - Black bike workshop prep / April 2018
- Added a "See all Facebook photos" link to `https://www.facebook.com/PhilTaintonRacing/photos`.
- Current images use closest local workshop/project assets until exact Facebook originals are manually saved locally.

## 2026-08-01 Saved Facebook Suzuki Team Photo

- Captured the visible Firefox Facebook photo window and cropped the central image.
- Saved as `assets/facebook/suzuki-team-2017.png`.
- Source shown in screenshot:
  - Facebook photo ID: `794835960669114`
  - Date: April 30, 2017
  - Caption text visible: "with Phil Tainton and Brodie Waters."
- Added the saved image to the heritage section and Facebook photo highlights section.

## 2026-08-01 Services Page Content

- Pulled service images from `https://www.ptr.com.au/services/`.
- Saved local service assets:
  - `assets/services/dyno-tuning.jpg`
  - `assets/services/cylinder-head.jpg`
  - `assets/services/suspension.jpg`
  - `assets/services/chassis.jpg`
  - `assets/services/machine-shop.jpg`
  - `assets/services/gearbox.jpg`
- Expanded homepage services grid from four text-only cards to six image-backed service cards.
- Added service content for dyno tuning, cylinder head, suspension, chassis, machine shop, and gearboxes.
- Updated chassis, machine shop, and gearbox/crankshaft copy from the lower section of the PTR services page screenshot.

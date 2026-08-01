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

## 2026-08-01 Front Page Hero Image

- Captured the visible Facebook image from the Firefox window.
- Source shown in screenshot:
  - Suzuki Motorcycles Australia
  - Date: October 4, 2017
  - Facebook photo ID: `10155093061287865`
  - Post references Josh Waters and ASBK at Phillip Island.
- Saved cleaned hero image with Facebook UI icons removed:
  - `assets/facebook/suzuki-action-hero-clean.png`
- Updated homepage hero background to use `assets/facebook/suzuki-action-hero-clean.png`.

## 2026-08-01 Facebook Cover Banner

- Redesigned the old PTR Facebook banner to better match the website style.
- Direction:
  - Black/purple racing visual system
  - Road performance and off road performance split
  - Central PTR branding
  - Clean service list
  - Bottom band with `PHIL TAINTON RACING | www.ptr.com.au`
- Saved final banner asset:
  - `assets/facebook/ptr-facebook-cover-2026.png`
- Updated the original red accents to purple/magenta to better match the website and PTR logo energy.

## 2026-08-01 Site Purple Theme Pass

- Applied the Facebook cover banner style across the website.
- Reworked the global accent palette from red racing accents to purple/magenta racing accents.
- Updated hero glow, speed lines, button gradients, ticker, image shadows, section slashes, service card accents, project link markers, contact band, and gallery accents.
- Kept Facebook and Instagram icon colors as their official brand colors.

## 2026-08-01 Racing Logo Upgrade

- Generated a wider motorsport-style PTR logo to match the Facebook cover banner.
- Saved as `assets/ptr-logo-racing.png`.
- Replaced header and footer logo images with the upgraded racing logo.
- Adjusted header/footer logo sizing for the wider asset.
- Enlarged the footer logo presentation and added a purple racing footer treatment so it does not appear like a tiny logo on a plain black block.

## 2026-08-01 Black Logo Background

- Created a black-background version of the upgraded PTR racing logo to match the Facebook cover banner.
- Saved as `assets/ptr-logo-racing-black.png`.
- Updated header and footer to use the black-background logo.

## 2026-08-01 Technical SEO Pass

- Added `robots.txt` with sitemap reference.
- Added production `sitemap.xml` for the current static homepage.
- Added homepage canonical URL: `https://www.ptr.com.au/`.
- Added SEO title and meta description targeting motorcycle dyno tuning, race bike preparation, and Melbourne/Knoxfield service relevance.
- Added Open Graph and Twitter card metadata using the hero image.
- Added JSON-LD structured data:
  - Local business / repair business profile
  - Website
  - WebPage
  - ItemList of services
  - Service schema for dyno tuning, cylinder heads, suspension, chassis, machine shop, and gearbox/crankshaft modifications
- Improved image alt text with more descriptive motorcycle tuning, dyno, race preparation, and PTR service keywords.

## 2026-08-01 Shop Category SEO Links

- Pulled live PTR shop category links from `https://www.ptr.com.au/shop/`.
- Added a homepage "Shop parts + categories" section linking to major shop categories:
  - ECU reflashing
  - Suspension / chassis setup
  - BMW S1000RR
  - Suzuki GSX-R1000
  - Suzuki GSX-R1000R
  - Suzuki Hayabusa
  - Suzuki Katana
  - Suzuki GSX-R600 / GSX-R750
  - Suzuki RM-Z / RMX
  - KTM 250 SXF
  - Marketplace / new and used parts
- Added JSON-LD ItemList schema for key shop categories to improve topical relevance around motorcycle parts, model categories, and performance services.

## 2026-08-01 Purple Palette Lift

- Lifted the site purple palette one step brighter/richer to better match the banner/logo energy.
- Updated core theme variables and small highlight text accents.

## 2026-08-01 Dyno Section Image Swap

- Replaced the dyno post feature image with `assets/services/dyno-tuning.jpg` so the visual matches the dyno-room copy.
- Updated the matching Facebook highlight image reference and alt text.

## 2026-08-01 Logo Oval Border

- Added a white oval border directly to `assets/ptr-logo-racing-black.png` so the main PTR logo has a stronger racing badge feel.

## 2026-08-01 Larger Logo Oval

- Rebuilt `assets/ptr-logo-racing-black.png` from the clean black logo with a larger canvas and wider oval so the border captures the purple splash.

## 2026-08-01 Wider Logo Band And Swish

- Widened the PTR logo oval band and added a purple racing swish accent inside the badge border.

## 2026-08-01 Remove Logo Swish

- Removed the purple swish accent from `assets/ptr-logo-racing-black.png` while keeping the wider white oval badge border.

## 2026-08-01 Oval Logo Badge

- Rebuilt `assets/ptr-logo-racing-black.png` as a true oval badge with transparent outside corners.
- Removed the internal rectangular backing so the PTR logo reads as an oval shape instead of a boxed image.

## 2026-08-01 Typography Upgrade

- Added Google Fonts `Oswald` and `Rajdhani` for a sharper race-shop feel.
- Applied display typography to headings, navigation, buttons, labels, service numbers, project links, and gallery captions.

## 2026-08-01 Centered Typography

- Centered the hero copy/actions and reusable section headings so the updated fonts feel more balanced and intentional.

## 2026-08-01 Center Footer Content

- Centered the footer logo, footer text, and social icons so they align with the oval PTR badge.

## 2026-08-01 Center Main Logo Mark

- Rebuilt `assets/ptr-logo-racing-black.png` so the PTR mark and purple splash sit more centrally inside the oval badge.

## 2026-08-01 Logo Mark Fine Tune

- Nudged the PTR mark slightly further right and down within the oval badge for better visual centering.

## 2026-08-01 Logo Mark Right Nudge

- Nudged the PTR mark a little further right inside the oval badge.

## 2026-08-01 Reference Style Logo Badge

- Updated `assets/ptr-logo-racing-black.png` toward the reference badge style with a thicker white oval band, black interior, centered PTR mark, and purple splash retained.

## 2026-08-01 Smaller Hero Heading

- Reduced the front-page `Phil Tainton Racing` hero heading size and tightened its max width for better balance.

# DEVLOG: The Therapy Couch International

## 27 Oct 2026
**Done**
- Set up folders: `references/`, `assets/`, `previews/`, `scrape/`.
- Scraped all 10 pages of thetherapycouchinternational.com (Wix). Raw HTML and text dump in `scrape/`.
- Organised all copy into `assets/current-site-content.md` (client wording unedited, plus sitemap and issues list).
- Downloaded 17 site images at full size into `assets/current-site/`, renamed by content after viewing each one.

- Extracted the old site's colours and fonts (in `assets/current-site-content.md`). Not being kept.
- Created client `CLAUDE.md` with the new palette and gradient sampled from `references/Color palette/`.

- Built first homepage design in `site/` (plain HTML/CSS/JS): hero (couch photo + gradient wash), philosophy line, what we help with, 4 therapies, how it works, about Rod & Natalie, testimonial, FAQ, contact + form, footer, mobile sticky booking bar.
- Compressed background images into `site/images/` (couch and chair, 1200 and 2400 wide).
- Rendered and checked `previews/home-375.png`, `home-768.png`, `home-1440.png`. Fixed hero card overlap at 768 and FAQ line spacing.

- Added 4 custom line icons to the Therapies cards (spiral, speech bubbles, orbits, summit flag).
- Moved page copy back to Rod's own wording (cleaned up only). Hero text centred.
- Added a scroll-drawn journey line to "How it works": wavy line connects the 3 steps (horizontal on desktop, vertical on mobile), each circle fills in as the line reaches it. Respects reduced motion. Frames saved as `previews/home-journey-animation-*.png`.

- Headings switched to Glowgirl (self-hosted woff2). Fixed knock-on wraps: "Four ways" back to one line, FAQ heading scaled in its column.

- Nav is now fixed: glass over the hero, turns solid cream with green text once scrolled past it. Anchor links land clear of it. Frames in `previews/home-nav-scrolled-*.png`.

- Nav logo now reads "The Therapy Couch" with "INTERNATIONAL" in small spaced caps underneath.
- Nav fades out (1.2s) when the booking section fills the lower 60% of the screen, fades back in on scroll up. Frame in `previews/home-nav-faded-at-booking-1440.png`.

**To do**
- Body font still Jost (placeholder). Confirm or supply.
- Check the Glowgirl licence covers web embedding for this client.
- Contact form has no handler yet (`action="#"`).
- About photo is a low-res casual selfie, needs a proper photo of Rod and Natalie.
- Only testimonial is from a trainee. Ask Rod for real client reviews.
- Confirm "30+ years" (old site also says 25), and which palette (Aurora vs Salmverse).
- No logo yet, header uses a text wordmark.
- Confirm the job scope: concept redesign for Alex's video, or a full rebuild?
- Collect references.
- Ask Rod for a logo, better photos, real client testimonials, and whether Natalie is still active in the practice.

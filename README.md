# Neurodiversity Assessment: Online Neurodivergent Screening

Single-page, SEO-optimised site targeting the keyword **online neurodivergent screening**.

## Files
| File | Purpose |
|---|---|
| `index.html` | Luxury, animated landing page with a 1,500+ word semantic article, SVG illustrations, FAQ and JSON-LD schema |
| `robots.txt` | Allows all crawlers and points to the sitemap |
| `sitemap.xml` | Lists the home page for search engines |
| `README.md` | These notes |

## Before you upload
1. Replace `https://neurodiversityassessment.com/` with your real domain in `index.html` (canonical, og:url, JSON-LD), `robots.txt` and `sitemap.xml`.
2. Upload all files to the site root so `robots.txt` and `sitemap.xml` load at `/robots.txt` and `/sitemap.xml`.
3. Submit the sitemap in Google Search Console and request indexing.

## SEO structure
- One H1, 11 H2 sections, several H3 sub-sections
- Keyword in title, meta description, H1, first paragraph, headings and conclusion
- Canonical tag, Open Graph and Twitter tags, Article and FAQPage schema
- Descriptive `aria-label` text on every SVG illustration

## Link rule
The only external link is in the **second paragraph** of the article. No other external links, phone numbers or call buttons exist anywhere on the page.

## Design
- Palette: midnight ink `#120E1F`, plum `#2A1F4A`, champagne gold `#D9B66B`, pearl `#F7F2E8`, soft teal `#5FB7AE`
- Fonts: Cormorant Garamond (headings) and Manrope (body) via Google Fonts, with system fallbacks
- Animation: drifting aurora glow, drawing constellation, gold button sheen and gentle scroll reveals (all disabled for visitors who prefer reduced motion)

## Images
Illustrations are inline SVG, so they load instantly and need no extra files. To use photos instead, swap an `<svg>` inside a `<figure>` for an `<img>` with descriptive alt text.

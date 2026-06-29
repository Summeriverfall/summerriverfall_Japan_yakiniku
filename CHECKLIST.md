# mooi Project QA Checklist

## Structure
- [x] Root `/index.html` — Language selection landing page
- [x] `/en/index.html` — English version
- [x] `/jp/index.html` — Japanese version
- [x] `/cn/index.html` — Chinese (Simplified) version

## Navigation & Links
- [x] Logo in header links to `/index.html` (language selection) on all pages
- [x] Language switcher (中文 / EN / 日本語) works across all 3 pages
- [x] Nav links scroll to correct sections (Lash, Facial, Nail, Foot Care, Visit)
- [x] All internal anchor links (#lash, #facial, #nail, #foot, #visit) functional

## Content Accuracy
- [x] All service names match the menu provided by owner
- [x] All prices correct: Eyelash (¥13,200 / ¥19,800 / ¥22,000 / ¥15,400), Facial (¥16,500 / ¥22,000 / ¥27,500), Nail (¥16,500/¥11,000 / ¥26,400/¥19,800), Foot (¥13,200 / ¥17,600)
- [x] Japanese descriptions match owner's text in JP version
- [x] English translations accurate
- [x] Chinese translations accurate

## Visual & Media
- [x] Hero section has rotating image carousel (4 slides)
- [x] Environment carousel below menu section with prev/next + dots
- [x] All 9 photos (2 interior + 7 service) used
- [x] Photos load from `assets/images/` with lazy loading
- [x] Language landing page has background photo

## Buttons & CTAs
- [x] WhatsApp floating button visible on all 3 language pages
- [x] WhatsApp link: `https://wa.me/81663745181`
- [x] Back-to-top button appears after scrolling 600px
- [x] "Book Your Visit" button scrolls to Visit section

## Contact & Location
- [x] Address: 〒531-0072 大阪府大阪市北区豊崎3丁目20-9 三栄ビル 6F
- [x] Hours: 10:00 – 21:30, 7 days a week
- [x] Phone: +81 6-6374-5181 (clickable tel: link)
- [x] Google Maps embed points to correct Umeda store location
- [x] "Open in Google Maps" link uses proper search query

## Responsive Design
- [x] Desktop (>900px): 3-column service grid, full gallery
- [x] Tablet (640-900px): single-column services, stacked layout
- [x] Mobile (<640px): hamburger nav, adjusted spacing, smaller buttons
- [x] Images scale correctly on all breakpoints
- [x] Touch targets adequate on mobile

## Performance
- [x] Images use `loading="lazy"`
- [x] Google Fonts use `preconnect`
- [x] CSS is single file, no render-blocking issues
- [x] JS is minimal, no frameworks

## SEO & Meta
- [x] All pages have unique `<title>`
- [x] All pages have `<meta name="description">`
- [x] Proper `lang` attribute on `<html>` for each language
- [x] Semantic HTML5 elements used (header, nav, main, section, article, footer)

## Browser Compatibility
- [ ] Test on Chrome
- [ ] Test on Safari
- [ ] Test on Firefox
- [ ] Test on Mobile Safari (iPhone)
- [ ] Test on Mobile Chrome (Android)

## Pre-Launch
- [ ] Verify WhatsApp number is correct and active
- [ ] Verify Google Maps pin shows correct location
- [ ] Verify all photos render correctly on production server
- [ ] Check page load speed (Lighthouse)
- [ ] Test all links in all 3 language versions
- [ ] Confirm business hours with owner
- [ ] Confirm all prices with owner
- [ ] SSL certificate installed on domain

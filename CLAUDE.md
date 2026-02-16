# MJGrowth Project Context

## Overview
Marketing/advisory website for **Mollie Jane Garza** - a first-generation Latina American sales & business development executive with 20 years experience driving growth for Fortune 100 brands, startups, and everything in between.

**Focus areas:** Sports + AI + Commerce Growth Advisory

**Context:** Neil is building this site for Mollie (a friend) to help potential clients understand who she is and what she offers.

**Live site:** https://mjgrowthconsulting.com (also: mjgrowth.vercel.app)

---

## Tech Stack
- Single-page HTML/CSS/JS
- Hosted on Vercel
- Git version controlled

---

## Key Files
- `index.html` - Main (and only) page
- `carousel-1.jpg` through `carousel-9.jpg` - Hero carousel images
- `mollie_headshot_2.jpg` - Profile photo
- `mollie_panel.jpeg` - Speaking/panel photo
- `logo-dark.png` / `logo-light.png` - Brand logos

---

## Development History

### Session: Jan 23, 2026
- Initial site setup
- Meta tags configured for Mollie Jane Garza
- Basic structure created

### Session: Feb 1-2, 2026
- Added carousel images 7, 8, 9
- Form improvements:
  - AJAX submission with inline confirmation
  - Live character counter on textarea
  - Minimum 20 character requirement
  - New dropdown options
- Carousel fixes:
  - Slowed to 7 second intervals
  - Fixed interval stacking bug
  - Image positioning adjustments
- Replaced emoji favicon with logo
- Made copyright year dynamic
- Elegant success state after form submission

---

## Design Notes
- Clean, minimal aesthetic
- Fonts: Inter (body), Playfair Display (headings)
- Color scheme: Black, white, grays (off-white, gray-100 through gray-800)

---

## Current State
- Site is live and functional
- Form submits successfully
- Carousel working with 9 images

---

## TODO / Future Ideas
- (Add items here as they come up)

---

## Session Notes
Use this section to capture decisions, context, or notes during work sessions.

### Feb 3, 2026
- Reviewed project structure and git history to rebuild context
- Created this CLAUDE.md file for future session continuity
- Updated headshot from `mollie_headshot.jpeg` to `mollie_headshot_2.jpg`
- Deployed to Vercel via CLI
- Confirmed custom domain `mjgrowthconsulting.com` is working

### Feb 16, 2026
- Removed NBA All-Star Weekend and Brand Safety Summit from schedule
- Made schedule **dynamic** - auto-highlights next upcoming event based on current date
  - Past events get checkmark ✓
  - Next upcoming event gets NEXT badge + black styling
  - Uses `data-date` attributes on schedule cards
- **Performance optimizations** (Lighthouse audit):
  - Compressed carousel images: 12.7MB → 3MB (76% reduction)
  - Made Google Fonts load async (non-blocking)
  - Performance score: 66 → 74
- Learned: Lighthouse CLI for auditing, `git revert` vs `git reset --hard`

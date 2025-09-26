# 📑 Changelog

All notable changes to this project will be documented in this file.

---

## [1.1.0] - 2025-09-26
### Added
- Completed `index.html` homepage with hero section, welcome message, and gallery
- Built `enquiry.html` page with volunteer/donation form and styled “mini-hero” banner
- Added form validation (required fields, email type) and thank-you alert on submission
- Secondary button style for alternative actions (e.g., “View Programs”)

### Styling & Layout
- Expanded `style.css` with:
  - `.mini-hero` banner section styling
  - Form styling for inputs, select dropdown, and textarea
  - `.btn.secondary` for alternate call-to-actions
- Improved spacing using CSS custom properties (`--space-1` to `--space-4`)
- Added accessibility styles (`:focus-visible`) and reduced-motion support

### Content Updates
- Updated **Home page** with stronger CTA (“Donate / Volunteer”)
- Improved **Programs page**: added “How We Measure Impact” section with KPIs and partner link
- Contact page updated with clearer branch addresses and optional Pretoria map embed
- All pages now include South African context in text and imagery

### Responsive Design
- Confirmed responsive layouts across all 5 pages:
  - Hero height adjusts at 980px / 680px breakpoints
  - Grids collapse to single column on mobile
  - Split layouts stack vertically for smaller screens

### Fixes & Final Polish
- Unified headers and footers across all pages
- Corrected inconsistent image `alt` attributes
- Removed duplicate inline width/height on images (relying on CSS instead)
- Consolidated inline CSS into `style.css` for maintainability

---

## [1.0.0] - 2025-09-04
### Added
- Initial commit: Added `index.html` and base folder structure
- Added `css/style.css` with reset and base styles
- Created `README.md` with project overview

### Added Pages
- `about.html` with mission, vision, and values section
- `programs.html` with 3-column layout for programs
- `contact.html` with Google Maps embed

### Styling & Layout
- Responsive navigation bar
- Hero section with background image overlay
- Card grid layout and hover effects

### Content Updates
- Expanded *Our Values* section with Care, Community, and Integrity
- Added South African context (nutrition, education, child protection) to Programs
- Footer with copyright

### Responsive Design
- Breakpoints for mobile and tablet
- Grid adjusts to 2-column on tablets, 1-column on phones
- Added accessibility: alt text for images

### Fixes & Final Polish
- Corrected navigation typo on `enquiry.html` link
- Resized images to fit columns consistently
- Updated README with installation and deployment instructions

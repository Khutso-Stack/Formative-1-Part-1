# 📑 Changelog

All notable changes to this project will be documented in this file.

---

## [1.2.0] - 2025-09-26
### Added
- **Homepage gallery** section using local images (`Kids-post-image.jpg`, `meal.jpg`, `classroom.jpg`, `school.jpg`, `shelter.jpg`) with captions.
- **Responsive screenshots** (mobile & desktop) added under `/docs/screenshots/` and referenced in README.
- `aria-current="page"` on active nav links for better accessibility feedback.

### Changed
- **Mobile navigation UX:** nav is non-sticky ≤768px, row+wrap layout, smaller paddings for more content space.
- **Hero overlay tuning** for better legibility and image visibility (lighter gradient).
- Standardised image usage across pages: removed inline `width/height`, rely on CSS `object-fit: cover`; where applicable, added `srcset/sizes` or `image-set`.

### Fixed
- Broken gallery images due to filename/path mismatches (case-sensitive on GitHub Pages).
- Conflicting mobile nav rules at the same breakpoint (removed column stack rule).
- Duplicate/weak `alt` text—improved descriptive alts on gallery and hero images.
- Ensured embedded Google Maps are fully responsive inside `.map-wrap`.

### Docs
- README updated with **live site link**, structured **Responsive Screenshots** tables, and clearer run/deploy instructions.
- Noted breakpoints (980px, 900px, 768px, 680px) and accessibility features (`:focus-visible`, reduced motion).



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

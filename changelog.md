# Changelog

This changelog documents the development milestones and improvements made to the Kids Haven website project. Each version reflects a meaningful update aligned with project goals and academic requirements.

## [1.0.0] - 2025-11-10
- Created initial HTML structure for homepage
- Added navigation bar and footer
- Linked CSS stylesheet and basic layout

## [1.1.0] - 2025-11-12
- Developed Contact Us and Enquiry pages
- Implemented form fields with placeholders and required attributes
- Styled forms for consistency and readability

## [1.2.0] - 2025-11-14
- Embedded YouTube video on About Us page
- Added testimonial section with real quotes
- Improved emotional resonance through layout and messaging

## [1.3.0] - 2025-11-15
- Upgraded Team section using image cards and grid layout
- Enhanced responsiveness using CSS Grid and Flexbox
- Improved accessibility with alt text and semantic tags

## [1.4.0] - 2025-11-16
- All inline styles were moved to kidshaven.css for consistency.
- Shared styles include fonts, colors, layout, buttons, and responsive rules.
- CSS file includes default styles for body, headings, links, and containers.
-Team section styled with cards
-Form and social links styled
-Service blocks styled with consistent layout
-Form fields and buttons styled

## [1.5.0] 2025-11-19
 Responsive Images with Download-on-Click
Type: Frontend Enhancement
Description:
- Implemented responsive image styling using CSS (max-width: 100%, height: auto) to ensure images scale properly across devices.
- Added hover effects for interactivity (transform: scale(1.05)).
- Integrated JavaScript logic to automatically wrap all <img> elements in <a> tags with the download attribute, enabling users to download images by clicking on them.
- Ensured compatibility with existing HTML structure without requiring manual changes to each image.
-Quotes styled with custom fonts and spacing
- Implemented JavaScript form validation for Contact and Enquiry pages
- Added meta tags and keyword-rich headings for SEO
- Finalized README with full project overview and setup instructions
- Created Harvard-style references in `REFERENCES.md`
## [19 November 2025]– Contact & Enquiry Form Upgrade

### Updated
- Replaced broken form actions (`submit_form.php` and `submit_enquiry.php`) with JavaScript-based handling to prevent "Page Not Available" errors.
- Added `id="contactForm"` to the Contact Us form for proper JavaScript targeting.
- Implemented client-side validation for required fields (name, email, subject, message).
- Displayed a success message (`#responseMessage`) upon valid submission.
- Styled the Send buttons for responsiveness and hover effects using CSS.
- Ensured mobile-friendly layout and accessibility improvements.

### Fixed
- Send buttons now work without needing a backend server.
- Removed outdated `action` and `method` attributes from both forms.

### Notes
- These changes improve user experience and allow form submissions to be simulated without server-side processing.
- Future enhancement: connect forms to Formspree or Google Forms for real email delivery.


# Niyantri Cafe Website

A cozy, chocolate-inspired website for Niyantri Cafe in Hyderabad, Telangana, India. This project includes three static pages built with Tailwind CSS classes directly in HTML:

- index.html (Home)
- about.html (About Us)
- contact.html (Contact)

Notes and decisions:
- Phase 2 builds a warm, cozy vibe with chocolate accents. Tailwind utility classes drive all styling (no external CSS files).
- All pages use semantic HTML5 structure (header, nav, main/section, footer).
- Navigation features a mobile hamburger menu with a playful animation and accessible ARIA attributes.
- Hero section uses a full-viewport background image with a semi-transparent overlay for contrast. Content is centered and uses line breaks to emphasize key words with brighter color.
- Testimonials section showcases 3 cards with a 5-star rating, quotes, and author details.
- Footer is a 3-column, dark-themed area with brand info, quick links, and a newsletter signup.
- All interactive elements include Tailwind-based transitions (transition-all duration-300 etc.).
- Page load fade-in: The body starts with opacity-0 and fades in on load.
- Scroll reveal: Sections fade in and slide up as they enter the viewport via a small IntersectionObserver.
- Placeholders for images use the provided placeholder syntax: src='https://pixabay.com/get/g4e6c9ed6672f76adcd1a0c3194708f67a3443caae7aa764e4d7f030c7bdfcbe48b5ece6c93eabb01d3fe92787ebeaa5f9f4772e224ee185ee7552ee1146af9d0_640.jpg'.

Contextual details:
- Current date: Sunday, September 21, 2025 (Hyderabad, Telangana, India). This is reflected in the content where appropriate.
- Copyright year: 2025

How to view:
- Open the three HTML files in a browser. For a complete experience, ensure Tailwind CSS is available in the environment (via CDN or build system) as the templates rely on Tailwind classes.

If you’d like, I can adjust text, color tones, or swap in a different menu structure. Would you like me to tweak any copy or add a dedicated Menu page next?
# AppName Landing Page
 
A simple responsive landing page built with HTML and Tailwind CSS (via CDN).
## Features
- Sticky navigation bar with smooth-scrolling anchor links
- Responsive hamburger menu for mobile (slides open/closed with animation)
- Hero section with call-to-action buttons
- Features section showing 3 cards (Lightning Fast, Secure, Analytics)
- Fade-in animations:
  - Hero text fades in when the page loads
  - Feature cards fade in one by one as you scroll down to them

## Responsive Breakpoints
 
This project uses Tailwind's default breakpoints:
## File Structure
index.html   # everything (HTML + Tailwind classes + CSS + JS) in one file
README.md    # this file
 
## Notes
 
- Tailwind is loaded from the CDN (`cdn.tailwindcss.com`), so an internet connection is needed for styles to load.
- The dashboard image (`daisbord.webp`) referenced in the hero section needs to be added to the same folder as `index.html` for it to show up.
- The mobile menu and animations are done with plain CSS (`@keyframes`, `transition`) and vanilla JavaScript (`IntersectionObserver`) — no extra libraries required.
## To-Do / Ideas for Later
 
**Add real content for Pricing, About, and Contact sections
 *Replace placeholder dashboard image
 * Add a dark mode toggle
## How to Run
No build step needed — it's a static HTML file.
1. Download `index.html`
2. Open it directly in your browser (double click it), or
3. Run a local server, e.g.:
 
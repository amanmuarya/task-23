# AppName Landing Page
A responsive single-page landing site built with HTML and Tailwind CSS (via CDN).
 
## Structure
 
 **Nav bar** — sticky header with desktop links and a hamburger menu on mobile (below the `md` breakpoint).
 **Hero section** — headline, subtext, two CTA buttons, and a product screenshot.
 **Features section** — three cards (Lightning Fast, Secure, Analytics), each with an icon, title, and description.
 **Footer** — logo and copyright line.
## Responsive behavior
 Mobile-first, using Tailwind's sm / md / lg` breakpoints.
 Nav collapses into a hamburger menu below `md`; the menu toggles via a small vanilla JS function.
 Hero switches from stacked (mobile) to side-by-side (`lg`) layout.
 Feature cards go from 1 column to 3 columns at `md`.
Fill in below: which widths you actually tested at 

## Accessibility
 Hamburger button has aria-expande, aria-controls, and aria-label; the open/close icons are marked `aria-hidden` since the button itself is labeled.
 Visible focus outlines added on interactive elements for keyboard navigation.
## What I built vs. what was provided
 
Fill in: which parts of this you wrote yourself, which parts you got help with and adapted, and anything you changed from an earlier version.
 
## Challenges
Fill in: what was actually hard here. Was it the Tailwind breakpoints? Getting the JS toggle to sync with the ARIA attribute? Something else?
## What I'd do differently / next steps
 a mobile menu animation, dark mode, etc.

## How to run it
No build step needed — it's a static file.
1. Make sure `dashboard.webp` 
2. Open `index.html` directly in a browser, or serve it locally, e.g:
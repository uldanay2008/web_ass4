# Winx Studio — Web Project (Assignment #3)

A responsive beauty studio website developed using HTML5, CSS3, Media Queries, and Bootstrap 5.

## Team Members
- **Assylzhan** — Beauty Specialist 
- **Uldanay** — Creative Director 

## Project Overview
Winx Studio is a multi-page web application dedicated to beauty tips, cosmetics, makeup styles, and consultations. In this assignment, the project was updated with CSS Media Queries for fluid typography/layouts and integrated with Bootstrap 5 components (Grid System, Responsive Navbar, Carousel, Cards, Forms, Buttons, and Utilities).

## Live Demo
- **URL:** [https://uldanay2008.github.io/web_ass3/](https://uldanay2008.github.io/web_ass3/)
## Pages Included
1. **Home (`index.html`)** — Hero section, introduction, and responsive navigation cards.
2. **Makeup (`makeup.html`)** — Grid-based catalog of popular makeup styles, step-by-step guides, and tips.
3. **Products (`products.html`)** — Grid of cosmetics with Bootstrap buttons and responsive layout.
4. **Tips (`tips.html`)** — Quick beauty tips, image gallery, and interactive button groups.
5. **Team (`team.html`)** — Team member profile cards and a 9-image Bootstrap Carousel gallery.
6. **Contact (`contact.html`)** — Fully responsive contact form with Bootstrap form controls, input groups, radios, and checkboxes.

## Built With
- **HTML5** — Semantic markup and accessibility (ARIA attributes).
- **CSS3 / Media Queries** — Custom styles and responsive breakpoints.
- **Bootstrap v5.3.3** — Navbar, Grid (`col-lg-6`, `col-md-4`, etc.), Carousel, Cards, Forms, and Spacing Utilities.

## Features Implemented
- **Responsive Typography & Layouts:** Scalable headers (`h1`-`h2`) and flexible 3-to-1 card transitions using pure CSS media queries.
- **Bootstrap 5 Grid & Utilities:** Modern layout structure with built-in spacing classes (`py-5`, `px-3`, `gap-4`).
- **Bootstrap Navbar:** Responsive navigation bar with a collapsible hamburger menu (`navbar-toggler`).
- **Interactive Carousel:** 9-image studio gallery carousel with indicators and controls on `team.html`.
- **Accessible Form Design:** Contact form utilizing `form-control`, `input-group`, floating/inline checks, and full screen adaptation.

## Assignment 4 — JavaScript
- Contact: required fields, email format, minimum 8-character password, confirmation, field errors.
- Tips: three FAQ questions with smooth independent toggles.
- Every page: subscription dialog (button, outside click, close button, Escape), background color cycle, live local date/time.
- Custom code: `js/script.js`, linked with `defer` on all six HTML pages.
- Forms demonstrate client-side validation only. They do not send or store data.

## Run and submit
1. Extract the ZIP and open index.html, or use a local development server.
2. Bootstrap and remote images require an internet connection.
3. Test empty/invalid/valid contact form entries, FAQ toggles, popup close methods, background changes and the clock.
4. Upload updated files to the shared repository and redeploy GitHub Pages.
5. Prepare the report with your group, actual component ownership, screenshots, implementation steps, reflection and the verified deployed URL.

The existing URL above comes from Assignment 3; the Assignment 4 changes have not been deployed by this update.

### Extra catalog features
Open Products. Use All, Face, Lips or Eyes to filter seven cards. Click Save on a card, then enable Show favorites only. Saved IDs persist in localStorage for the same browser and origin. Filters apply to the Product Catalog; the separate carousel is unchanged.

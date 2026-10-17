Cumbre Trails: Project Summary

Live site: https://luisff511.github.io/cumbre-trails/
Repository: https://github.com/Luisff511/cumbre-trails

The company

Cumbre Trails is an imaginary company that runs small-group guided hiking tours in the mountains. It is based in Marbella (Málaga). It is aimed at beginners, families and experienced hikers who want certified guides, all the equipment they need and a safe way to enjoy nature.

Pages
Home (index.html): the landing page, built from the client’s design. It has:
a hero section with the title “Find your next summit”, a short introduction, a sign-up button and a photo of hikers;
a “Why hike with us?” section with four image cards (sunrise starts, hidden lakes, routes for every level and starry nights);
a customer testimonial;
a blue call-to-action box with a 10% discount on the first hike.
Tours (tours.html): the four signature routes. Each one shows its duration, difficulty, group size, price and a “Book now” button:
Sunrise Ridge (€45)
Hidden Lakes Loop (€60)
Forest Discovery (€25)
Starlight Camp (€140)
About us (about.html): a full-width mountain banner, the company’s story and mission, key figures (8 years of experience, 12k+ hikers, 40 routes and a 4.9 rating), a quote from the co-founder and the team of four guides.
Contact (contact.html): contact details (Avda. Ricardo Soriano 105, Marbella, plus phone, email and opening hours) and a sign-up form where users choose a tour and the number of people.

All pages share the same header, navigation, footer, colour palette and typography, so they look like one consistent website.

Technical features
Semantic HTML5: header, nav, main, section, article, aside, blockquote, figure, footer and form with labels.
Vanilla CSS: one external stylesheet per page (index.css, tours.css, about.css and contact.css).
Flexbox only. No CSS Grid and no JavaScript.
Client’s design system:
colours #1F2937, #F9FAF8, #E5E7EB and #3882F6;
the Roboto font, imported from Google Fonts;
the required sizes and weights: 48px extra-bold hero title, 36px headings and a 36px light italic quote.
Responsive design: media queries at 768px and 480px, tested at 375px, 768px and 1280px. Layouts stack vertically on small screens, and there is no horizontal overflow.
CSS-only burger menu: a hidden checkbox and its label (the “checkbox hack”). The selector .nav-toggle:checked ~ .main-nav shows the menu on screens of 768px or less.
Responsive images:
<picture> for art direction: a square crop on mobile and a wide crop on desktop, with WebP and a JPG fallback;
srcset with 1x/2x for the fixed-size cards;
srcset + sizes for the tour images and the full-width banner.
Font Awesome is used only for icons.
Real photos from Wikimedia Commons (public domain, CC0 and CC BY 2.0, with credit in the footer).
Hosted on GitHub Pages.

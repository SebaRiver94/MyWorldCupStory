🏆 My World Cup Story
Personal site chronicling my journeys to Russia 2018 and Qatar 2022 with travel tips, photos, and stadium highlights. Built with HTML5, Bootstrap 5, Sass, and Animate.css.








🌍 Table of Contents
Features

Pages

Project Structure

Run Locally

Sass Workflow

Animations

SEO Essentials

Deploy

Screenshots

Credits

License

✨ Features
5-section site with clean semantics and responsive layout

Bootstrap Grid for layout + utility classes

Animate.css effects on carousels and sections

Sass partials and variables for maintainable styling

Basic SEO and accessibility (titles, descriptions, alt text)

📄 Pages
Page	File	What’s inside
Home	index.html	Hero, intro, ticket CTA
Russia 2018	pages/rusia2018.html	Cities, stadiums, matches, trip summary
Qatar 2022	pages/qatar2022.html	Stadiums, matches, highlights
World Cup Tips	pages/travelTips.html	Flights, lodging, transport, fan ID
Contact 2026	pages/contact.html	Contact form + info carousel

🗂 Project Structure
arduino
Copiar
Editar
.
├── index.html
├── pages/
│   ├── rusia2018.html
│   ├── qatar2022.html
│   ├── travelTips.html
│   └── contact.html
├── styles/
│   └── styles.css            # compiled CSS (linked from HTML)
├── sass/                     # optional: Sass source
│   ├── main.scss
│   ├── _variables.scss
│   ├── _mixins.scss
│   ├── _base.scss
│   ├── _header.scss
│   ├── _buttons.scss
│   ├── _carousels.scss
│   ├── _travelTips.scss
│   ├── _accordion.scss
│   ├── _contact.scss
│   ├── _footer.scss
│   └── _responsive.scss
└── assets/
    ├── img/
    └── icons/
🧪 Run Locally
bash
Copiar
Editar
git clone <your-repo-url>
cd <your-repo>
# open index.html in your browser
Tip: Use VS Code’s Live Server for auto-reload.

🧵 Sass Workflow
Compile once (compressed):

bash
Copiar
Editar
sass sass/main.scss styles/styles.css --style=compressed --no-source-map
Watch mode (rebuild on save):

bash
Copiar
Editar
sass --watch sass/main.scss:styles/styles.css
Make sure your HTML links to:
<link rel="stylesheet" href="../styles/styles.css">

🎭 Animations
Animate.css via CDN in pages that need it.

Carousels use animate__animated + effect classes like:

animate__fadeIn, animate__fadeInUp (smooth)

animate__zoomIn (more punchy)

Small JS hook re-triggers the animation on slide change.

Change effect quickly by swapping the class on .carousel-item.

🔍 SEO Essentials
Unique <title> and meta description per page

meta viewport for responsive

Descriptive alt attributes on images

Concise, readable URLs and headings hierarchy

This project stays within the course scope: basic SEO + accessibility best practices.

🚀 Deploy
Hosted on Vercel: index.html as entry point

Update deployment via Git:

bash
Copiar
Editar
git add .
git commit -m "Update SEO and styles"
git push
🖼 Screenshots
Replace with your actual images from assets/img/ if you want to showcase.




🙌 Credits
Images & icons under assets/ for personal/educational use

Frameworks: Bootstrap, Animate.css

📄 License
Educational/demo use. Update the license if you plan broader distribution.


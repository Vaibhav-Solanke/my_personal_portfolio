📊 Flowchart
[Homepage (new.html)]
      |
      ├── About Section
      ├── Skills Section
      ├── Projects Section
      ├── Contact Section → [feedback.html]

      Welcome to my portfolio site!
      As you scroll down, sections animate smoothly into view — thanks to the AOS (Animate On Scroll) library.

These animations add polish and guide the viewer’s attention section by section.

On certain parts of the site (e.g., hero section or project highlights), you’ll notice interactive 3D elements powered by Spline, adding a futuristic and creative touch.

The rest of the flow remains intuitive: About → Skills → Projects → Contact form.

Landing View: The homepage opens with a clean header that includes my name and a short tagline about what I do.

About Section: Here, I introduce myself—who I am, what I’m passionate about, and my background.

Skills Section: Next, you’ll see my technical skills listed out clearly — from programming languages to tools I use daily.

Projects Section: This area showcases a few highlighted works, including descriptions and links to GitHub or live demos.

Contact Button: Clicking the contact link takes you to feedback.html, where visitors can send me a message via a form.

The site uses new.css for its visual styling and gradient.png to add subtle design flair. If added to a phone's home screen, it’ll display a custom icon thanks to apple-touch-icon.png.




🧩 Updated Components Table
File / Library	Description
AOS (via CDN/JS)	Adds scroll-based animations like fade-in, slide-up, zoom-in, etc.
Spline (via embed)	Embeds real-time 3D models directly into your webpage
new.html	Base HTML, includes sections and embeds for AOS/Spline
new.css	Custom styles (complementary to AOS classes)
feedback.html	Functional or placeholder contact form



✨ How to Set Up (AOS + Spline)
AOS Setup
Include AOS CSS + JS:

html

<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/aos@2.3.4/dist/aos.css" />
<script src="https://cdn.jsdelivr.net/npm/aos@2.3.4/dist/aos.js"></script>
Initialize it in your <script>:

js

AOS.init();
Add animations using data-aos:

html

<div data-aos="fade-up">This will animate on scroll</div>
Spline Setup
Go to Spline, create a model.

Click Share → Embed, and paste the iframe into your HTML:

html

<iframe src="https://my.spline.design/yourmodel" frameborder="0" width="100%" height="500px"></iframe>

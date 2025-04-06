Final Learning Journal Entry – Prac 9: Sass
Name: Deepesh Bijarnia
Subject: CP3402 – Web Design and Development
Prac: 9 – Sass

 What I Learned
In this practical, I explored the power of Sass (Syntactically Awesome Stylesheets) and how it enhances CSS development by introducing variables, nesting, mixins, inheritance, and modular file structures. I built a fully responsive personal portfolio site using a custom Sass setup and automated the workflow with Gulp and BrowserSync.

How to Start a Sass Project (Step-by-Step)
1. Create project folder structure: my-portfolio/
2. Install Sass globally: npm install -g sass
3. Compile SCSS to CSS continuously: sass scss/style.scss css/style.css --watch
4. (Optional but recommended) Set up Gulp for automation:
npm init -y
npm install gulp gulp-sass browser-sync --save-dev
5. Create a gulpfile.js:
Then run:
gulp

Key Sass Features I Used
•	Variables: For storing colors, font sizes, spacing units, and reusable design tokens.
•	Nesting: To write cleaner, scoped CSS inside components like .card, section, and form.
•	Mixins: I created mixins for hover effects, reusable button styles, and responsive breakpoints.
•	Extend/Inheritance: Applied shared styling using @extend for consistent component look and feel.
•	Partial SCSS files: Organized my styles into multiple partials and imported them using @use.



Workflow Setup
I used Gulp to automate the following tasks:
•	Watch .scss files for changes
•	Compile SCSS into CSS
•	Auto-reload browser using BrowserSync
This setup drastically improved development speed and made testing across screen sizes seamless.

My Project
I designed and built a modern, responsive one-page portfolio website, featuring:
•	A two-column About section with profile image and biography
•	Skill bars representing different levels of expertise using dynamic SCSS animations
•	A gallery of projects using Unsplash images and local assets
•	A mobile-first navigation menu with toggle animation
•	A styled contact form with responsive layout
All styling is done from scratch — no templates or frameworks used.

Challenges & Reflections
•	I faced some namespace conflicts while using @use and @forward, which helped me better understand Sass modules and scope.
•	Creating consistent styles for lightbox modals and skill animations required careful structuring of my mixins and variables.
•	Once the Gulp workflow was set up, it significantly improved my feedback loop and code organization.

Final Reflection
This practical gave me hands-on experience with Sass and how it scales CSS development. I now feel more confident using modular stylesheets, organizing code with partials, and automating builds. The integration of BrowserSync with Gulp made real-time editing intuitive, and the Sass syntax encouraged DRY (Don't Repeat Yourself) principles throughout my project.



# Final Learning Journal Entry – Prac 9: Sass

**Name**: Deepesh Bijarnia  
**Subject**: CP3402 – Web Design and Development  
**Prac**: 9 – Sass  



## What I Learned

In this practical, I explored the power of **Sass (Syntactically Awesome Stylesheets)** and how it enhances CSS development by introducing variables, nesting, mixins, inheritance, and modular file structures. I built a **fully responsive personal portfolio site** using a custom Sass setup and automated the workflow with **Gulp** and **BrowserSync**.



## How to Start a Sass Project (Step-by-Step)

1. **Create project folder structure**:

```
my-portfolio/
├── scss/
│   └── style.scss
├── css/
│   └── style.css (compiled)
├── index.html
```

2. **Install Sass globally**:

```bash
npm install -g sass
```

3. **Compile SCSS to CSS continuously**:

```bash
sass scss/style.scss css/style.css --watch
```

4. **(Optional but recommended)** Set up **Gulp** for automation:

```bash
npm init -y
npm install gulp gulp-sass browser-sync --save-dev
```

5. **Create a `gulpfile.js`**:

6. **Run the Gulp task**:

```bash
gulp
```

## Key Sass Features I Used

- **Variables**: For storing colors, font sizes, spacing units, and reusable design tokens.
- **Nesting**: For cleaner, scoped CSS inside components like `.card`, `section`, and `form`.
- **Mixins**: Created for hover effects, reusable button styles, and responsive breakpoints.
- **Extend/Inheritance**: Used `@extend` to apply shared styles and avoid repetition.
- **Partial SCSS files**: Structured my styles into modular files and imported using `@use`.

---

## Workflow Setup

Using **Gulp**, I automated:

- Watching `.scss` files for changes  
- Compiling SCSS into minified CSS  
- Auto-reloading the browser via **BrowserSync**

This workflow drastically improved development speed and helped test responsiveness in real time.


## My Project

I designed and built a modern, one-page responsive **portfolio website**, which features:

- A **two-column About section** with a profile image and biography  
- **Skill bars** using SCSS animations to display proficiency  
- A **project gallery** with images from **Unsplash** and local assets  
- A **mobile-first navigation menu** with toggle animation  
- A **styled contact form** with responsive behavior  

All styling is handcrafted — no third-party templates or frameworks used.



## Challenges & Reflections

- Encountered **namespace conflicts** using `@use` and `@forward` — resolving them deepened my understanding of Sass modules.
- Styling dynamic components like the **lightbox modal** and **skill bars** required careful planning and reusable mixins.
- Once the Gulp workflow was working, it significantly **boosted my productivity** and helped maintain clean, modular code.

---

## Final Reflection

This prac gave me hands-on experience with **Sass in a real-world project**. I now feel confident using modular SCSS, maintaining reusable components, and automating builds with **Gulp**. Integrating **BrowserSync** into the workflow was especially helpful for testing and iterating quickly. Overall, this practical solidified Sass as a powerful tool in my front-end toolkit.


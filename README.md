# Shubham's Portfolio Website

Welcome to the official online portfolio of Shubham Koshti! This modern, responsive website showcases my skills, projects, and professional journey in the fields of Software Development Engineering, Artificial Intelligence and Machine Learning.

🔗 [**Explore My Portfolio**](https://koshti.github.io/SHUBH-Portfolio/)

---

## Features

- **Responsive Design**: Optimized for all device sizes
- **Dynamic Theme Switcher**: Toggle between light and dark modes
- **Interactive UI**: Engaging animations and smooth transitions
- **Resume Showcase**: Separate sections for each career focus
- **Project Gallery**: Easily filter and explore my work
- **Publications & Certifications**: Academic and professional milestones
- **Contact Form**: Reach out directly for collaborations or inquiries

---

## Technology Stack

- HTML5 for structuring the content
- CSS3 (Flexbox, Grid, Custom Properties) for responsive layouts
- Vanilla JavaScript (ES6+) for interactive features
- Modular Architecture for maintainable and reusable code
- Font Awesome for icons
- Google Fonts for elegant typography
- Formspree for handling form submissions securely

---

## CSS Organization

The CSS is organized using a component-based approach:

- **base.css**: Core styles, variables, and global resets
- **common.css**: Shared styles for sections, animations, utility classes, etc.
- **responsive.css**: Contains all responsive styles for different screen sizes
- **components/**: Each UI component has its own stylesheet (e.g., `header.css`, `hero.css`, `about.css`, etc.)

### CSS Variables

The project uses CSS variables (custom properties) for consistent styling. Example:

```css
:root {
  --primary-color: #4361ee;
  --secondary-color: #3f37c9;
  --accent-color: #4895ef;
  --text-color: #333;
  --text-color-light: #666;
  --background-color: #fff;
  --background-alt: #f9f9f9;
  --card-bg: #fff;
  --border-color: #e0e0e0;
  --shadow-color: rgba(0, 0, 0, 0.1);
  --success-color: #4caf50;
  --spacing-xs: 0.5rem;
  --spacing-sm: 1rem;
  --spacing-md: 2rem;
  --spacing-lg: 3rem;
  --spacing-xl: 5rem;
  --border-radius-sm: 4px;
  --border-radius-md: 8px;
  --border-radius-lg: 16px;
  --transition-fast: 0.2s ease;
  --transition-normal: 0.3s ease;
  --transition-slow: 0.5s ease;
}
```

### Best Practices

- Use CSS variables for consistent styling
- Organize component-specific styles in `css/components/`
- Follow the BEM (Block Element Modifier) naming convention for clarity
- Define all media queries in `responsive.css` for better maintainability
-Keep reusable components in `common.css`

### Dark Mode

The site supports a dark mode toggle feature for users who prefer a darker interface. The transition is smooth and included in the component styles.

---

## Project Structure

```
portfolio/
├── index.html
├── css/
│   ├── base.css
│   ├── common.css
│   ├── responsive.css
│   ├── components/
│   │   ├── about.css
│   │   ├── certifications.css
│   │   ├── contact.css
│   │   ├── custom-icons.css
│   │   ├── education.css
│   │   ├── experience.css
│   │   ├── footer.css
│   │   ├── header.css
│   │   ├── hero.css
│   │   ├── model.css
│   │   ├── projects.css
│   │   ├── publications.css
│   │   ├── resume.css
│   │   └── skills.css
├── components/
│   ├── about.html
│   ├── certifications.html
│   ├── contact.html
│   ├── education.html
│   ├── experience.html
│   ├── footer.html
│   ├── header.html
│   ├── hero.html
│   ├── model.html
│   ├── projects.html
│   ├── publications.html
│   ├── resume.html
│   └── skills.html
├── js/
│   ├── main.js
│   └── template-engine.js
├── assets/
│   ├── favicon.svg
|   ├── certificates/
|   │   ├── Icons/
|   │   │   ├── brain.png
|   │   │   ├── certificate.png
|   │   │   ├── copyright.png
|   │   │   ├── python.png
│   |   |   └── sql-server.png
|   │   ├── Copyright Certificate PPMI.pdf
|   │   ├── IBM ML0109EN Certificate_Cognitive Class.pdf
│   |   └── Project Poster with Copyright.pdf
│   ├── images/
│   │   ├── e_beta_innovations_llp_logo.jpeg
│   │   ├── imr_logo.png
│   │   ├── SHUBH.png
│   │   └── SHUBHAM.png
│   ├── projects/
│   │   ├── AI_ChatBot.jpg
│   |   ├── OES_Project.jpeg
│   │   ├── Parkinson's Disease.jpg
│   │   ├── SQL_Query_Execution.png
│   │   ├── VR_Game_Testing.png
│   │   └── VR_Game.jpg
│   └── resumes/
│       └── Shubham_koshti_Resume.pdf
```

---

## Setup and Deployment

This website is designed to be hosted on GitHub Pages:

1. Fork this repository
2. Navigate to your repository settings on GitHub
3. Enable GitHub Pages, and choose `main` branch as the source
4. Your site will be available at `https://koshti.github.io/SHUBH-Portfolio/`

For local development:

1. Clone the repository
2. Open `index.html` in your browser to view the site locally

---

## Customization

- Replace the profile image in the `assets/images/` folder
- Upload your personal resume PDF in the `assets/resumes/` folder
- Update project information in the corresponding HTML files
- Customize colors by editing the CSS variables in `base.css`

---

## Contact Form

The contact form uses Formspree to handle submissions. To configure it for your own use:
1. Create a Formspree account
2. Set up a new form to get your form endpoint
3. Replace the form action URL in `contact.html` with your own Formspree endpoint

---
# Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript.

## 🚀 Live Demo

Visit your portfolio at: [https://skinnysnail.github.io](https://skinnysnail.github.io)

## ✨ Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Clean and professional design with smooth animations
- **Smooth Scrolling**: Enhanced user experience with smooth navigation
- **Mobile Menu**: Hamburger menu for mobile devices
- **Project Showcase**: Display your best projects with links to demos and repositories
- **Contact Section**: Multiple ways for people to reach you

## 📝 Customization Guide

### 1. Personal Information

Edit `index.html` to update your personal information:

- **Line 8**: Update `<title>` with your name
- **Line 32**: Replace "Your Name" with your actual name
- **Line 33**: Update your professional title/tagline
- **Line 34**: Change the description
- **Lines 46-50**: Update the About section with your bio
- **Lines 174-180**: Update email, GitHub, and LinkedIn links

### 2. Skills

Update the skills in the **Skills & Technologies** section (lines 54-63 in `index.html`):

```html
<div class="skill-item">Your Skill</div>
```

Add or remove skills as needed.

### 3. Projects

Customize the three project cards (starting around line 72):

For each project, update:
- Project title (`<h3>`)
- GitHub repository link
- Live demo link (or remove if not applicable)
- Project description
- Technology tags

**To add more projects**, copy a project card block and paste it within the `projects-grid` div.

### 4. Color Scheme

Edit `styles.css` to change colors. The color variables are at the top:

```css
:root {
    --primary-color: #6366f1;      /* Main brand color */
    --primary-dark: #4f46e5;       /* Darker shade */
    --secondary-color: #0ea5e9;    /* Accent color */
    /* ... other colors ... */
}
```

### 5. Adding a Profile Picture

To add your photo to the About section:

1. Add your image file to the repository
2. In `index.html`, add this before the about-text div:

```html
<div class="about-image">
    <img src="your-photo.jpg" alt="Your Name">
</div>
```

3. Add this CSS to `styles.css`:

```css
.about-image img {
    width: 100%;
    max-width: 400px;
    border-radius: 1rem;
    box-shadow: var(--shadow-lg);
}
```

## 🛠️ Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- Vanilla JavaScript
- GitHub Pages

## 📱 Responsive Breakpoints

- **Desktop**: > 768px
- **Tablet**: 768px
- **Mobile**: < 480px

## 🚀 Deployment

This site is automatically deployed to GitHub Pages from the `main` branch.

Any changes pushed to `main` will be reflected on your live site within a few minutes.

## 📄 License

Feel free to use this template for your own portfolio!

## 🤝 Contributing

Found a bug or want to suggest an improvement? Feel free to open an issue or submit a pull request!

---

**Built with ❤️ for your portfolio**

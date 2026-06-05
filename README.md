# Portfolio Website

Welcome to my portfolio website! This is a personal website showcasing my work as an artist and game developer.

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Dark Theme**: Modern dark theme with gradient accents
- **Multiple Sections**:
  - Hero section with call-to-action buttons
  - About me with personal statement and skills
  - Work portfolio divided into art and game development
  - Resume with experience, education, and achievements
  - Contact section with social links and contact form

## Getting Started

This website is built with:
- HTML5
- CSS3 (with CSS variables for easy theming)
- Vanilla JavaScript (no dependencies)

## Customization Guide

### 1. Update Personal Information
Edit `index.html` and replace:
- "TewOrcapt" with your name
- Email, LinkedIn, and social media links in the contact section
- About me text and description

### 2. Add Your Work
In the Work section, update:
- Art portfolio items with your artwork
- Game projects with descriptions and links
- You can replace placeholder images with actual image URLs

### 3. Update Resume
Modify the Resume section with:
- Your experience and positions
- Education details
- Achievements and certifications

### 4. Customize Colors
Edit the color variables in `styles.css`:
```css
:root {
    --primary-color: #6366f1;      /* Change to your preferred color */
    --secondary-color: #8b5cf6;
    --accent-color: #ec4899;
    /* ... other colors ... */
}
```

### 5. Add Contact Form Functionality
The contact form currently shows a placeholder alert. To make it functional:
- Use a service like [Formspree](https://formspree.io/)
- Or integrate with [EmailJS](https://www.emailjs.com/)
- Or set up your own backend

## File Structure

```
.
├── index.html       # Main HTML file
├── styles.css       # Styling and responsive design
├── script.js        # JavaScript functionality
└── README.md        # This file
```

## Deployment

This website is deployed on GitHub Pages at: `https://teworcapt.github.io/`

To update after making changes:
1. Commit your changes
2. Push to the main branch
3. Your changes will be live within minutes!

## Tips

- Keep file sizes optimized for faster loading
- Use descriptive project titles and descriptions
- Add actual images for your art and game projects
- Update your contact information
- Consider adding more detailed project pages as your portfolio grows

## License

This portfolio website is personal and proprietary.

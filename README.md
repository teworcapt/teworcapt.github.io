# Portfolio Website

Welcome to my portfolio website! This is a personal website showcasing my work as an artist and game developer.

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Dark Theme**: Modern dark theme with gradient accents
- **Image Folders**: Organized structure for images (hero background, art, games)
- **Multiple Sections**:
  - Hero section with background image
  - About me with personal statement and skills
  - Work portfolio divided into art and game development
  - Resume with experience, education, and achievements
  - Contact section with social links and contact form

## Getting Started

This website is built with:
- HTML5
- CSS3 (with CSS variables for easy theming)
- Vanilla JavaScript (no dependencies)

## Folder Structure

```
.
├── index.html           # Main HTML file
├── styles.css           # Styling and responsive design
├── script.js            # JavaScript functionality
├── README.md            # This file
├── images/
│   ├── hero-bg.jpg      # Hero section background image
│   ├── art/             # Art portfolio images
│   │   ├── artwork-1.jpg
│   │   ├── artwork-2.jpg
│   │   └── artwork-3.jpg
│   └── games/           # Game screenshots
│       ├── game-1.jpg
│       ├── game-2.jpg
│       └── game-3.jpg
└── assets/
    └── resume.pdf       # Your resume PDF
```

## Customization Guide

### 1. Add Hero Background Image

Place your hero background image at `images/hero-bg.jpg`. The image should be:
- Recommended size: 1920x1080px or larger
- Format: JPG, PNG, or WebP
- The image will be overlaid with a dark semi-transparent gradient for text readability

### 2. Add Artwork

Add your art portfolio images to the `images/art/` folder:
- `artwork-1.jpg` - First art piece
- `artwork-2.jpg` - Second art piece
- `artwork-3.jpg` - Third art piece

### 3. Add Game Screenshots

Add your game screenshots to the `images/games/` folder:
- `game-1.jpg` - First game screenshot
- `game-2.jpg` - Second game screenshot
- `game-3.jpg` - Third game screenshot

### 4. Update Personal Information

Edit `index.html` and replace:
- "TewOrcapt" with your name
- Email, LinkedIn, GitHub, and ArtStation links in the contact section
- About me text and description
- Work titles and descriptions

### 5. Update Resume

Modify the Resume section with:
- Your experience and positions
- Education details
- Real achievements and certifications

Place your resume PDF at `assets/resume.pdf`

### 6. Customize Colors

Edit the color variables in `styles.css`:
```css
:root {
    --primary-color: #6366f1;      /* Change to your preferred color */
    --secondary-color: #8b5cf6;
    --accent-color: #ec4899;
    /* ... other colors ... */
}
```

### 7. Add Contact Form Functionality

The contact form currently shows a placeholder alert. To make it functional:
- Use a service like [Formspree](https://formspree.io/)
- Or integrate with [EmailJS](https://www.emailjs.com/)
- Or set up your own backend

## Image Guidelines

- **Format**: JPG for photographs, PNG for graphics with transparency
- **Optimization**: Compress images to optimize page load times
- **Dimensions**: 
  - Hero background: 1920x1080px or larger
  - Portfolio items: 800x600px recommended
  - Maintain consistent aspect ratios

## Deployment

This website is deployed on GitHub Pages at: `https://teworcapt.github.io/`

To update after making changes:
1. Add or update files in the appropriate folders
2. Commit your changes
3. Push to the main branch
4. Your changes will be live within minutes!

## Tips

- Keep file sizes optimized for faster loading
- Use descriptive project titles and descriptions
- Add actual images for your art and game projects
- Update your contact information
- Consider adding more detailed project pages as your portfolio grows
- The placeholder images will show until you add your own

## License

This portfolio website is personal and proprietary.
# Portfolio Website

A modern, responsive portfolio website with an eye-friendly engineered background and smooth navigation.

## Features

- **Eye-friendly Design**: Engineered background with subtle gradients and grid patterns
- **Responsive Navigation**: Smooth scrolling navigation with mobile-friendly hamburger menu
- **Modern Sections**: Home, About, Skills, Projects, Resume, and Contact sections
- **Interactive Elements**: Hover effects, animations, and form validation
- **Mobile Responsive**: Optimized for all device sizes

## Sections

### 1. Home Section
- Hero section with your name and title
- Call-to-action buttons
- Profile image placeholder

### 2. About Section
- Personal description
- Experience statistics
- Professional background

### 3. Skills Section
- Categorized skills (Frontend, Backend, Tools)
- Interactive skill tags
- Animated skill items

### 4. Projects Section
- Featured project cards
- Technology tags
- Live demo and GitHub links

### 5. Resume Section
- Timeline-based experience
- Education details
- Downloadable resume

### 6. Contact Section
- Contact information
- Contact form with validation
- Social media links

## Customization Guide

### Personal Information
1. **Name and Title**: Update in `index.html`
   ```html
   <h1 class="hero-title">Hi, I'm <span class="highlight">Your Name</span></h1>
   <h2 class="hero-subtitle">Full Stack Developer</h2>
   ```

2. **About Section**: Modify the description in the about section
3. **Contact Information**: Update email, phone, and location
4. **Social Links**: Update GitHub, LinkedIn, Twitter, Instagram links

### Skills
Edit the skills in `index.html`:
```html
<div class="skill-items">
    <div class="skill-item">Your Skill</div>
    <!-- Add more skills -->
</div>
```

### Projects
Replace the project cards with your own:
```html
<div class="project-card">
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Project description</p>
        <div class="project-tech">
            <span>Technology</span>
        </div>
        <div class="project-links">
            <a href="your-demo-link" class="project-link">Live Demo</a>
            <a href="your-github-link" class="project-link">GitHub</a>
        </div>
    </div>
</div>
```

### Resume
Update your experience and education in the resume section.

### Colors and Styling
The main color scheme uses:
- Primary: `#667eea` (Blue)
- Secondary: `#764ba2` (Purple)
- Background: `#0a0a0a` (Dark)

To change colors, update the CSS variables in `styles.css`.

## File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge

## Performance Features

- Smooth scrolling navigation
- Lazy loading animations
- Optimized CSS with minimal reflows
- Mobile-first responsive design

## Getting Started

1. Download or clone the files
2. Open `index.html` in your browser
3. Customize the content as needed
4. Deploy to your preferred hosting service

## Deployment

You can deploy this portfolio to:
- GitHub Pages
- Netlify
- Vercel
- Any static hosting service

## Customization Tips

1. **Profile Image**: Replace the placeholder icon with your actual image
2. **Projects**: Add screenshots or GIFs of your projects
3. **Resume**: Link to your actual resume PDF
4. **Analytics**: Add Google Analytics or other tracking
5. **SEO**: Update meta tags and descriptions

## License

This project is open source and available under the MIT License.

## Support

For questions or issues, please refer to the code comments or create an issue in the repository. 
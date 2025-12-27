# Rohan Umbarepatil - Portfolio Website

A professional, premium-quality personal portfolio website showcasing skills, projects, and online presence.

## Features

- **Modern Design**: Clean, professional layout with dark theme and subtle gradients
- **Responsive**: Fully responsive design for mobile, tablet, and desktop
- **Interactive**: Smooth animations, micro-interactions, and scroll effects
- **Professional**: Corporate + creator-style blend suitable for job applications
- **SEO Optimized**: Proper meta tags and semantic HTML structure
- **Fast Loading**: Optimized performance and minimal dependencies

## Sections

1. **Hero Section** - Professional introduction with call-to-action buttons
2. **About Me** - Concise professional bio and passion statement
3. **Skills & Tools** - Programming languages, web technologies, and creative skills
4. **Projects** - Showcase of work with GitHub links and tech stacks
5. **Social Media** - Professional social media presence with priority links
6. **Contact** - Professional contact form with validation
7. **Footer** - Clean footer with social links and copyright

## Setup Instructions

1. **Download/Clone** the portfolio-website folder
2. **Open** `index.html` in your web browser
3. **Customize** the content as needed (see customization guide below)
4. **Deploy** to your preferred hosting platform

## Customization Guide

### Personal Information
- Edit `index.html` to update:
  - Name and title in hero section
  - About me content
  - Skills and technologies
  - Project details and links
  - Social media URLs

### Styling
- Modify `css/style.css` to:
  - Change color scheme (search for color variables)
  - Adjust fonts and typography
  - Modify spacing and layout
  - Add custom animations

### Functionality
- Update `js/script.js` to:
  - Add new interactive features
  - Modify form handling
  - Customize animations

### Adding Projects
To add new projects, copy this template in the projects section:

```html
<div class="project-card">
    <h3>Project Name</h3>
    <p>Project description highlighting key features and technologies used.</p>
    <div class="tech-stack">
        <span>Technology 1</span>
        <span>Technology 2</span>
        <span>Technology 3</span>
    </div>
    <a href="https://github.com/rohan1785/project-repo" target="_blank" class="project-link">
        <i class="fab fa-github"></i> View on GitHub
    </a>
</div>
```

## Deployment Options

### GitHub Pages
1. Create a new repository on GitHub
2. Upload all files to the repository
3. Go to Settings > Pages
4. Select source branch (usually main/master)
5. Your site will be available at `https://username.github.io/repository-name`

### Netlify
1. Drag and drop the portfolio-website folder to Netlify
2. Your site will be deployed automatically
3. Customize domain name if needed

### Vercel
1. Import the project from GitHub
2. Deploy with default settings
3. Your site will be live instantly

## File Structure

```
portfolio-website/
├── index.html          # Main HTML file
├── css/
│   └── style.css      # Stylesheet
├── js/
│   └── script.js      # JavaScript functionality
├── images/            # Image assets (add your photos here)
└── README.md          # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance Features

- Optimized CSS and JavaScript
- Lazy loading for images
- Smooth scroll behavior
- Efficient animations
- Minimal external dependencies

## Contact Form

The contact form includes:
- Client-side validation
- Professional styling
- Success/error notifications
- Responsive design

Note: For production use, you'll need to implement server-side form handling or use a service like Formspree, Netlify Forms, or EmailJS.

## Social Media Integration

The website includes dedicated sections for:
- GitHub (prioritized for professional visibility)
- LinkedIn (prioritized for professional networking)
- Instagram, Twitter, Facebook (additional presence)

All links open in new tabs and include proper icons.

## Maintenance

- Regularly update project information
- Keep social media links current
- Update skills as you learn new technologies
- Add new projects as you complete them
- Monitor and update contact information

## License

This portfolio template is free to use and modify for personal and commercial purposes.

---

**Built with passion by Rohan Umbarepatil**
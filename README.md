# Personal Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. Features smooth animations, mobile-friendly design, and interactive elements.

## Features

- **Responsive Design**: Works perfectly on all devices (desktop, tablet, mobile)
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: Hover effects, smooth scrolling, and dynamic content
- **Contact Form**: Functional contact form with validation
- **Performance Optimized**: Fast loading and smooth animations
- **Cross-Browser Compatible**: Works on all modern browsers

## Sections

1. **Hero Section**: Eye-catching introduction with call-to-action buttons
2. **About Section**: Personal information and statistics
3. **Skills Section**: Technical skills organized by category
4. **Projects Section**: Showcase of featured projects with descriptions
5. **Contact Section**: Contact information and contact form
6. **Footer**: Simple footer with copyright information

## Customization Guide

### 1. Personal Information

Edit the following in `index.html`:

- **Name**: Replace "Your Name" throughout the file
- **Title**: Change "Full Stack Developer & UI/UX Designer" to your profession
- **Description**: Update the hero description and about section
- **Contact Info**: Update email, phone, and location in the contact section

### 2. Profile Image

Replace the placeholder icon in the hero section:
- Remove the `<i class="fas fa-user-circle"></i>` icon
- Add your profile image: `<img src="your-image.jpg" alt="Your Name">`
- Update CSS accordingly in `style.css`

### 3. Skills

Update the skills section in `index.html`:
- Add or remove skill categories
- Update skill items with your technologies
- Change icons by using different Font Awesome classes

### 4. Projects

Customize your projects:
- Replace project titles, descriptions, and technologies
- Add real project images instead of placeholders
- Update project links (live demo and GitHub repository)

### 5. Colors and Styling

Customize the color scheme in `style.css`:
- Primary color: `#6c5ce7` (purple)
- Accent color: `#ffd700` (gold)
- Background gradients: Update gradient colors in hero and contact sections

### 6. Social Media Links

Update social media links in the contact section:
- LinkedIn, GitHub, Twitter, Instagram links
- Add or remove social platforms as needed

## Setup Instructions

1. **Download Files**: Ensure you have all three files:
   - `index.html`
   - `style.css`
   - `script.js`

2. **Add Images**: Create an `images` folder and add your:
   - Profile picture
   - Project screenshots
   - Any other images you want to use

3. **Update Content**: Follow the customization guide above

4. **Test Locally**: Open `index.html` in your browser to preview

5. **Deploy**: Upload files to your web hosting service

## Deployment Options

### GitHub Pages
1. Create a new repository on GitHub
2. Upload your files
3. Go to Settings > Pages
4. Select source branch (main/master)
5. Your site will be available at `username.github.io/repository-name`

### Netlify
1. Zip your project files
2. Go to netlify.com
3. Drag and drop your zip file
4. Your site will be live instantly

### Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in your project directory
3. Follow the prompts to deploy

## File Structure

```
portfolio/
│
├── index.html          # Main HTML file
├── style.css           # CSS styles
├── script.js           # JavaScript functionality
├── README.md           # This file
│
└── images/             # (Create this folder)
    ├── profile.jpg     # Your profile picture
    ├── project1.jpg    # Project screenshots
    └── project2.jpg
```

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Opera

## Performance Tips

1. **Optimize Images**: Compress images before uploading
2. **Minimize Code**: Remove unused CSS/JS in production
3. **Use CDN**: Keep Font Awesome and Google Fonts on CDN for faster loading
4. **Enable Compression**: Use gzip compression on your server

## Customization Examples

### Changing Colors
```css
/* In style.css, find and replace: */
#6c5ce7 → #your-primary-color
#ffd700 → #your-accent-color
```

### Adding New Projects
```html
<!-- Copy this structure in the projects section -->
<div class="project-card">
    <div class="project-image">
        <img src="images/your-project.jpg" alt="Project Name">
        <div class="project-overlay">
            <div class="project-links">
                <a href="your-live-demo-url" class="project-link">
                    <i class="fas fa-external-link-alt"></i>
                </a>
                <a href="your-github-repo-url" class="project-link">
                    <i class="fab fa-github"></i>
                </a>
            </div>
        </div>
    </div>
    <div class="project-content">
        <h3>Your Project Title</h3>
        <p>Your project description...</p>
        <div class="project-tech">
            <span class="tech-tag">React</span>
            <span class="tech-tag">Node.js</span>
        </div>
    </div>
</div>
```

## Troubleshooting

### Common Issues

1. **Animations not working**: Check if JavaScript is enabled
2. **Mobile menu not working**: Ensure script.js is linked correctly
3. **Fonts not loading**: Check internet connection for Google Fonts
4. **Icons not showing**: Verify Font Awesome CDN link

### Contact Form

The contact form includes client-side validation. For a fully functional form, you'll need to:
1. Set up a backend service (Node.js, PHP, etc.)
2. Or use a service like Formspree, Netlify Forms, or EmailJS

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you need help customizing your portfolio:
1. Check this README file
2. Look at the code comments
3. Search online for HTML/CSS/JS tutorials
4. Consider hiring a developer for complex customizations

---

**Happy coding! 🚀**

Remember to update this README file with your own information and any additional features you add to your portfolio.

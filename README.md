# Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Smooth Animations**: Fade-in animations and smooth scrolling
- **Modern UI**: Clean and professional design with gradient elements
- **Sections Included**:
  - Navigation bar with smooth scrolling
  - Hero section with call-to-action
  - About section with stats
  - Featured projects showcase
  - Skills and technologies
  - Contact form
  - Social media links
  - Footer

## File Structure

```
portfolio/
├── index.html      # Main HTML file
├── styles.css      # Styling and responsive layout
├── script.js       # Interactive features and animations
└── README.md       # This file
```

## Getting Started

1. **Open the website**: Simply open `index.html` in your web browser
2. **Customize the content**:
   - Replace "Your Name" with your actual name in the hero section
   - Update the About section with your bio
   - Add your actual projects in the Projects section
   - Update skills with your technologies
   - Add your contact information and social media links

## Customization Guide

### Change Your Name
Find this line in `index.html`:
```html
<h1>Hi, I'm <span class="highlight">Your Name</span></h1>
```
Replace "Your Name" with your actual name.

### Update Projects
Modify the project cards in the Projects section with your actual projects:
```html
<div class="project-card">
    <div class="project-image" style="background: linear-gradient(...)"></div>
    <h3>Your Project Name</h3>
    <p>Your project description</p>
    <!-- ... -->
</div>
```

### Change Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #667eea;
    --secondary-color: #764ba2;
    /* ... other colors ... */
}
```

### Add Your Social Links
Update the social links in the Contact section:
```html
<div class="social-links">
    <a href="https://github.com/yourprofile" title="GitHub">GitHub</a>
    <a href="https://linkedin.com/in/yourprofile" title="LinkedIn">LinkedIn</a>
    <!-- ... -->
</div>
```

## Features Implemented

### JavaScript Functionality
- **Smooth Scrolling**: Click navigation links for smooth page scrolling
- **Mobile Menu**: Hamburger menu for mobile devices
- **Form Handling**: Contact form with success message
- **Scroll Animations**: Elements fade in as they come into view
- **Active Navigation**: Highlights current section in navbar
- **Scroll-to-Top Button**: Appears when scrolling down the page
- **Navbar Shadow**: Enhances on scroll for better UX
- **Counter Animation**: Animated statistics in About section

### Responsive Breakpoints
- **Desktop**: Full layout with optimal spacing
- **Tablet** (≤768px): Adjusted grid layouts
- **Mobile** (≤480px): Single column layout with optimized touch targets

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Tips for Best Results

1. **Profile Picture**: Add your profile picture to the About section
2. **Project Images**: Replace project placeholder images with actual screenshots
3. **Project Links**: Add real links to your deployed projects or repositories
4. **Contact Form**: For production, integrate with a backend service like FormSubmit or Emailjs
5. **SEO**: Update meta tags in `index.html` for better search engine visibility
6. **Analytics**: Consider adding Google Analytics for tracking

## Deployment

To deploy your portfolio:

### GitHub Pages
1. Create a GitHub repository named `yourusername.github.io`
2. Push all files to the repository
3. Your site will be live at `https://yourusername.github.io`

### Other Hosting Options
- Netlify (drag and drop deployment)
- Vercel
- Firebase Hosting
- Heroku

## Future Enhancements

- Add a blog section
- Include project filtering
- Add dark mode toggle
- Implement email notifications for contact form
- Add testimonials section
- Include PDF resume download

## License

This template is free to use and modify for personal use.

## Support

For any issues or questions, refer to the code comments in the HTML, CSS, and JavaScript files.

Enjoy your new portfolio website! 🚀

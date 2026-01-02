# Michael Dedvukaj - Professional Portfolio

A modern, responsive portfolio website showcasing cybersecurity expertise, software engineering projects, and iOS development skills.

## Features

- **Modern Design**: Premium UI with smooth animations and micro-interactions
- **Dark Mode**: Full dark mode support with persistent theme preference
- **Responsive**: Fully responsive design that works on all devices
- **Performance Optimized**: Fast loading with optimized animations
- **Accessibility**: Semantic HTML and ARIA labels for better accessibility
- **Interactive Elements**: Animated skill bars, counting stats, and smooth scrolling

## Design Highlights

- **Gradient Backgrounds**: Dynamic gradient orbs with parallax effect
- **Smooth Animations**: Intersection Observer API for scroll-triggered animations
- **Modern Typography**: Inter font family for professional appearance
- **Color System**: Comprehensive design tokens for consistent theming
- **Glassmorphism**: Modern frosted glass effects on navigation

## Project Structure

```
MDportfolio/
├── index.html                          # Main HTML file
├── styles.css                          # Complete CSS with design system
├── script.js                           # JavaScript for interactivity
├── README.md                           # This file
└── Copy of OWASP Honeynet...pdf       # Research paper (linked in projects)
```

## Featured Projects

### 1. OWASP Honeynet Experiment
- **Type**: Cybersecurity Research (Capstone Project)
- **Description**: Comprehensive honeypot system deployment and analysis
- **Documentation**: 31-page research paper included
- **Technologies**: Network Security, Honeypot Systems, Threat Analysis, Linux, Wireshark

### 2. QuickSend
- **Type**: iOS Application
- **Description**: Secure file sharing app with subscription management
- **Status**: Live on App Store
- **Technologies**: Swift, UIKit, iOS Development, Cloud Storage, StoreKit

### 3. Network Security Analysis
- **Type**: Security Tools
- **Description**: Custom scripts for network analysis and vulnerability assessment
- **Technologies**: Python, Network Analysis, Security Monitoring

## 🛠️ Technical Skills Showcased

### Cybersecurity
- Network Security
- Threat Analysis
- Vulnerability Assessment
- Security Monitoring

### Development
- Swift / iOS Development
- Python
- JavaScript
- Git / Version Control

### Infrastructure
- AWS Cloud Services
- Linux Systems
- Network Configuration
- Docker

### Tools
- Wireshark, Nmap, Burp Suite, Metasploit
- Xcode, VS Code
- Splunk, Postman
- MongoDB, PostgreSQL

## Customization Guide

### Update Personal Information

1. **Contact Details** (index.html, lines 171-173):
   ```html
   <a href="mailto:YOUR_EMAIL@example.com" class="contact-method">
   <a href="https://linkedin.com/in/YOUR_PROFILE" class="contact-method">
   <a href="https://github.com/YOUR_USERNAME" class="contact-method">
   ```

2. **Stats Numbers** (index.html, lines 117-129):
   - Update `data-target` attributes with your actual numbers
   - Modify descriptions to match your achievements

3. **Project Details**:
   - Update project descriptions
   - Add actual App Store link for QuickSend
   - Modify technology tags as needed

### Add Resume Download

Replace the placeholder link in the Contact section:
```html
<a href="path/to/your-resume.pdf" class="btn btn-primary" download>
```

### Customize Colors

Edit CSS variables in `styles.css` (lines 8-20):
```css
:root {
    --color-primary: #6366f1;  /* Change to your brand color */
    --color-secondary: #8b5cf6;
    --color-accent: #ec4899;
}
```

## Deployment Options

### Option 1: GitHub Pages (Recommended - Free)

1. Create a new GitHub repository
2. Push your portfolio files
3. Go to Settings → Pages
4. Select "Deploy from a branch"
5. Choose "main" branch and "/ (root)" folder
6. Your site will be live at `https://yourusername.github.io/repository-name`

### Option 2: Netlify (Free)

1. Sign up at [netlify.com](https://netlify.com)
2. Drag and drop your portfolio folder
3. Your site will be live instantly with a custom URL

### Option 3: Vercel (Free)

1. Sign up at [vercel.com](https://vercel.com)
2. Import your GitHub repository
3. Deploy with one click

## Testing

### Local Testing

Simply open `index.html` in your browser:
```bash
open index.html
```

Or use a local server:
```bash
# Python 3
python3 -m http.server 8000

# Then visit http://localhost:8000
```

### Browser Compatibility

Tested and working on:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## SEO Optimization

The portfolio includes:
- Semantic HTML5 elements
- Meta descriptions
- Proper heading hierarchy
- Alt text for images (when added)
- Fast loading times
- Mobile-friendly design

### Add More SEO

Add these meta tags to `<head>`:
```html
<meta name="author" content="Michael Dedvukaj">
<meta name="keywords" content="cybersecurity, software engineer, iOS developer, network security">
<meta property="og:title" content="Michael Dedvukaj - Cybersecurity & Software Engineer">
<meta property="og:description" content="Portfolio showcasing cybersecurity projects and iOS development">
<meta property="og:image" content="path/to/preview-image.jpg">
```

## Adding Screenshots

To add project screenshots:

1. Create an `images` folder
2. Add your screenshots
3. Update the project cards:
   ```html
   <div class="project-image" style="background-image: url('images/project-screenshot.jpg');">
   ```

## Features to Add (Optional)

- [ ] Contact form with backend integration
- [ ] Blog section for technical articles
- [ ] Testimonials section
- [ ] Certifications showcase
- [ ] Project case studies with detailed pages
- [ ] Analytics integration (Google Analytics)

## Troubleshooting

### Dark mode not persisting
- Check browser localStorage is enabled
- Clear cache and reload

### Animations not working
- Ensure JavaScript is enabled
- Check browser console for errors

### Mobile menu not appearing
- Resize window or reload page
- Check if viewport meta tag is present

## License

This portfolio template is free to use and modify for personal use.

## Credits

- **Design & Development**: Custom built
- **Fonts**: [Inter](https://fonts.google.com/specimen/Inter) by Google Fonts
- **Icons**: Unicode emojis (universal support)

## Support

For questions about this portfolio:
- Review the code comments
- Check browser console for errors
- Ensure all files are in the same directory

---
*Last updated: January 2026*

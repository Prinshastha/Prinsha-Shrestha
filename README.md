# Prinsha Shrestha - Personal Portfolio Website

A modern, responsive personal portfolio website showcasing professional experience, skills, and expertise in digital marketing and operations.

## Features

✨ **Modern Design**
- Clean, professional UI with smooth animations
- Fully responsive design (mobile, tablet, desktop)
- Gradient backgrounds and interactive elements

📱 **Responsive Layout**
- Mobile-first approach
- Hamburger menu for mobile devices
- Adaptive grid layouts

🎯 **Key Sections**
- Hero section with call-to-action buttons
- Professional summary
- Areas of expertise (12 key competencies)
- Detailed work experience
- Education and certifications
- Career objectives and hobbies
- Contact information

⚡ **Interactive Features**
- Smooth scrolling navigation
- Mobile menu toggle
- Hover animations
- Scroll-based animations
- Active navigation highlighting

🎨 **Customizable Colors**
- Primary: Deep Blue (#1e3a8a)
- Secondary: Teal (#0f766e)
- Accent: Amber (#f59e0b)
- Easy to customize via CSS variables

## File Structure

```
Prinsha/
├── index.html          # Main HTML file
├── styles.css          # Stylesheet with responsive design
├── script.js           # JavaScript for interactivity
└── README.md           # Documentation (this file)
```

## Getting Started

### Option 1: View Locally
1. Download or clone the repository
2. Open `index.html` in your web browser
3. Navigate through the website using the menu

### Option 2: Deploy Online

#### Deploy to GitHub Pages
1. Push the files to a GitHub repository
2. Go to repository Settings → Pages
3. Select `main` branch as source
4. Your site will be live at `https://yourusername.github.io/Prinsha`

#### Deploy to Netlify
1. Drag and drop the project folder to [netlify.com](https://netlify.com)
2. Or connect your GitHub repository
3. Your site will be live automatically

#### Deploy to Vercel
1. Connect your GitHub repository to [vercel.com](https://vercel.com)
2. Click "Import" and follow the steps
3. Your site will be live automatically

#### Deploy to Heroku / Other Hosting
1. Add a simple `server.js` or use a static hosting service
2. Upload files to your hosting provider
3. Access via your custom domain

## Customization

### Update Contact Information
Edit the contact details in `index.html`:
```html
<span>+977 986-1584363</span>
<span>shresthaprinsha2012@gmail.com</span>
<span>Swyambhu, Kathmandu</span>
```

### Update LinkedIn Profile
Find the LinkedIn link in the contact section and replace with your profile:
```html
<a href="https://www.linkedin.com/in/your-profile" class="contact-method" target="_blank">
```

### Customize Colors
Edit CSS variables in `styles.css`:
```css
:root {
    --primary-color: #1e3a8a;      /* Change this */
    --secondary-color: #0f766e;    /* Change this */
    --accent-color: #f59e0b;       /* Change this */
}
```

### Add Profile Picture
Add to the hero section in `index.html`:
```html
<img src="path/to/your/photo.jpg" alt="Profile Picture" class="profile-image">
```

And add CSS:
```css
.profile-image {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    margin-bottom: 1rem;
    box-shadow: var(--shadow-lg);
}
```

### Add Social Links
Add more contact methods in the contact section:
```html
<a href="https://twitter.com/yourhandle" class="contact-method" target="_blank">
    <i class="fab fa-twitter"></i>
    <span>Twitter</span>
</a>
```

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- Optimized images and CSS
- Minimal JavaScript for fast loading
- Responsive images for different screen sizes
- CDN-hosted Font Awesome icons

## SEO Features

- Semantic HTML structure
- Meta tags for better indexing
- Descriptive page title
- Structured content sections

## Future Enhancements

- [ ] Add contact form with backend
- [ ] Add blog section
- [ ] Add project portfolio
- [ ] Add testimonials/recommendations section
- [ ] Implement dark mode toggle
- [ ] Add PDF resume download
- [ ] Add search functionality
- [ ] Performance metrics

## License

This portfolio website is personal and can be freely used and modified.

## Support

For any issues or questions:
- Email: shresthaprinsha2012@gmail.com
- Phone: +977 986-1584363

---

**Last Updated:** December 2024

Created with ❤️ for showcasing professional excellence

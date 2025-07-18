# Sharath - Graphic Designer Portfolio

A modern, responsive portfolio website for graphic designers built with HTML, CSS, and JavaScript. This portfolio showcases your work, skills, and services in an attractive and professional manner.

## 🚀 Features

- **Modern Design**: Clean, professional layout with modern typography and color scheme
- **Responsive**: Fully responsive design that works on all devices
- **Interactive Portfolio**: Filterable portfolio section with hover effects
- **Smooth Animations**: CSS animations and JavaScript interactions
- **Contact Form**: Functional contact form with validation
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Performance Optimized**: Fast loading with optimized code

## 📁 File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🛠️ Setup Instructions

1. **Download/Clone** the files to your local machine
2. **Open** `index.html` in your web browser
3. **Customize** the content as needed (see customization guide below)
4. **Deploy** to your preferred hosting service

## 🎨 Customization Guide

### 1. Personal Information

Edit the following sections in `index.html`:

- **Name**: Replace "Sharath" with your name throughout the file
- **Title**: Update the hero title and subtitle
- **About Section**: Modify the description and skills
- **Contact Information**: Update email, phone, and location
- **Social Links**: Add your social media profiles

### 2. Portfolio Projects

Replace the placeholder images and content in the portfolio section:

```html
<div class="portfolio-item" data-category="branding">
    <div class="portfolio-image">
        <img src="your-project-image.jpg" alt="Project Description">
        <div class="portfolio-overlay">
            <h3>Your Project Title</h3>
            <p>Project description</p>
            <a href="#" class="portfolio-link">View Project</a>
        </div>
    </div>
</div>
```

### 3. Services

Update the services section with your specific offerings:

```html
<div class="service-card">
    <div class="service-icon">
        <i class="fas fa-palette"></i>
    </div>
    <h3>Your Service</h3>
    <p>Service description</p>
</div>
```

### 4. Colors and Styling

Modify the color scheme in `styles.css`:

```css
/* Primary Colors */
:root {
    --primary-color: #6366f1;
    --secondary-color: #8b5cf6;
    --accent-color: #10b981;
}
```

### 5. Images

Replace placeholder images with your actual work:
- Portfolio project images
- Profile photo (if desired)
- Logo or branding elements

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

## 🔧 Technical Features

### CSS Features
- CSS Grid and Flexbox layouts
- CSS animations and transitions
- Custom properties (CSS variables)
- Media queries for responsiveness

### JavaScript Features
- Mobile navigation toggle
- Portfolio filtering system
- Smooth scrolling navigation
- Form validation
- Intersection Observer animations
- Counter animations
- Parallax effects

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 📧 Contact Form

The contact form includes:
- Name, email, subject, and message fields
- Client-side validation
- Success message simulation
- Form reset after submission

**Note**: The form currently shows a success message. To make it functional, you'll need to:
1. Set up a backend service (PHP, Node.js, etc.)
2. Configure email sending functionality
3. Update the form action and method

## 🚀 Deployment Options

### GitHub Pages
1. Create a GitHub repository
2. Upload your files
3. Enable GitHub Pages in repository settings

### Netlify
1. Drag and drop your folder to Netlify
2. Your site will be live instantly

### Vercel
1. Connect your GitHub repository
2. Deploy automatically

### Traditional Hosting
1. Upload files via FTP
2. Point your domain to the hosting

## 📝 Customization Tips

1. **Images**: Use high-quality images (recommended: 1200x800px for portfolio items)
2. **Content**: Keep descriptions concise and engaging
3. **Performance**: Optimize images before uploading
4. **SEO**: Add meta tags and descriptions
5. **Analytics**: Add Google Analytics or similar tracking

## 🎯 SEO Optimization

Add these meta tags to the `<head>` section:

```html
<meta name="description" content="Professional graphic designer portfolio showcasing creative work and services">
<meta name="keywords" content="graphic design, branding, logo design, web design, portfolio">
<meta name="author" content="Your Name">
<meta property="og:title" content="Your Name - Graphic Designer">
<meta property="og:description" content="Professional graphic designer portfolio">
<meta property="og:image" content="your-image.jpg">
```

## 🔒 Security Considerations

- Validate all form inputs
- Use HTTPS for production
- Sanitize user inputs
- Keep dependencies updated

## 📞 Support

If you need help customizing your portfolio:
1. Check the code comments for guidance
2. Review the CSS classes for styling options
3. Test on different devices and browsers
4. Validate your HTML and CSS

## 📄 License

This portfolio template is free to use for personal and commercial projects.

---

**Happy designing! 🎨**

Feel free to modify this template to match your unique style and showcase your amazing work. #   P r o j e c t _ P o r t f o l i o  
 
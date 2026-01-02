# Paul Joseph Kohler - Professional Music Portfolio Website

A responsive, professional website for showcasing your piano accompanist services and teaching credentials.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Professional Styling**: Clean, modern design with elegant typography
- **Smooth Navigation**: Single-page application with smooth scrolling
- **Contact Form**: Functional contact form with validation
- **Mobile Menu**: Hamburger menu for mobile devices
- **Performance Optimized**: Fast loading with optimized animations

## File Structure

```
pauljosephkohler/
├── index.html          # Main HTML structure
├── styles.css          # All styling and responsive design
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Customization Guide

### 1. Adding Your Photo

Replace the placeholder in the hero section:

```html
<!-- In index.html, around line 60 -->
<div class="hero-image">
  <img src="your-photo.jpg" alt="Paul Joseph Kohler" class="hero-photo" />
</div>
```

And update the CSS:

```css
/* In styles.css, replace the .image-placeholder styles */
.hero-photo {
  width: 300px;
  height: 400px;
  object-fit: cover;
  border-radius: 10px;
  box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
}
```

### 2. Updating Personal Information

#### Contact Details

Update the contact information in `index.html`:

```html
<!-- Around line 130 -->
<div class="contact-item">
  <i class="fas fa-envelope"></i>
  <div>
    <h4>Email</h4>
    <p>your.actual.email@example.com</p>
  </div>
</div>
<div class="contact-item">
  <i class="fas fa-phone"></i>
  <div>
    <h4>Phone</h4>
    <p>(555) 123-4567</p>
  </div>
</div>
<div class="contact-item">
  <i class="fas fa-map-marker-alt"></i>
  <div>
    <h4>Location</h4>
    <p>Your City, State</p>
  </div>
</div>
```

#### Page Title

Update the title in `index.html`:

```html
<title>Paul Joseph Kohler - Piano Accompanist</title>
```

### 3. Adding Your Qualifications

In the Accompanist section, replace the placeholder text:

```html
<!-- Around line 80 -->
<div class="qualification-item">
  <h4>Education</h4>
  <p>Bachelor of Music in Piano Performance, University Name, 20XX</p>
</div>
<div class="qualification-item">
  <h4>Performance Experience</h4>
  <p>
    10+ years accompanying vocalists, instrumentalists, and choirs in various
    settings including recitals, competitions, and professional performances.
  </p>
</div>
<div class="qualification-item">
  <h4>Specializations</h4>
  <p>
    Classical piano accompaniment, vocal coaching, chamber music, contemporary
    repertoire
  </p>
</div>
```

### 4. Adding Performance Samples

Replace the sample placeholders with your actual content:

```html
<!-- Around line 100 -->
<div class="sample-item">
  <div class="sample-placeholder">
    <!-- Replace with actual video/audio embed or image -->
    <iframe src="your-video-url" frameborder="0" allowfullscreen></iframe>
  </div>
  <h4>Schubert Lieder Accompaniment</h4>
  <p>Performance with soprano at Carnegie Hall, 2023</p>
</div>
```

### 5. Updating Teaching Information

#### Teaching Philosophy

```html
<!-- Around line 180 -->
<div class="teaching-philosophy">
  <h3>Teaching Philosophy</h3>
  <p>
    I believe in fostering a love for music while developing strong technical
    foundations. My approach combines traditional methods with modern
    pedagogical techniques, tailored to each student's unique learning style and
    goals.
  </p>
</div>
```

#### Teaching Services

```html
<!-- Around line 190 -->
<div class="service-item">
  <i class="fas fa-graduation-cap"></i>
  <h4>Private Piano Lessons</h4>
  <p>
    One-on-one instruction for all ages and skill levels, from beginners to
    advanced students preparing for competitions and auditions.
  </p>
</div>
```

#### Student Testimonials

```html
<!-- Around line 210 -->
<div class="testimonial-item">
  <p>
    "Paul's teaching style is both encouraging and challenging. He helped me
    develop not just technical skills, but also musical expression and
    confidence."
  </p>
  <h4>- Sarah Johnson, Student</h4>
</div>
```

### 6. Customizing Colors

To change the color scheme, update these CSS variables in `styles.css`:

```css
/* Primary color (currently grayscale) */
.btn-primary {
  background: #your-color;
}

/* Secondary color for accents */
.nav-link:hover,
.nav-link.active {
  color: #your-accent-color;
}
```

### 7. Adding Social Media Links

Add social media icons to the footer:

```html
<!-- In the footer section -->
<div class="social-links">
  <a href="https://linkedin.com/in/yourprofile" target="_blank">
    <i class="fab fa-linkedin"></i>
  </a>
  <a href="https://youtube.com/yourchannel" target="_blank">
    <i class="fab fa-youtube"></i>
  </a>
  <a href="https://instagram.com/yourprofile" target="_blank">
    <i class="fab fa-instagram"></i>
  </a>
</div>
```

## Setting Up the Contact Form

The contact form is currently set up to show a success message. To make it functional:

1. **For a simple solution**: Use a service like Formspree or Netlify Forms
2. **For a custom solution**: Set up a backend server to handle form submissions

### Using Formspree (Recommended for beginners):

1. Go to [formspree.io](https://formspree.io)
2. Create a free account
3. Create a new form
4. Update the form action in `index.html`:

```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST"></form>
```

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Tips

1. **Optimize images**: Use WebP format when possible, compress images
2. **Minimize HTTP requests**: Combine CSS/JS files for production
3. **Use a CDN**: Consider hosting on Netlify, Vercel, or similar for better performance

## Deployment

### Option 1: GitHub Pages

1. Push your code to a GitHub repository
2. Go to Settings > Pages
3. Select source branch (usually `main`)
4. Your site will be available at `https://username.github.io/repository-name`

### Option 2: Netlify (Recommended)

1. Go to [netlify.com](https://netlify.com)
2. Drag and drop your project folder
3. Your site will be live instantly with a custom URL

### Option 3: Traditional Web Hosting

Upload all files to your web hosting provider's public directory.

## Support

The code is well-commented and organized for easy modification. Each section is clearly marked in the HTML, and CSS classes are descriptive and semantic.

## License

This template is free to use and modify for your personal portfolio.

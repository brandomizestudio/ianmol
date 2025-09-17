# ianmol's Portfolio Website

A modern, minimalistic portfolio website featuring smooth animations, interactive elements, and responsive design.

## Features

### 🎨 Design & Animations
- **Modern Dark Theme**: Sleek dark design with gradient accents
- **Smooth Animations**: CSS keyframes and JavaScript-powered animations
- **Scroll Animations**: Elements animate into view as you scroll
- **Interactive Elements**: Hover effects, magnetic buttons, cursor trail
- **Loading Screen**: Professional loading animation on page load

### 📱 Responsive Design
- **Mobile-First**: Optimized for all screen sizes
- **Touch-Friendly**: Mobile navigation and touch interactions
- **Adaptive Layout**: Grid layouts that adapt to different screens

### 🚀 Interactive Features
- **Typing Animation**: Animated introduction text
- **Parallax Effects**: Subtle background movement on scroll
- **Counter Animations**: Animated statistics numbers
- **Smooth Scrolling**: Seamless navigation between sections
- **Contact Form**: Functional contact form with validation

## Sections

### 1. Hero Section
- Animated introduction with typing effect
- Updated subtitle: "Web Developer, Video Editor & Entrepreneur"
- Mentions Brandomize company in description
- Professional stock portrait (placeholder for your photo)
- Call-to-action buttons
- Scroll indicator

### 2. About Section
- Personal description highlighting entrepreneurship
- Updated to mention Brandomize company founding
- Animated statistics
- Education timeline with your academic journey:
  - BCA from GJU University (2020-2023)
  - Senior Secondary from Pioneer Convert School (2018-2020)
  - Secondary from S.V.M High School (2017-2018)

### 3. Skills Section
- Interactive skill cards with hover animations
- **Web Development**: HTML/CSS, JavaScript, React, Node.js
- **Video Editing**: DaVinci Resolve, Final Cut Pro, Color Grading
- **Color Grading**: Color Theory, LUTs, HDR, Cinematic Look
- **AI Tools**: ChatGPT, Midjourney, GitHub Copilot

### 4. Projects Section
- Placeholder project cards (ready for your real projects)
- Hover effects and overlay animations
- Project links and technology tags

### 5. Services Section (Brandomize)
- Company introduction and overview
- Interactive service cards with hover effects:
  - **YouTube Growth**: Content strategy, SEO optimization, audience analysis
  - **Instagram Marketing**: Content creation, hashtag strategy, story optimization
  - **SOP & Workflows**: Process mapping, automation setup, documentation
  - **Local Visibility**: Local SEO, Google My Business optimization
  - **Business Growth**: Digital strategy, brand development, online presence
  - **Personal Branding**: Brand strategy, content planning, authority building
- Call-to-action section for potential clients

### 6. Contact Section
- Contact information
- Interactive contact form
- Social media links
- Professional layout

## File Structure

```
ianmol-portfolio/
├── index.html          # Main HTML structure
├── styles.css          # All CSS styles and animations
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Advanced styling, animations, and responsive design
- **Vanilla JavaScript**: Interactive functionality
- **Font Awesome**: Icons
- **Google Fonts**: Inter font family
- **Unsplash**: Stock images (placeholders)

## Customization

### Adding Your Photos
Replace the stock image URLs in `index.html`:
```html
<!-- Hero section profile image -->
<img src="your-profile-photo.jpg" alt="Ianmol Portrait" class="profile-img">

<!-- Project images -->
<img src="your-project-image.jpg" alt="Project Name">
```

### Updating Contact Information
Edit the contact details in the contact section:
```html
<div class="contact-item">
    <i class="fas fa-envelope"></i>
    <span>your-email@example.com</span>
</div>
```

### Adding Real Projects
Replace the placeholder projects with your actual work:
1. Update project images
2. Change project titles and descriptions
3. Add real project links
4. Update technology tags

### Color Scheme
The website uses a modern color palette:
- **Primary**: #00d4ff (Cyan blue)
- **Secondary**: #7c3aed (Purple)
- **Background**: #0a0a0a (Dark)
- **Text**: #ffffff (White)

To change colors, update the CSS custom properties or the specific color values in `styles.css`.

## Browser Compatibility

- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers

## Performance Features

- **Lazy Loading**: Images load as needed
- **Optimized Animations**: Hardware-accelerated CSS animations
- **Throttled Scroll Events**: Smooth performance on scroll
- **Preloaded Images**: Critical images preload for faster display

## Getting Started

1. Open `index.html` in a web browser
2. The website will work locally without a server
3. For production, upload all files to your web hosting service

## Future Enhancements

- Add a blog section
- Include a portfolio filtering system
- Add more interactive animations
- Implement a backend for the contact form
- Add a dark/light theme toggle

## Credits

- **Design & Development**: Custom built for ianmol
- **Images**: Unsplash (placeholders)
- **Icons**: Font Awesome
- **Fonts**: Google Fonts (Inter)

---

**Note**: This is a static website. To make the contact form functional, you'll need to integrate it with a backend service or form handling solution like Formspree, Netlify Forms, or EmailJS.

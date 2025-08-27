# Game Developer Portfolio

A modern, responsive portfolio website designed specifically for game developers. Features a sleek design with gaming-inspired aesthetics, smooth animations, and comprehensive sections to showcase your projects and skills.

## 🎮 Features

- **Responsive Design** - Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX** - Gaming-inspired design with neon accents and smooth animations
- **Project Showcase** - Dedicated section to display your games with tech stack tags
- **Skills Visualization** - Interactive skill bars showing your expertise levels
- **Contact Form** - Functional contact form with validation
- **Smooth Animations** - CSS animations and JavaScript interactions
- **SEO Optimized** - Clean HTML structure for better search engine visibility

## 🚀 Getting Started

### Prerequisites
- A modern web browser
- Basic knowledge of HTML, CSS, and JavaScript (for customization)

### Installation
1. Download or clone this repository
2. Open `index.html` in your web browser
3. Start customizing the content for your portfolio

## 📝 Customization Guide

### Personal Information
Edit the following sections in `index.html`:

#### Hero Section
```html
<h1 class="hero-title">
    <span class="title-line">Your Name</span>
    <span class="title-line">Game Developer</span>
</h1>
<p class="hero-subtitle">Your tagline or brief description</p>
```

#### About Section
```html
<p class="about-description">
    Your personal story and experience in game development
</p>
```

#### Contact Information
```html
<div class="contact-item">
    <i class="fas fa-envelope"></i>
    <span>your.email@example.com</span>
</div>
<div class="contact-item">
    <i class="fas fa-phone"></i>
    <span>Your Phone Number</span>
</div>
```

### Projects
Replace the project cards in the Projects section with your own games:

```html
<div class="project-card">
    <div class="project-image">
        <!-- Add your game screenshot here -->
        <img src="path/to/your/game-image.jpg" alt="Game Name">
    </div>
    <div class="project-content">
        <h3 class="project-title">Your Game Name</h3>
        <p class="project-description">Description of your game</p>
        <div class="project-tech">
            <span class="tech-tag">Unity</span>
            <span class="tech-tag">C#</span>
        </div>
        <div class="project-links">
            <a href="your-demo-link" class="project-link">Play Demo</a>
            <a href="your-code-link" class="project-link">View Code</a>
        </div>
    </div>
</div>
```

### Skills
Update the skills section to reflect your expertise:

```html
<div class="skill-item">
    <div class="skill-name">Your Skill</div>
    <div class="skill-bar">
        <div class="skill-progress" style="width: 85%"></div>
    </div>
</div>
```

### Social Links
Update the social media links in the contact section:

```html
<div class="social-links">
    <a href="your-github" class="social-link"><i class="fab fa-github"></i></a>
    <a href="your-linkedin" class="social-link"><i class="fab fa-linkedin"></i></a>
    <a href="your-twitter" class="social-link"><i class="fab fa-twitter"></i></a>
    <a href="your-youtube" class="social-link"><i class="fab fa-youtube"></i></a>
</div>
```

## 🎨 Styling Customization

### Colors
The main color scheme uses neon green (#00ff88) and blue (#00d4ff). You can change these in `styles.css`:

```css
:root {
    --primary-color: #00ff88;
    --secondary-color: #00d4ff;
    --background-dark: #0a0a0a;
    --background-light: #111;
}
```

### Fonts
The portfolio uses:
- **Orbitron** for headings (gaming-style font)
- **Roboto** for body text

You can change fonts by updating the Google Fonts link in the HTML head section.

### Animations
Customize animations by modifying the CSS keyframes in `styles.css`:

```css
@keyframes rotate {
    0% { transform: rotateX(0deg) rotateY(0deg); }
    100% { transform: rotateX(360deg) rotateY(360deg); }
}
```

## 📱 Responsive Design

The portfolio is fully responsive with breakpoints at:
- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

## 🔧 Advanced Customization

### Adding New Sections
To add a new section, follow this structure:

```html
<section id="your-section" class="your-section">
    <div class="container">
        <h2 class="section-title">Your Section Title</h2>
        <!-- Your content here -->
    </div>
</section>
```

### Custom Animations
Add custom CSS animations:

```css
@keyframes yourAnimation {
    0% { /* initial state */ }
    100% { /* final state */ }
}

.your-element {
    animation: yourAnimation 2s ease infinite;
}
```

### JavaScript Functionality
Add custom JavaScript in `script.js`:

```javascript
// Your custom functionality
document.addEventListener('DOMContentLoaded', () => {
    // Your code here
});
```

## 🌐 Deployment

### GitHub Pages
1. Push your code to a GitHub repository
2. Go to Settings > Pages
3. Select your main branch as source
4. Your portfolio will be available at `https://username.github.io/repository-name`

### Netlify
1. Drag and drop your project folder to Netlify
2. Your site will be deployed automatically
3. You'll get a custom URL

### Vercel
1. Connect your GitHub repository to Vercel
2. Deploy automatically on every push
3. Get a custom domain and SSL certificate

## 📊 Performance Optimization

- Images are optimized for web
- CSS and JavaScript are minified
- Lazy loading for better performance
- Smooth scrolling and animations

## 🔍 SEO Optimization

- Semantic HTML structure
- Meta tags for social sharing
- Clean URLs and navigation
- Fast loading times

## 🛠️ Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this project and customize it for your needs. If you make improvements, consider sharing them with the community!

## 📞 Support

If you need help customizing your portfolio or have questions, feel free to reach out!

---

**Happy Game Developing! 🎮** 
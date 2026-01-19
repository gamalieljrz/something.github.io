# Isaac's Portfolio Website

A modern, responsive personal portfolio website showcasing projects, achievements, and professional experience.

## 🌟 Features

- **Responsive Design**: Fully responsive layout that works on desktop, tablet, and mobile devices
- **Dark/Light Theme**: Toggle between dark and light themes with persistent preference storage
- **Smooth Animations**: Elegant fade-in animations and smooth scrolling for better user experience
- **Interactive Components**: 
  - Mobile-friendly navigation menu
  - Interactive project cards with hover effects
  - Animated statistics counters
  - Contact form with validation
- **SEO Optimized**: Semantic HTML5 structure with proper meta tags
- **Performance**: Zero dependencies, vanilla JavaScript for fast loading

## 🚀 Quick Start

Simply open `index.html` in your browser or deploy to GitHub Pages:

1. **Local Development**: 
   ```bash
   # Open directly in browser
   open index.html
   ```

2. **GitHub Pages Deployment**:
   - Push to the `main` branch
   - Go to repository Settings → Pages
   - Select `main` branch as source
   - Your site will be live at `https://gamalieljrz.github.io/something.github.io/`

## 📁 Project Structure

```
.
├── index.html      # Main HTML structure with all content
├── styles.css      # CSS with theme variables and responsive design
├── script.js       # JavaScript for interactivity and animations
├── README.md       # This file
└── LICENSE         # MIT License
```

## 🎨 Customization

### Updating Personal Information

Edit `index.html` to customize:
- **Hero Section**: Update name, title, and description
- **About Section**: Modify bio, skills, and statistics
- **Projects**: Add/remove/edit project cards with your actual projects
- **Achievements**: Customize achievements and awards
- **Contact**: Update email and social media links

### Styling

The `styles.css` file uses CSS variables for easy theming:

```css
:root {
    --accent-primary: #2563eb;    /* Main accent color */
    --accent-secondary: #1e40af;  /* Secondary accent */
    /* ... more variables */
}
```

### Adding New Sections

Follow the existing section structure:

```html
<section id="your-section" class="your-section">
    <div class="container">
        <h2 class="section-title">Section Title</h2>
        <!-- Your content -->
    </div>
</section>
```

## 🎯 Interactive Features

- **Theme Toggle**: Click the sun/moon icon to switch themes
- **Mobile Menu**: Hamburger menu for mobile navigation
- **Smooth Scrolling**: Navigation links smoothly scroll to sections
- **Form Submission**: Contact form (requires backend integration)
- **Easter Egg**: Try the Konami code (↑↑↓↓←→←→BA)

## 🛠️ Tech Stack

- **HTML5**: Semantic markup
- **CSS3**: Modern features (Grid, Flexbox, Variables, Animations)
- **Vanilla JavaScript**: No frameworks, pure ES6+
- **Google Fonts**: Inter font family

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔧 Backend Integration

The contact form currently simulates submission. To integrate with a backend:

1. Replace the `simulateFormSubmission` function in `script.js`
2. Use a service like Formspree, EmailJS, or your own API
3. Example with Formspree:

```javascript
async function submitForm(data) {
    const response = await fetch('https://formspree.io/f/YOUR_FORM_ID', {
        method: 'POST',
        headers: { 'Content-Type': 'application/json' },
        body: JSON.stringify(data)
    });
    return response.json();
}
```

## 📊 Dummy Data

The site includes comprehensive dummy data:
- **8 Featured Projects** with diverse tech stacks
- **8 Achievement Cards** covering awards, certifications, and milestones
- **4 Statistics** showing experience metrics
- **Rich Bio** with professional description
- **12 Skill Tags** showcasing technical expertise

## 🎓 Learning Resources

This portfolio demonstrates:
- Modern CSS layouts (Grid, Flexbox)
- CSS custom properties for theming
- Intersection Observer API for animations
- Local Storage API for theme persistence
- Form handling and validation
- Responsive design best practices

## 📝 License

MIT License - feel free to use this template for your own portfolio!

## 🤝 Contributing

This is a personal portfolio template, but suggestions and improvements are welcome!

## 📧 Contact

- GitHub: [@gamalieljrz](https://github.com/gamalieljrz)
- Website: [gamalieljrz.github.io/something.github.io](https://gamalieljrz.github.io/something.github.io)

---

Built with 💙 and ☕ by Isaac

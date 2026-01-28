# Ritanshu Choudhary - Flutter Developer Portfolio

A modern, high-performance personal portfolio website showcasing professional Flutter development expertise.

## 🎨 Features

- **Dark Theme with Neon Accents**: Stunning dark mode with electric blue and purple gradient accents
- **Smooth Animations**: Scroll-triggered animations, typing effects, and micro-interactions
- **Glassmorphism Design**: Modern glass-effect cards with backdrop blur
- **Responsive Design**: Mobile-first approach, works perfectly on all devices
- **Performance Optimized**: Vanilla HTML/CSS/JS for maximum speed
- **SEO Optimized**: Proper meta tags, semantic HTML, and heading structure

## 🚀 Quick Start

### View Locally

1. Open `index.html` in any modern web browser
2. Or use a local server for best experience:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

Then navigate to `http://localhost:8000`

## 📁 File Structure

```
profilo_ritanshu/
├── index.html      # Main HTML structure
├── style.css       # All styles and animations
├── script.js       # Interactive functionality
└── README.md       # This file
```

## 🎯 Sections

1. **Hero Section**: Dynamic introduction with typing animation and stats
2. **About Section**: Professional summary and personal information
3. **Skills Section**: Categorized technical skills with icons
4. **Experience Section**: Timeline of professional journey
5. **Projects Section**: Featured projects with tech stacks and links
6. **Contact Section**: Contact form and direct communication methods

## 🛠 Technologies Used

- **HTML5**: Semantic structure
- **CSS3**: Custom properties, Grid, Flexbox, animations
- **JavaScript**: Vanilla JS for interactions
- **Font Awesome**: Icons
- **Google Fonts**: Inter font family

## 🎨 Design System

### Colors
- Background Primary: `#0a0a0f`
- Background Secondary: `#111118`
- Accent Primary (Neon Blue): `#00d4ff`
- Accent Secondary (Purple): `#a855f7`
- Text Primary: `#ffffff`
- Text Secondary: `#b4b4b8`

### Typography
- Font Family: Inter
- Responsive font sizes using clamp()
- Font weights: 300, 400, 500, 600, 700, 800

## 📱 Responsive Breakpoints

- Desktop: > 968px
- Tablet: 640px - 968px
- Mobile: < 640px

## ✨ Interactive Features

- **Typing Animation**: Auto-rotating role titles
- **Smooth Scroll**: Navigation with smooth scrolling
- **Scroll Animations**: Fade-in effects on scroll
- **Parallax Effect**: Mouse-following gradient orbs
- **Card Tilt**: 3D tilt effect on project cards
- **Counter Animation**: Animated statistics
- **Form Validation**: Contact form with mailto integration

## 🚀 Deployment Options

### GitHub Pages
1. Create a new repository on GitHub
2. Push these files to the repository
3. Go to Settings > Pages
4. Select main branch as source
5. Your site will be live at `https://yourusername.github.io/repo-name`

### Netlify
1. Drag and drop the folder to [Netlify Drop](https://app.netlify.com/drop)
2. Or connect your GitHub repository for automatic deployments

### Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in the project directory
3. Follow the prompts

### Custom Domain
After deploying to any platform above, you can connect a custom domain through the platform's settings.

## 📝 Customization

### Update Personal Information
Edit `index.html` and update:
- Contact details
- Professional summary
- Experience details
- Project information

### Change Colors
Edit `style.css` and modify CSS custom properties in the `:root` section:
```css
:root {
    --accent-primary: #00d4ff;  /* Change to your preferred color */
    --accent-secondary: #a855f7; /* Change to your preferred color */
}
```

### Add Projects
Add new project cards in the `projects-grid` section of `index.html`

### Modify Typing Animation
Edit the `roles` array in `script.js`:
```javascript
const roles = [
    'Your Role 1',
    'Your Role 2',
    // Add more roles
];
```

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📄 License

This portfolio is created for Ritanshu Choudhary. Feel free to use it as inspiration for your own portfolio.

## 📧 Contact

- **Email**: ritanshu97@gmail.com
- **Phone**: +91-8219815609
- **GitHub**: [@RitanshuChoudhary](https://github.com/RitanshuChoudhary)
- **Location**: Chandigarh (Mohali), India

---

Built with ❤️ using HTML, CSS, and JavaScript

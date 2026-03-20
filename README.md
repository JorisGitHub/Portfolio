# Joris Gueriot | Portfolio

A modern, responsive personal portfolio website showcasing professional experience, skills, and achievements as a Technical Support Specialist.

## 🎯 Overview

This portfolio website is designed to present a professional online presence with a clean, modern design. It features a card-based layout with smooth interactions and built-in dark/light theme support that adapts to system preferences.

**Live Profile:** [Connect on LinkedIn](https://www.linkedin.com/in/joris-gueriot-922792221)

## ✨ Features

- **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- **Dark/Light Theme Toggle** - Automatically adapts to system preferences with manual override option
- **Modern UI** - Clean card-based layout with smooth transitions and hover effects
- **Smooth Animations** - Subtle hover effects and transitions for better user experience
- **SEO Friendly** - Proper HTML semantic structure for better search engine visibility
- **Fast Loading** - Lightweight CSS with minimal JavaScript for optimal performance

## 📁 Project Structure

```
Portfolio Folder/
├── Portfolio.html          # Main HTML file with portfolio content
├── styles.css              # Stylesheet with theme variables
├── README.md               # This file
└── resume.pdf              # Resume document (referenced in portfolio)
```

## 🛠 Technologies Used

- **HTML5** - Semantic markup structure
- **CSS3** - Including:
  - CSS Variables for dynamic theming
  - Flexbox for layout
  - Media queries for responsive design
  - CSS transitions for smooth animations
- **Vanilla JavaScript** - Lightweight theme management without external dependencies

## 🎨 Color Scheme

### Dark Theme (Default)
- Background: `#0f172a` to `#1e293b`
- Text: `#f1f5f9`
- Accent: `#38bdf8`

### Light Theme
- Background: `#f8fafc` to `#f1f5f9`
- Text: `#0f172a`
- Accent: `#0284c7`

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No build tools or dependencies required

### How to Use

1. **Open locally** - Download all files to a folder
   ```
   - Extract all files to a directory
   - Open Portfolio.html in your web browser
   ```

2. **Deploy online** - Upload files to a web hosting service:
   - [GitHub Pages](https://pages.github.com/)
   - [Netlify](https://www.netlify.com/)
   - [Vercel](https://vercel.com/)
   - Any standard web host

### File Structure Recommendations

```
project-root/
├── index.html          (rename from Portfolio.html)
├── styles.css
├── resume.pdf
└── README.md
```

## 🎨 Customization

### Updating Content

Edit `Portfolio.html` to change:
- Name and tagline
- About Me section
- Skills list
- LinkedIn profile URL
- Resume file path

### Modifying Colors

Edit `styles.css` CSS variables at the top:

```css
:root {
  --bg-primary: #0f172a;      /* Main background */
  --accent: #38bdf8;           /* Highlight color */
  /* ... other variables */
}

@media (prefers-color-scheme: light) {
  :root {
    --bg-primary: #f8fafc;     /* Light mode background */
    --accent: #0284c7;         /* Light mode accent */
  }
}
```

### Adding Theme Toggle Button

Add a button to your HTML to manually toggle themes:

```html
<button onclick="toggleTheme()" style="position: fixed; top: 10px; right: 10px;">
    🌙 Toggle Theme
</button>
```

The `toggleTheme()` function is already included in the JavaScript.

## 🌓 Theme System

The portfolio automatically detects your system's color scheme preference:

- **Auto** - Follows system preference (default)
- **Dark** - Force dark theme
- **Light** - Force light theme

User preference is saved to browser localStorage and persists across sessions.

```javascript
// Manually toggle theme
toggleTheme();

// Check current theme
const currentTheme = document.documentElement.getAttribute('data-theme');
```

## 📱 Responsive Breakpoints

The design is optimized for:
- **Desktop** - 1200px and above
- **Tablet** - 768px to 1199px
- **Mobile** - Below 768px

## 📋 Content Sections

### Header
- Name and professional tagline

### About Me
- Professional background
- Key competencies
- Work experience summary

### Currently Looking For
- Job search status
- Career goals and interests

### Skills
- Grid layout of professional skills and technologies
- Categories: Customer Support, Technical, Cloud, Languages

### Connect with Me
- LinkedIn profile link
- Resume download
- Call-to-action buttons

### Footer
- Copyright information

## 🔧 Browser Support

- Chrome/Edge 90+
- Firefox 87+
- Safari 14+
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📝 License

This portfolio is personal work. Feel free to use it as inspiration for your own portfolio.

## 📧 Contact

- **LinkedIn:** [Joris Gueriot](https://www.linkedin.com/in/joris-gueriot-922792221)
- **Location:** Dublin, Ireland
- **Specialization:** Customer Support | Technical Troubleshooting | Cloud Technologies

## 🎯 Key Skills

- Customer Support Specialist
- Technical Troubleshooting
- Microsoft 365 & Azure
- Python Programming
- Cross-platform OS knowledge
- Cybersecurity Awareness
- Multilingual Support (French, English, Spanish)

---

**Last Updated:** March 2026

**Version:** 1.0

# Matteo Jin - Personal Portfolio

A modern, responsive personal portfolio website built with HTML, CSS, and JavaScript. This site showcases projects, skills, and provides a way to get in touch.

![Portfolio Preview](https://via.placeholder.com/800x400/2563eb/ffffff?text=Portfolio+Preview)

## 🚀 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Interactive Elements**: Smooth scrolling, mobile menu, and hover effects
- **Fast Loading**: Optimized for performance with minimal dependencies
- **SEO Friendly**: Proper meta tags and semantic HTML structure
- **GitHub Pages Ready**: Easy deployment to GitHub Pages

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with CSS Grid and Flexbox
- **JavaScript (ES6+)**: Interactive functionality and animations
- **Google Fonts**: Inter font family for modern typography
- **Font Awesome**: Icons for social links and UI elements

## 📁 Project Structure

```
matteojin.github.io/
├── index.html              # Main HTML file
├── README.md               # Project documentation
└── assets/
    ├── css/
    │   └── style.css       # Main stylesheet
    └── js/
        └── main.js         # JavaScript functionality
```

## 🚀 Getting Started

### Prerequisites

- A GitHub account
- Basic knowledge of HTML/CSS/JavaScript (optional for customization)

### Local Development

1. **Clone the repository:**
   ```bash
   git clone https://github.com/matteojin/matteojin.github.io.git
   cd matteojin.github.io
   ```

2. **Open in browser:**
   - Simply open `index.html` in your web browser
   - Or use a local server for better development experience:
     ```bash
     # Using Python
     python -m http.server 8000

     # Using Node.js (if you have http-server installed)
     npx http-server
     ```

3. **Make changes:**
   - Edit `index.html` to update content
   - Modify `assets/css/style.css` for styling changes
   - Update `assets/js/main.js` for functionality changes

### Deployment to GitHub Pages

This repository is already configured for GitHub Pages deployment. Here's how it works:

1. **Automatic Deployment:**
   - GitHub Pages automatically deploys from the `main` branch
   - Your site will be available at `https://matteojin.github.io`

2. **Custom Domain (Optional):**
   - Add a `CNAME` file to the root directory with your custom domain
   - Update your DNS settings to point to GitHub Pages

## 🎨 Customization

### Personal Information

Edit the following sections in `index.html`:

- **Hero Section**: Update name, title, and description
- **About Section**: Add your personal story and skills
- **Projects Section**: Replace placeholder projects with your actual work
- **Contact Section**: Update email, social links, and contact information

### Styling

Modify `assets/css/style.css` to:

- Change color scheme (update CSS custom properties in `:root`)
- Adjust spacing and typography
- Modify animations and transitions
- Customize responsive breakpoints

### Colors

The site uses CSS custom properties for easy color customization:

```css
:root {
    --primary-color: #2563eb;    /* Main blue */
    --accent-color: #f59e0b;     /* Accent yellow */
    --text-dark: #1f2937;        /* Dark text */
    --bg-light: #f8fafc;         /* Light background */
}
```

## 📱 Features in Detail

### Navigation
- Fixed header with smooth scroll navigation
- Mobile-responsive hamburger menu
- Active section highlighting

### Animations
- Fade-in animations on scroll
- Typing effect in hero section
- Smooth hover transitions
- Loading animation

### Responsive Design
- Mobile-first approach
- Flexible grid layouts
- Optimized touch interactions
- Readable typography across devices

## 🔧 Development

### Adding New Sections

1. Add HTML structure to `index.html`
2. Add corresponding CSS styles to `style.css`
3. Update navigation links if needed
4. Add JavaScript functionality to `main.js` if required

### Performance Optimization

- Minimize CSS and JavaScript files
- Optimize images (if added)
- Use semantic HTML for better SEO
- Enable compression on your server

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this repository and customize it for your own use. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## 📞 Contact

- **Email**: your.email@example.com
- **GitHub**: [matteojin](https://github.com/matteojin)
- **LinkedIn**: [Your LinkedIn Profile](https://linkedin.com/in/yourprofile)

---

**Built with ❤️ by Matteo Jin**

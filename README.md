# Chinwe Martins - Portfolio Website

A clean, responsive personal portfolio website showcasing frontend development skills and projects. Built with pure HTML, CSS, and JavaScript to demonstrate foundational web development capabilities.

## 🌐 Live Demo

**[View Live Website](https://chinwemartins02.github.io/portfoliowebsite/)**

## 📋 Table of Contents

- [About the Project](#about-the-project)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Installation & Setup](#installation--setup)
- [Usage](#usage)
- [Sections Overview](#sections-overview)
- [Customization Guide](#customization-guide)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [Contact](#contact)
- [License](#license)

## 🎯 About the Project

This portfolio website serves as a professional showcase for Chinwe Martins, a frontend developer with a background in Biochemistry. The site demonstrates clean coding practices, responsive design principles, and modern web development techniques using only vanilla HTML, CSS, and JavaScript.

### Why This Project?

- **Demonstrates core web development skills** without relying on frameworks
- **Showcases responsive design** that works across all devices
- **Provides a professional online presence** for career opportunities
- **Serves as a template** for other developers creating their portfolios

## ✨ Features

- **📱 Fully Responsive Design** - Works seamlessly on desktop, tablet, and mobile
- **🎨 Modern UI/UX** - Clean, professional design with smooth animations
- **⚡ Fast Loading** - Optimized vanilla code without heavy frameworks
- **📧 Contact Integration** - Direct WhatsApp messaging functionality
- **📄 CV Download** - Easy access to downloadable resume
- **🔗 Project Showcases** - Live links to deployed projects
- **🎯 Smooth Navigation** - Anchor-based single-page navigation
- **🌙 Cross-browser Compatible** - Works across all modern browsers

## 🛠 Technologies Used

- **HTML5** - Semantic markup and structure
- **CSS3** - Styling, animations, and responsive design
- **GitHub Pages** - Free hosting and deployment

## 📁 Project Structure

```
portfolio/
├── index.html              # Main HTML file
├── styles.css              # Main stylesheet
├── assets/                 # Images and documents
│   ├── Chinwe Martins.png  # Profile picture
│   └── MARTINS CHINWE.docx # Downloadable CV
└── README.md              # Project documentation
```

## 🚀 Installation & Setup

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Text editor (VS Code, Sublime Text, Atom, etc.)
- Git (for cloning and version control)

### Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/chinwemartins02/portfolio.git
   ```

2. **Navigate to project directory**
   ```bash
   cd portfolio
   ```

3. **Open in browser**
   - Double-click `index.html`, or
   - Use Live Server extension in VS Code, or
   - Run a local server:
   

4. **View in browser**
   Open `http://localhost:3000` in your browser

## 💻 Usage

### For Viewing

Simply visit the [live website](https://chinwemartins02.github.io/portfolio/) or open `index.html` in any modern web browser.

### For Development

1. Open the project in your preferred code editor
2. Make changes to HTML, CSS, or add JavaScript functionality
3. Refresh the browser to see changes
4. Use browser developer tools for debugging

### Key Files to Modify

- **`index.html`** - Update content, add new sections, modify structure
- **`styles.css`** - Change colors, fonts, layout, add animations
- **`assets/`** - Replace images, update CV document

## 📄 Sections Overview

### 🏠 Hero Section
- **Purpose**: First impression with name and role
- **Features**: Call-to-action button, clean typography
- **Customization**: Update name, title, and CTA text

### 👤 About Section
- **Purpose**: Personal introduction and skills showcase
- **Features**: Profile image, bio, skills tags
- **Customization**: Replace image, update bio, modify skills

### 🎓 Education Section
- **Purpose**: Academic background and training
- **Features**: Timeline layout, downloadable CV
- **Customization**: Add/remove education items, update CV link

### 💡 Interests Section
- **Purpose**: Showcase passions and motivations
- **Features**: Icon-based cards, hover effects
- **Customization**: Update interests, change icons, modify descriptions

### 🚀 Projects Section
- **Purpose**: Display portfolio work with live links
- **Features**: Project cards, technology tags, external links
- **Customization**: Add new projects, update links, modify descriptions

### 📧 Contact Section
- **Purpose**: Enable visitors to get in touch
- **Features**: WhatsApp integration, contact form layout
- **Customization**: Update WhatsApp number, modify contact methods

## 🎨 Customization Guide

### Changing Colors

The main color scheme is defined in CSS variables. Update these in `styles.css`:

```css
:root {
  --primary-color: #8b5cf6;     /* Purple accent */
  --text-color: #333;           /* Dark text */
  --bg-color: #ffffff;          /* Background */
  --section-bg: #f8fafc;        /* Section background */
}
```

### Adding New Sections

1. Add HTML structure in `index.html`:
```html
<section id="new-section" class="section">
  <div class="container">
    <h2 class="section-title">New Section</h2>
    <!-- Your content here -->
  </div>
</section>
```

2. Add navigation link:
```html
<li><a href="#new-section">New Section</a></li>
```

3. Style in `styles.css`:
```css
#new-section {
  /* Your styles here */
}
```

### Updating Content

- **Profile Image**: Replace `assets/Chinwe Martins.png`
- **CV Document**: Replace `assets/MARTINS CHINWE.docx`
- **WhatsApp Number**: Update the number in the WhatsApp link
- **Social Links**: Add your social media links in the contact section

## 🌐 Deployment

### GitHub Pages (Current Method)

1. **Push to GitHub**
   ```bash
   git add .
   git commit -m "Update portfolio"
   git push origin main
   ```

2. **Enable GitHub Pages**
   - Go to repository Settings
   - Scroll to Pages section
   - Select source branch (usually `main`)
   - Site will be available at `https://yourusername.github.io/repository-name/`

### Alternative Deployment Options

- **Netlify**: Drag and drop the folder or connect GitHub repo
- **Vercel**: Import GitHub repository
- **GitHub Codespaces**: Use for development and preview
- **Local Server**: For testing and development

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Here's how you can contribute:

### For Bug Reports
1. Check existing issues first
2. Create a new issue with detailed description
3. Include browser info and steps to reproduce

### For Feature Requests
1. Open an issue describing the feature
2. Explain why it would be useful
3. Provide examples if possible

### For Code Contributions
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Test thoroughly across different browsers
5. Commit changes (`git commit -m 'Add some amazing feature'`)
6. Push to branch (`git push origin feature/amazing-feature`)
7. Open a Pull Request

### Development Guidelines
- Keep code clean and well-commented
- Follow existing code style and structure
- Test on multiple browsers and devices
- Ensure responsive design is maintained
- Optimize images and assets

## 📞 Contact

**Chinwe Martins**
- **WhatsApp**: [+234 817 604 2780](https://wa.me/2348176042780)
- **GitHub**: [@chinwemartins02](https://github.com/chinwemartins02)
- **Portfolio**: [chinwemartins02.github.io/portfolio](https://chinwemartins02.github.io/portfolio/)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🎉 Acknowledgments

- **New Horizons ICT Institute** - For frontend development training
- **University of Nigeria, Nsukka** - For foundational analytical skills
- **GitHub Pages** - For free hosting
- **Open Source Community** - For inspiration and resources

---

**Built with ❤️ and lots of ☕ by Chinwe Martins**

*Last Updated: July 2025*

# Rohan's Portfolio Website

A modern, responsive personal portfolio website built with HTML, CSS, and JavaScript, featuring Tailwind CSS for styling and smooth animations.

## 🚀 Features

- **Fully Responsive Design** - Works perfectly on mobile, tablet, and desktop
- **Modern UI/UX** - Clean, minimal design with soft colors and rounded corners
- **Smooth Animations** - Scroll-triggered animations and hover effects
- **Interactive Components** - Mobile menu, smooth scrolling, and form validation
- **Performance Optimized** - Debounced scroll events and lazy loading support
- **Accessibility Focused** - ARIA labels, keyboard navigation, and screen reader support

## 🛠️ Technologies Used

- **HTML5** - Semantic markup and structure
- **CSS3** - Custom styling with Tailwind CSS framework
- **JavaScript (ES6+)** - Interactive functionality and animations
- **Tailwind CSS** - Utility-first CSS framework for rapid development
- **Font Awesome** - Icon library for visual elements

## 📁 Project Structure

```
portfolio-website/
├── index.html          # Main HTML file
├── styles.css          # Custom CSS styles
├── script.js           # JavaScript functionality
├── README.md           # Project documentation
├── assets/             # Asset folder
│   ├── images/         # Image files (add your photos here)
│   ├── icons/          # Custom icons (if needed)
│   └── documents/      # Resume and other documents
└── .gitignore          # Git ignore file
```

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic knowledge of HTML, CSS, and JavaScript (for customization)

### Installation

1. **Clone or Download** the project files to your local machine
2. **Open** `index.html` in your web browser
3. **Customize** the content, images, and styling as needed

### Current Status
✅ **Portfolio website is complete and functional**
✅ **Resume download is working**
✅ **All sections are responsive and animated**
🔄 **Contact form needs Formspree setup**
🔄 **Add your actual photos and project images**

### Local Development

For development purposes, you can use any local server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have it installed)
npx serve .

# Using PHP
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

## 🎨 Customization Guide

### 1. Personal Information
Edit the following sections in `index.html`:
- **Hero Section**: Update name, title, and description
- **About Section**: Modify your background and experience
- **Skills**: Adjust skill levels and add/remove skills
- **Projects**: Replace with your actual projects
- **Contact**: Update email, social media links

### 2. Images and Assets
- **Profile Images**: Replace placeholder icons with your photos
- **Project Images**: Add screenshots or images of your projects
- **Resume**: ✅ Resume is already added and the download button is functional

### 3. Colors and Styling
The website uses a custom color palette defined in the HTML:
- **Primary**: #2563EB (Blue)
- **Secondary**: #1E293B (Dark Slate)
- **Accent**: #64748B (Gray)
- **Light**: #F8FAFC (Off-white)
- **Soft**: #E2E8F0 (Light Gray)

### 4. Contact Form
The contact form is currently set up with a placeholder Formspree endpoint. To make it functional:

1. Sign up at [Formspree](https://formspree.io/)
2. Create a new form
3. Replace `your-form-id` in the form action with your actual form ID

### 5. Resume Download
✅ **Resume download is now functional!** The button links to `assets/documents/Rohan Kailash B_Resume.pdf`

## 📱 Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## 🔧 JavaScript Features

### Core Functionality
- **Mobile Menu**: Responsive navigation with smooth animations
- **Smooth Scrolling**: Animated navigation between sections
- **Scroll Animations**: Elements animate in as they come into view
- **Skill Bar Animation**: Animated progress bars for skills
- **Form Validation**: Client-side form validation with notifications
- **Back to Top**: Smooth scroll to top button

### Performance Features
- **Debounced Scroll Events**: Optimized scroll performance
- **Intersection Observer**: Efficient scroll animation detection
- **Lazy Loading**: Support for lazy loading images (when implemented)

## 🎯 Browser Support

- **Modern Browsers**: Chrome 60+, Firefox 55+, Safari 12+, Edge 79+
- **Mobile Browsers**: iOS Safari 12+, Chrome Mobile 60+
- **Fallbacks**: Graceful degradation for older browsers

## 📝 Customization Examples

### Adding a New Skill
```html
<div class="skill-item">
    <span class="skill-name">New Skill</span>
    <div class="skill-bar">
        <div class="skill-progress" style="width: 85%"></div>
    </div>
</div>
```

### Adding a New Project
```html
<div class="project-card group">
    <div class="project-image">
        <img src="assets/images/project-image.jpg" alt="Project Name" class="w-full h-48 object-cover rounded-t-xl">
        <div class="project-overlay">
            <a href="https://github.com/yourusername/project" class="btn-primary">
                <i class="fab fa-github mr-2"></i>
                View Code
            </a>
        </div>
    </div>
    <div class="project-content">
        <h3 class="text-xl font-semibold text-secondary mb-2">Project Name</h3>
        <p class="text-gray-600 mb-4">Project description goes here.</p>
        <div class="flex flex-wrap gap-2">
            <span class="tech-tag">Technology</span>
        </div>
    </div>
</div>
```

## 🚀 Deployment

### GitHub Pages
1. Push your code to a GitHub repository
2. Go to Settings > Pages
3. Select source branch (usually `main` or `master`)
4. Your site will be available at `https://username.github.io/repository-name`

### Netlify
1. Drag and drop your project folder to [Netlify](https://netlify.com)
2. Your site will be deployed automatically
3. Custom domain can be configured in the dashboard

### Vercel
1. Connect your GitHub repository to [Vercel](https://vercel.com)
2. Automatic deployments on every push
3. Custom domain and SSL included

## 🐛 Troubleshooting

### Common Issues

**Form not working**: Check that you've updated the Formspree endpoint
**Images not loading**: Ensure image paths are correct and files exist
**Mobile menu not working**: Check that all JavaScript files are loaded
**Styling issues**: Verify Tailwind CSS CDN is accessible

### Debug Mode
Open browser console (F12) to see any JavaScript errors or debug information.

## 🤝 Contributing

Feel free to fork this project and customize it for your own portfolio. If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- **Tailwind CSS** for the utility-first CSS framework
- **Font Awesome** for the comprehensive icon library
- **Google Fonts** for the Inter font family
- **Formspree** for the contact form service

## 📞 Support

If you need help customizing this portfolio or have questions about the implementation, feel free to reach out through the contact form on the website.

---

**Built with ❤️ by Rohan**


*Last updated: September 2025* 

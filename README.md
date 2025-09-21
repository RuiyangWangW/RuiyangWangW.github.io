# Ruiyang Wang - Academic Website

A modern, responsive personal website designed for academic researchers and PhD students in robotics. Perfect for showcasing research, projects, and professional achievements to potential employers and collaborators.

## 🚀 Features

- **Responsive Design**: Looks great on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Academic Focus**: Sections specifically designed for researchers
- **SEO Optimized**: Structured for search engine visibility
- **Fast Loading**: Optimized performance with modern web standards
- **Contact Form**: Built-in contact form with validation
- **Social Media Integration**: Links to professional profiles

## 📂 Structure

```
ruiyang_wang_website/
├── index.html              # Main website file
├── css/
│   └── style.css           # All styling and responsive design
├── js/
│   └── script.js           # Interactive features and animations
├── images/                 # Your photos and project images
├── assets/
│   └── Ruiyang_Wang_CV.pdf # Your CV/Resume (add your own)
└── README.md              # This file
```

## 🛠️ Setup Instructions

### 1. Quick Start
1. Download all files to your computer
2. Open `index.html` in a web browser to preview
3. Edit the content to match your information
4. Upload to a web hosting service

### 2. Customization

#### Personal Information
Edit `index.html` and replace the following placeholders:

- **Name**: Replace "Ruiyang Wang" with your name
- **University**: Update university and department information
- **Email**: Change email addresses to your own
- **Social Media**: Update LinkedIn, GitHub, and other profile links
- **Location**: Update your location in the contact section

#### Content Sections

**About Section**: 
- Update your research interests
- Modify technical skills
- Adjust the statistics (years PhD, projects, publications, etc.)

**Research Section**:
- Replace with your actual publications
- Add links to papers, code repositories, and demos
- Update conference names and years

**Projects Section**:
- Showcase your actual projects
- Add real project descriptions
- Include technology stacks you've used
- Link to GitHub repositories and live demos

**CV Section**:
- Update education history
- Add your work experience
- Include awards and honors
- Replace the CV PDF with your actual resume

#### Styling
- Colors can be changed in `css/style.css`
- The main theme uses a blue-purple gradient (`#667eea` to `#764ba2`)
- Fonts are loaded from Google Fonts (Inter family)

### 3. Adding Your Photos

#### Profile Photo
1. Add your professional photo to the `images/` folder
2. Replace the placeholder in the hero section:
   ```html
   <div class="hero-image">
       <img src="images/your-photo.jpg" alt="Ruiyang Wang">
   </div>
   ```

#### Project Images
1. Add project screenshots to the `images/` folder
2. Replace the icon placeholders in project cards:
   ```html
   <div class="project-image">
       <img src="images/project1.jpg" alt="Project Name">
   </div>
   ```

### 4. Adding Your CV
1. Export your CV as a PDF
2. Name it `Ruiyang_Wang_CV.pdf` (or update the link in `index.html`)
3. Place it in the `assets/` folder

## 🌐 Deployment Options

### GitHub Pages (Free)
1. Create a GitHub repository
2. Upload all files
3. Go to repository Settings > Pages
4. Select source branch (usually `main`)
5. Your site will be available at `username.github.io/repository-name`

### Netlify (Free)
1. Create account at netlify.com
2. Drag and drop your website folder
3. Get a free subdomain or connect your custom domain

### Other Options
- **Vercel**: Similar to Netlify, great for static sites
- **GitHub Codespaces**: Edit and preview online
- **Traditional Web Hosting**: Upload via FTP to any web host

## 📱 Mobile Optimization

The website is fully responsive and includes:
- Hamburger menu for mobile navigation
- Flexible grid layouts that adapt to screen size
- Touch-friendly buttons and links
- Optimized text sizes for readability

## 🎨 Customization Tips

### Color Scheme
To change the color scheme, update these CSS variables in `style.css`:
```css
/* Main gradient colors */
--primary-gradient: linear-gradient(135deg, #your-color1 0%, #your-color2 100%);
--primary-color: #your-primary-color;
```

### Typography
The site uses the Inter font family. To change fonts:
1. Update the Google Fonts link in `index.html`
2. Modify the font-family in `style.css`

### Animations
- Scroll animations are handled by Intersection Observer API
- Smooth scrolling is enabled by default
- Hover effects are CSS-based for better performance

## 🔧 Advanced Features

### Contact Form
The contact form includes client-side validation. For server-side processing:
1. Set up a backend service (Node.js, PHP, etc.)
2. Update the form action in `index.html`
3. Or use services like Formspree, Netlify Forms, or EmailJS

### Analytics
To add Google Analytics:
1. Get your tracking ID from Google Analytics
2. Add the tracking code to the `<head>` section of `index.html`

### SEO Optimization
The site includes basic SEO:
- Semantic HTML structure
- Meta descriptions (add your own)
- Proper heading hierarchy
- Alt tags for images (when you add them)

## 📊 Performance Tips

1. **Optimize Images**: Compress photos before uploading
2. **Minimize HTTP Requests**: Combine CSS/JS files if needed
3. **Use CDN**: For production, consider using a CDN for assets
4. **Enable Compression**: Configure gzip on your server

## 🐛 Troubleshooting

### Common Issues
- **Menu not working on mobile**: Check that `script.js` is loading correctly
- **Styling not applied**: Ensure CSS file path is correct in `index.html`
- **Animations not smooth**: Check browser compatibility and GPU acceleration

### Browser Support
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 📄 License

This template is free to use for personal and academic purposes. Feel free to modify and distribute.

## 🤝 Contributing

Found a bug or want to suggest an improvement? Feel free to open an issue or submit a pull request.

## 📞 Support

If you need help customizing your website:
1. Check this README first
2. Search for solutions online
3. Ask for help in web development communities
4. Consider hiring a web developer for complex customizations

---

**Good luck with your academic journey and website! 🎓**

Remember to:
- Keep your content updated
- Add new projects and publications regularly
- Update your CV periodically
- Share your website URL in your email signature and social media profiles
# Portfolio Website with Video Background

A modern, responsive portfolio website built with HTML, CSS, and JavaScript featuring a full-screen video background.

## 🚀 Features

- **Full-screen video background** with overlay
- **Responsive design** that works on all devices
- **Smooth scrolling navigation** with mobile menu
- **Animated skill bars** with progress indicators
- **Interactive project cards** with hover effects
- **Contact form** with validation
- **Typing effect** for hero section
- **Parallax scrolling** effects
- **Modern gradient design** with smooth animations

## 📁 File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
├── README.md           # This file
└── your-video.mp4      # Your video file (add this)
```

## 🛠️ Setup Instructions

### 1. Add Your Video
- Place your video file in the project folder
- Update the video source in `index.html`:
```html
<source src="your-video.mp4" type="video/mp4">
```
- Replace `your-video.mp4` with your actual video filename

### 2. Customize Content

#### Personal Information
Update the following in `index.html`:

**Hero Section:**
```html
<span class="name">Your Name</span>
<p class="hero-subtitle">Your Title</p>
```

**Contact Information:**
```html
<span>your.email@example.com</span>
<span>+1 (555) 123-4567</span>
<span>Your Location</span>
```

**Social Links:**
```html
<a href="your-github-url" class="social-link">
<a href="your-linkedin-url" class="social-link">
<a href="your-twitter-url" class="social-link">
```

#### Skills Section
Update skills and percentages in `index.html`:
```html
<div class="skill-progress" data-width="95"></div>
```

#### Projects Section
Replace the project cards with your own projects:
```html
<div class="project-card">
    <div class="project-content">
        <h3>Your Project Title</h3>
        <p>Your project description</p>
        <div class="project-tech">
            <span>Technology 1</span>
            <span>Technology 2</span>
        </div>
        <div class="project-links">
            <a href="your-github-url">Code</a>
            <a href="your-live-url">Live</a>
        </div>
    </div>
</div>
```

### 3. Customize Colors
Update the color scheme in `styles.css`:

**Primary Colors:**
```css
background: linear-gradient(45deg, #667eea, #764ba2);
```

**Alternative Color Schemes:**
- Blue: `linear-gradient(45deg, #4facfe, #00f2fe)`
- Green: `linear-gradient(45deg, #43e97b, #38f9d7)`
- Purple: `linear-gradient(45deg, #fa709a, #fee140)`
- Orange: `linear-gradient(45deg, #ff9a9e, #fecfef)`

### 4. Run the Website
Simply open `index.html` in your web browser, or use a local server:

**Using Python:**
```bash
python -m http.server 8000
```

**Using Node.js:**
```bash
npx serve .
```

## 🎨 Customization Options

### Video Background Settings
- **Autoplay**: Video starts automatically
- **Muted**: Video is muted (required for autoplay)
- **Loop**: Video repeats continuously
- **Mobile Fallback**: Video is disabled on mobile devices to save data

### Animation Settings
- **Typing Speed**: Adjust in `script.js` line 108
- **Scroll Animations**: Modify timing in CSS transitions
- **Skill Bar Animation**: Change duration in `script.js`

### Responsive Breakpoints
- **Mobile**: ≤ 768px
- **Tablet**: 769px - 1024px
- **Desktop**: > 1024px

## 📱 Mobile Optimization

- Video background is disabled on mobile devices
- Gradient background fallback is used instead
- Touch-friendly navigation menu
- Optimized for mobile performance

## 🔧 Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers

## 📝 Notes

- **Video Format**: Use MP4 format for best compatibility
- **Video Size**: Keep video file size reasonable for fast loading
- **Performance**: Video is optimized for smooth playback
- **Accessibility**: Proper contrast and text readability maintained

## 🚀 Deployment

### GitHub Pages
1. Upload files to a GitHub repository
2. Go to Settings > Pages
3. Select source branch
4. Your site will be available at `https://username.github.io/repository-name`

### Netlify
1. Drag and drop the project folder to Netlify
2. Your site will be deployed instantly

### Vercel
1. Connect your GitHub repository
2. Deploy automatically on push

## 🤝 Contributing

Feel free to customize and improve this portfolio template!

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

**Happy coding! 🎉** 
# Dorasi Zevta - Portfolio Website

A comprehensive portfolio website showcasing the work of Dorasi Zevta, a Junior Cyber Security Engineer with expertise in both logical and creative domains. Built with HTML, CSS, and JavaScript featuring modern design, dark/light theme toggle, and smooth animations.

## About Dorasi Zevta

Dorasi is a passionate and detail-oriented Junior Cyber Security Engineer with a strong foundation in network security, web security, and data security. With 2+ years of experience, Dorasi thrives on solving security challenges and staying relevant through Capture The Flag competitions and keeping up with the latest technology.

Beyond cybersecurity, Dorasi is also a creative professional with experience in:
- Electronic music production
- Graphic design
- Web development
- App development
- Game development
- 3D art

## Features

- 🎨 **Modern Design**: Clean, professional layout with gradient accents and smooth animations
- 🌙 **Dark/Light Theme**: Toggle between themes with persistent storage
- 📱 **Responsive**: Fully responsive design that works on all devices
- ⚡ **Smooth Animations**: CSS animations and JavaScript interactions
- 🎯 **Interactive Elements**: Hover effects, scroll animations, and typing effects
- 🔒 **Cybersecurity Focus**: Specialized sections for security projects and tools
- 🎵 **Creative Portfolio**: Dedicated sections for music, design, and art
- 🚀 **Performance**: Optimized for fast loading

## Portfolio Sections

### Main Portfolio (`index.html`)
1. **Hero Section**: Introduction with animated typing effects
2. **About Section**: Personal information with cybersecurity focus
3. **Cyber Shield Services**: Network Security, Web Security, Data Security, Threat Identification
4. **Skills Section**: Tools, Operating Systems, and Tech Stack
5. **Experience Section**: Work history including IT Support and freelance work
6. **Featured Projects**: Security-focused projects like Secure File Upload System, Keylogger, and SQL Injection demonstrations
7. **Contact Section**: Contact information and form

### Creative Work Portfolio (`creative-work.html`)
- **Graphic Design**: Posters and visual designs using Photoshop and Canva
- **3D Art**: Stylized voxel-based artworks created with MagicaVoxel
- **Music Production**: EDM genres including Techno, Tech House, Hybrid Trap, Festival Trap, Future Bass, and Deep House

### Specialized Portfolio Pages
- `graphic-design.html` - Graphic design portfolio
- `3d-art.html` - 3D art showcase
- `music-production.html` - Music production with platform tabs (SoundCloud, Spotify, Apple Music, YouTube)
- `web-development.html` - Web development projects
- `app-development.html` - Mobile and web app development
- `game-development.html` - Game development projects
- `projects.html` - Extended project showcase

## Skills & Technologies

### Cybersecurity Tools
- **Advanced**: Mikrotik, Windows
- **Intermediate**: Kali, Ubuntu, Debian, Nmap, sqlmap, Netcat, Metasploit, Burp Suite
- **Beginner**: GNS3, Wireshark, macOS

### Programming & Web Technologies
- **Intermediate**: HTML, CSS, JavaScript
- **Beginner**: Python, SQL, PHP, Bash

### Creative Tools
- **Music Production**: FL Studio, Ableton Live
- **Graphic Design**: Photoshop, Canva
- **3D Art**: MagicaVoxel

## Work Experience

- **IT Support** @ Murni Teguh Group (May 2024 – November 2024)
- **Frontend Developer** @ Self Employed (2020 – Present)
- **Graphic Designer** @ Freelance (2020 – Present)

## Featured Projects

### Security Projects
1. **Secure File Upload System** - Python, Flask, Scikit-learn
2. **Keylogger** - Security research tool for ethical testing
3. **SQL Injection** - Vulnerability demonstration and prevention

### Creative Projects
- **Graphic Design**: 25+ completed projects with custom illustrations and bold typography
- **3D Art**: Architectural scenes and character concepts using voxel-based design
- **Music Production**: Multiple EDM genres with focus on sound design and mixing

## Customization Guide

### Personal Information

Edit the following in `index.html`:

```html
<!-- Update your name -->
<h1 class="hero-title">
    Hi, I'm <span class="highlight" id="binary-anim">your name</span>
</h1>

<!-- Update your description -->
<p class="hero-description">
    a visionary who blurs the lines between logical work and creative work.
</p>

<!-- Update about section content -->
<p>
    I'm a passionate and detail oriented Junior Cyber Security Engineer...
</p>

<!-- Update statistics -->
<div class="stat">
    <h3>2+</h3>
    <p>Years Experience</p>
</div>
```

### Contact Information

Update your contact details in the contact section:

```html
<div class="contact-method">
    <i class="fas fa-envelope"></i>
    <span>your.email@example.com</span>
</div>
<div class="contact-method">
    <i class="fas fa-phone"></i>
    <span>+1 (555) 123-4567</span>
</div>
<div class="contact-method">
    <i class="fas fa-map-marker-alt"></i>
    <span>Your City, Country</span>
</div>
```

### Social Links

Update your social media links:

```html
<div class="social-links">
    <a href="https://github.com/yourusername" class="social-link">
        <i class="fab fa-github"></i>
    </a>
    <a href="https://linkedin.com/in/yourusername" class="social-link">
        <i class="fab fa-linkedin"></i>
    </a>
    <a href="https://soundcloud.com/yourusername" class="social-link">
        <i class="fab fa-soundcloud"></i>
    </a>
</div>
```

### Skills

Customize your skills in the skills section:

```html
<div class="skill-category">
    <h3>Tools</h3>
    <div class="skill-items">
        <div class="skill-item" data-level="Beginner">Tool Name</div>
        <!-- Add more skills -->
    </div>
</div>
```

### Projects

Update your projects in the projects section:

```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-shield-alt"></i>
    </div>
    <div class="project-content">
        <h3>Project Name</h3>
        <p>Project description...</p>
        <div class="project-tech">
            <span>Technology 1</span>
            <span>Technology 2</span>
        </div>
        <div class="project-links">
            <a href="#" class="project-link"><i class="fab fa-github"></i> Code</a>
            <a href="#" class="project-link"><i class="fas fa-external-link-alt"></i> Live</a>
        </div>
    </div>
</div>
```

## Color Scheme

The website uses CSS variables for easy color customization. Edit the colors in `styles.css`:

```css
:root {
    --primary-color: #6366f1;      /* Main brand color */
    --secondary-color: #8b5cf6;    /* Secondary brand color */
    --accent-color: #06b6d4;       /* Accent color */
    --text-primary: #1f2937;       /* Primary text color */
    --text-secondary: #6b7280;     /* Secondary text color */
    --bg-primary: #ffffff;         /* Primary background */
    --bg-secondary: #f9fafb;       /* Secondary background */
    --bg-tertiary: #f3f4f6;        /* Tertiary background */
    --border-color: #e5e7eb;       /* Border color */
}
```

## Fonts

The website uses the Inter font family. You can change it in `styles.css`:

```css
body {
    font-family: 'Inter', sans-serif;
}
```

To use a different font, update the Google Fonts link in `index.html` and change the font-family in CSS.

## Features Explained

### Theme Toggle
- Click the moon/sun icon in the navigation to toggle between light and dark themes
- Theme preference is saved in localStorage
- Smooth transition between themes

### Mobile Navigation
- Hamburger menu for mobile devices
- Smooth slide-in animation
- Auto-close when clicking navigation links

### Smooth Scrolling
- Navigation links smoothly scroll to sections
- Accounts for fixed navbar height
- Active link highlighting based on scroll position

### Typing Animations
- Animated typing effects for hero titles and experience sections
- Customizable typing speed and content

### Music Platform Tabs
- Interactive tabs for different music platforms (SoundCloud, Spotify, Apple Music, YouTube)
- Smooth transitions between platform content

### Contact Form
- Form validation for required fields and email format
- Success/error notifications
- Simulated form submission (replace with your backend)

### Animations
- Fade-in animations on scroll
- Typing animation for hero title
- Hover effects on cards and buttons
- Parallax effect on hero section

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Performance Tips

1. **Optimize Images**: Replace placeholder icons with optimized images
2. **Minify CSS/JS**: Minify files for production
3. **CDN**: Use CDN for external libraries
4. **Lazy Loading**: Implement lazy loading for images
5. **Caching**: Set appropriate cache headers

## Deployment

### GitHub Pages
1. Push your code to a GitHub repository
2. Go to Settings > Pages
3. Select source branch (usually `main`)
4. Your site will be available at `https://username.github.io/repository-name`

### Netlify
1. Connect your GitHub repository to Netlify
2. Deploy automatically on push to main branch
3. Get a custom domain and SSL certificate

### Vercel
1. Import your GitHub repository to Vercel
2. Automatic deployments on push
3. Custom domain and SSL included

## File Structure

```
portfolio/
├── index.html              # Main portfolio page
├── creative-work.html      # Creative work showcase
├── graphic-design.html     # Graphic design portfolio
├── 3d-art.html           # 3D art showcase
├── music-production.html  # Music production portfolio
├── web-development.html   # Web development projects
├── app-development.html   # App development projects
├── game-development.html  # Game development projects
├── projects.html         # Extended project showcase
├── styles.css            # CSS styles and animations
├── script.js             # JavaScript functionality
├── graphic-design.css    # Additional CSS for graphic design page
├── profile.png           # Profile picture
├── about-bg.png         # About section background
├── cloud-server.png     # Hero section background
├── Various GIF files    # Animated backgrounds and assets
└── README.md            # This file
```

## Customization Checklist

- [ ] Update personal information (name, title, description)
- [ ] Add your profile picture (replace `profile.png`)
- [ ] Update contact information
- [ ] Add your social media links
- [ ] Customize skills and technologies
- [ ] Add your projects with links
- [ ] Update color scheme if desired
- [ ] Add your own logo/branding
- [ ] Test on different devices
- [ ] Deploy to your preferred platform

## Support

If you need help customizing your portfolio:

1. Check the HTML comments for guidance
2. Review the CSS variables for styling options
3. Test changes in a local development environment
4. Use browser developer tools for debugging
# My Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. Designed for GitHub Pages deployment.

## 📁 Project Structure

```
portfolio/
├── images/              # Folder for your portfolio images
├── index.html           # Main HTML file
├── style.css            # Styling
├── script.js            # JavaScript functionality
└── README.md            # This file
```

## 🚀 Getting Started

### Local Setup
1. Open `index.html` in your web browser to preview the website
2. All files are included - no dependencies needed

### GitHub Pages Deployment

#### Option 1: Using the `gh-pages` branch
1. Initialize git in the project (if not already done):
   ```bash
   git init
   ```

2. Add all files:
   ```bash
   git add .
   git commit -m "Initial commit: Portfolio website"
   ```

3. Push to your GitHub repository:
   - Create a new repository on GitHub named `<username>.github.io`
   - Push your code to the main branch

4. Your site will be live at: `https://<username>.github.io`

#### Option 2: Using a project repository
1. Create a repository named `portfolio` (or any name)
2. Push your code
3. Go to Settings → Pages → Source: set to `main` branch and `/root` folder
4. Your site will be at: `https://<username>.github.io/portfolio`

## ✏️ Customization Guide

### 1. **Update Your Information**
Open `index.html` and replace:
- `Your Name` - your actual name (appears in nav and hero)
- `Full Stack Developer | Designer | Creative Thinker` - your tagline
- About section text - your bio
- Skill tags - your actual skills

### 2. **Add Portfolio Images**
- Save your project images to the `images/` folder
- Update image paths in `index.html`:
  ```html
  <img src="images/your-image.jpg" alt="Project description">
  ```
- Recommended image size: 400x250px (or any 16:9 ratio)
- Supported formats: JPG, PNG, WebP

### 3. **Update Portfolio Projects**
Edit the portfolio items in `index.html`:
- Change "Project Title" to your actual project names
- Update project descriptions
- Add real project links in the `href` attribute
- Replace placeholder images

### 4. **Setup Contact Form**
Replace `your-email@example.com` in `script.js` with your actual email:
```javascript
const mailtoLink = `mailto:YOUR-EMAIL@example.com?...`;
```

For a more robust solution, consider using:
- [Formspree](https://formspree.io/)
- [Basin](https://usebasin.com/)
- [Netlify Forms](https://www.netlify.com/products/forms/)

### 5. **Update Social Links**
In the contact section, update social media URLs:
```html
<a href="https://github.com/yourusername" class="social-link">GitHub</a>
<a href="https://linkedin.com/in/yourusername" class="social-link">LinkedIn</a>
```

### 6. **Customize Colors**
Edit the CSS variables in `style.css`:
```css
:root {
    --primary-color: #667eea;        /* Main color */
    --secondary-color: #764ba2;      /* Accent color */
    --dark-bg: #1a1a1a;             /* Dark background */
    --light-bg: #f7f7f7;            /* Light background */
    --text-dark: #333;              /* Dark text */
    --text-light: #666;             /* Light text */
}
```

## 📱 Features

✅ Fully responsive design (desktop, tablet, mobile)
✅ Smooth scrolling navigation
✅ Portfolio grid with hover effects
✅ Contact form
✅ Social media links
✅ Fast loading (pure HTML/CSS/JS)
✅ SEO-friendly structure
✅ GitHub Pages ready

## 🎨 Sections

1. **Navigation** - Sticky header with smooth scrolling
2. **Hero** - Eye-catching introduction
3. **About** - Your bio and skills
4. **Portfolio** - Showcase your projects
5. **Contact** - Contact form and social links
6. **Footer** - Copyright info

## 📝 Tips for Enhancement

- Keep descriptions concise and compelling
- Use high-quality images (optimize for web)
- Keep skill tags relevant and current
- Update projects regularly
- Test on multiple devices before deploying
- Check all links before going live

## 🔍 SEO Optimization

Update the `<title>` and add meta description in `index.html`:
```html
<title>Your Name - Web Developer Portfolio</title>
<meta name="description" content="Your professional tagline here">
```

## 📞 Need Help?

- Check your browser's console for errors (F12)
- Validate HTML at [validator.w3.org](https://validator.w3.org/)
- Test responsive design with browser developer tools
- Ensure all image paths are correct

---

**Ready to deploy?** Simply push to GitHub and your portfolio will go live! 🎉

# Md. Tanvir Hossain - Portfolio Website

A modern, responsive portfolio website showcasing my skills, projects, and experience as a Machine Learning Engineer and Researcher.

## 🌐 Live Demo

Visit the live website: [https://tanvir-eece-cse.github.io](https://tanvir-eece-cse.github.io)

## ✨ Features

- **Modern Dark Theme** - Sleek dark design with cyan accent colors
- **Responsive Design** - Works perfectly on desktop, tablet, and mobile
- **Smooth Animations** - AOS (Animate on Scroll) library for engaging animations
- **Interactive Elements** - Custom cursor, typing effect, and hover animations
- **Single Page Application** - Smooth scrolling between sections
- **Contact Form** - Direct email integration

## 🛠️ Technologies Used

- HTML5
- CSS3 (Custom Properties, Flexbox, Grid)
- JavaScript (ES6+)
- [AOS Library](https://michalsnik.github.io/aos/) - Animate On Scroll
- [Font Awesome](https://fontawesome.com/) - Icons
- [Google Fonts](https://fonts.google.com/) - Space Grotesk & JetBrains Mono

## 📁 Project Structure

```
tanvir-portfolio/
├── index.html          # Main HTML file
├── styles.css          # All CSS styles
├── script.js           # JavaScript functionality
├── README.md           # This file
└── images/             # Image assets (add your profile photo)
    └── profile.jpg
```

## 🚀 Deployment on GitHub Pages

### Step 1: Create GitHub Repository

1. Go to [GitHub](https://github.com) and create a new repository
2. Name it `<your-username>.github.io` (e.g., `tanvir-eece-cse.github.io`)
3. Make it **Public**
4. Don't initialize with README (we already have one)

### Step 2: Push to GitHub

```bash
# Navigate to the portfolio folder
cd tanvir-portfolio

# Initialize git repository
git init

# Add all files
git add .

# Commit
git commit -m "Initial commit: Portfolio website"

# Add remote origin (replace with your repo URL)
git remote add origin https://github.com/tanvir-eece-cse/tanvir-eece-cse.github.io.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** > **Pages**
3. Under "Source", select **main** branch
4. Click **Save**
5. Wait a few minutes for deployment
6. Your site will be live at `https://<your-username>.github.io`

## 🎨 Customization

### Update Profile Image

Replace the placeholder image URL in `index.html`:

```html
<img src="your-image-url.jpg" alt="Your Name" class="profile-image">
```

### Update Colors

Edit CSS variables in `styles.css`:

```css
:root {
    --accent-primary: #00d4ff;      /* Main accent color */
    --accent-secondary: #7b2cbf;    /* Secondary accent */
    --bg-primary: #0a0a0f;          /* Main background */
}
```

### Update Content

1. **Personal Info** - Update name, contact details in `index.html`
2. **Skills** - Modify skill items in the skills section
3. **Projects** - Add/remove project cards
4. **Experience** - Update timeline items
5. **Social Links** - Update GitHub, LinkedIn URLs

## 📱 Sections

1. **Hero** - Introduction with typing animation
2. **About** - Personal bio and quick stats
3. **Skills** - Technical skills organized by category
4. **Projects** - Featured projects with descriptions
5. **Experience** - Education and work timeline
6. **Publications** - Research papers and achievements
7. **Contact** - Contact form and social links

## 📧 Contact

- **Email**: tanvir.eece.mist@gmail.com
- **Phone**: +880 1714987380
- **GitHub**: [tanvir-eece-cse](https://github.com/tanvir-eece-cse)
- **LinkedIn**: [tanvir-eece](https://linkedin.com/in/tanvir-eece)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

⭐ If you found this portfolio template helpful, please give it a star!

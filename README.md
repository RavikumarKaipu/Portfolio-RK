# Ravikumar Kaipu - Portfolio

A modern, cyberpunk-themed portfolio website showcasing full-stack development skills and projects.

## 🚀 Live Demo

Once deployed, your portfolio will be live at your Vercel URL.

## ✨ Features

- **Cyberpunk Design** - Modern UI with glowing effects, custom cursor, and animated particles
- **Responsive Layout** - Optimized for all devices (desktop, tablet, mobile)
- **Interactive Elements** - Custom cursor, smooth scrolling, reveal animations
- **Projects Showcase** - Display your best work with live demos and code links
- **Skills Visualization** - Animated skill cards with proficiency indicators
- **Contact Form** - Easy way for visitors to reach out

## 🛠️ Tech Stack

- HTML5
- CSS3 (Custom Properties, Animations, Grid, Flexbox)
- Vanilla JavaScript
- Canvas API for particle effects
- Google Fonts (Orbitron, Rajdhani, Share Tech Mono)

## 📦 Deployment

### Deploy to Vercel (Recommended)

1. **Push to GitHub:**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Portfolio website"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git push -u origin main
   ```

2. **Deploy on Vercel:**
   - Go to [vercel.com](https://vercel.com)
   - Click "New Project"
   - Import your GitHub repository
   - Click "Deploy"
   - Your site will be live in seconds!

### Alternative: Deploy to Netlify

1. Push to GitHub (same as above)
2. Go to [netlify.com](https://netlify.com)
3. Click "New site from Git"
4. Choose your repository
5. Click "Deploy site"

### Local Development

Simply open `index.html` in your browser:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx http-server

# Or just open the file
open index.html  # macOS
start index.html # Windows
```

Then visit `http://localhost:8000`

## 📁 Project Structure

```
ravikumar-portfolio/
├── index.html          # Main portfolio page (self-contained)
├── README.md           # This file
├── vercel.json         # Vercel configuration
└── .gitignore          # Git ignore rules
```

## 🎨 Customization

### Update Your Information

Open `index.html` and modify:

1. **Personal Details** (Lines 6-8):
   - Page title
   - Your name in the hero section

2. **Hero Section** (Lines 114-400):
   - Name and role
   - Description
   - Resume link

3. **About Section** (Lines 470-630):
   - Bio and experience
   - Stats/metrics

4. **Projects** (Lines 695-1050):
   - Project cards with images, descriptions, and links
   - Technologies used

5. **Skills** (Lines 1055-1430):
   - Programming languages
   - Frontend/Backend frameworks
   - Tools & platforms

6. **Contact Links** (Lines 2060-2063):
   - GitHub URL
   - LinkedIn URL
   - Email address

### Color Scheme

Modify the CSS variables in the `:root` section (Lines 9-20):

```css
:root {
  --cyan: #00f5ff;      /* Primary accent */
  --purple: #bf00ff;    /* Secondary accent */
  --pink: #ff006e;      /* Tertiary accent */
  --gold: #ffd700;      /* Highlights */
  --green: #00ff88;     /* Success states */
}
```

## 🔧 Configuration Files

### vercel.json
Optimizes deployment with proper headers and routing.

### .gitignore
Prevents committing unnecessary files to Git.

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 🤝 Contributing

This is a personal portfolio, but feel free to fork it for your own use!

## 📄 License

Free to use for personal and commercial projects.

## 📞 Contact

- **Email**: kravikumar9392@gmail.com
- **LinkedIn**: [ravikumar-kaipu-75a8aa20a](https://linkedin.com/in/ravikumar-kaipu-75a8aa20a)
- **GitHub**: [RavikumarKaipu](https://github.com/RavikumarKaipu)

---

Built with 💙 by Ravikumar Kaipu

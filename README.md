# Portfolio Website - Dishank Viradiya

A modern, responsive portfolio website showcasing my work experience, projects, skills, and education. Built with HTML, CSS, and JavaScript, designed for deployment on GitHub Pages.

## 🌟 Features

- **Responsive Design**: Fully responsive layout that works on all devices
- **Modern UI**: Clean and professional design with smooth animations
- **Interactive Navigation**: Smooth scrolling and active link highlighting
- **Project Showcase**: Image slideshows for each project with auto-play and manual controls
- **Resume Section**: Download or view resume PDF directly from the site
- **Work Experience Grid**: Card-based layout for work history
- **Skills Section**: Organized categorization of technical skills
- **Contact Information**: Easy-to-find contact details and social links
- **Scroll Animations**: Intersection Observer API for smooth scroll-triggered animations
- **Mobile-Friendly**: Hamburger menu for mobile navigation

## 🚀 Live Demo

Once deployed, your portfolio will be available at:
```
https://dishank2933.github.io/portfolio
```
*(Replace `portfolio` with your actual repository name)*

## 📁 Project Structure

```
Portfolio/
├── index.html          # Main HTML file
├── styles.css          # Styling and responsive design
├── script.js           # JavaScript for interactivity and slideshow
├── README.md           # This file
├── resume.pdf          # Your resume (add this file)
└── images/             # Folder for project screenshots
    └── projects/
        ├── vb24.png, vb24-2.png, vb24-3.png
        ├── bluemoon.png, bluemoon-2.png, bluemoon-3.png
        ├── ziro.png, ziro-2.png, ziro-3.png
        ├── challan-office.png, challan-office-2.png, challan-office-3.png
        └── placeholder.png
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with CSS Grid, Flexbox, and animations
- **JavaScript (ES6+)**: Interactive features and smooth UX
- **Font Awesome**: Icons for visual enhancement
- **Google Fonts**: Inter font family

## 📦 Setup & Deployment

### Local Development

1. **Clone or download this repository**
   ```bash
   cd "/run/media/beast/New Volume/Z-Python_project/Portfolio"
   ```

2. **Open `index.html` in your browser**
   - Simply double-click the `index.html` file, or
   - Use a local server (recommended):
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Python 2
     python -m SimpleHTTPServer 8000
     
     # Using Node.js http-server
     npx http-server
     ```
   - Then visit `http://localhost:8000` in your browser

### GitHub Pages Deployment

1. **Create a new repository on GitHub**
   - Go to [GitHub](https://github.com/new)
   - Name it `portfolio` (or any name you prefer)
   - Don't initialize with README (we already have one)

2. **Initialize Git and push your code**
   ```bash
   # Navigate to your portfolio directory
   cd "/run/media/beast/New Volume/Z-Python_project/Portfolio"
   
   # Initialize git repository
   git init
   
   # Add all files
   git add .
   
   # Commit files
   git commit -m "Initial commit: Portfolio website"
   
   # Add your GitHub repository as remote
   git remote add origin https://github.com/dishank2933/portfolio.git
   
   # Push to GitHub
   git branch -M main
   git push -u origin main
   ```

3. **Enable GitHub Pages**
   - Go to your repository on GitHub
   - Click on **Settings** → **Pages** (in the left sidebar)
   - Under **Source**, select **main** branch
   - Click **Save**
   - Your site will be published at `https://dishank2933.github.io/portfolio/`

4. **Wait for deployment**
   - GitHub will automatically build and deploy your site
   - This usually takes 1-2 minutes
   - You'll see a green checkmark when it's ready

## 🖼️ Adding Project Images

1. **Create the images folder structure** (already created)

2. **Add your project screenshots** - Up to 3 images per project:
   - VB24: `vb24.png`, `vb24-2.png`, `vb24-3.png`
   - BlueMoon: `bluemoon.png`, `bluemoon-2.png`, `bluemoon-3.png`
   - Ziro: `ziro.png`, `ziro-2.png`, `ziro-3.png`
   - Challan Office: `challan-office.png`, `challan-office-2.png`, `challan-office-3.png`

3. **Image specifications**
   - Format: PNG or JPG
   - Recommended size: 1200x600px or 16:9 aspect ratio
   - File size: Keep under 500KB for faster loading
   - Slideshow: Images auto-rotate every 4 seconds with manual controls

4. **Commit and push images**
   ```bash
   git add images/
   git commit -m "Add project screenshots"
   git push
   ```

## 📄 Adding Your Resume

1. **Export your resume as PDF** named `resume.pdf`
2. **Place it in the root folder** (same level as index.html)
3. **Commit and push**
   ```bash
   git add resume.pdf
   git commit -m "Add resume PDF"
   git push
   ```

The resume section will have Download and View buttons that link to this file.

## 🎨 Customization

### Colors
Edit CSS variables in `styles.css`:
```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #10b981;
    --accent-color: #f59e0b;
    /* ... other colors */
}
```

### Content
- **Personal Info**: Edit the hero section in `index.html`
- **Projects**: Update project cards with your own details
- **Skills**: Modify skill tags in the skills section
- **Experience**: Add or edit timeline items

### Fonts
Change fonts by updating the Google Fonts link in `index.html` and the CSS:
```css
body {
    font-family: 'YourFont', sans-serif;
}
```

## 📱 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License

This project is open source and available for personal use. Feel free to fork and customize it for your own portfolio!

## 📞 Contact

**Dishank Viradiya**
- Email: dishank.amd@gmail.com
- GitHub: [@dishank2933](https://github.com/dishank2933)
- LinkedIn: [dishank2933](https://linkedin.com/in/dishank2933)

---

Built with ❤️ by Dishank Viradiya

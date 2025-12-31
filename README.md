# Jeswin Jerard - Portfolio Website

A personal portfolio website showcasing professional experience, skills, projects, and education.

## 🚀 How to Run

This is a static website built with pure HTML, CSS, and JavaScript. No build tools or dependencies are required!

### Method 1: Open Directly in Browser (Simplest)

1. Navigate to the project directory
2. Double-click on `index.html` or right-click and select "Open with" your preferred browser
3. The website will open directly in your browser

### Method 2: Using a Local Web Server (Recommended)

Running a local web server prevents potential CORS issues and provides a more realistic development environment.

#### Using Python (if installed):

**Python 3.x:**
```bash
python -m http.server 8000
```

**Python 2.x:**
```bash
python -m SimpleHTTPServer 8000
```

Then open your browser and navigate to: `http://localhost:8000`

#### Using Node.js (if installed):

Install `http-server` globally:
```bash
npm install -g http-server
```

Run the server:
```bash
http-server
```

Then open your browser and navigate to the provided URL (usually `http://localhost:8080`)

#### Using PHP (if installed):
```bash
php -S localhost:8000
```

Then open your browser and navigate to: `http://localhost:8000`

#### Using VS Code Live Server Extension:

1. Install the "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"

## 📁 Project Structure

```
Portfolio/
├── index.html          # Main HTML file
├── style.css           # Stylesheet
├── script.js           # JavaScript for interactivity
├── assets/             # Images and other assets
│   ├── profile.png     # Profile photo
│   └── resume.pdf      # Resume file
└── README.md           # This file
```

## 🛠️ Technology Stack

- **HTML5** - Structure and content
- **CSS3** - Styling and animations
- **JavaScript (Vanilla)** - Interactivity and dynamic features

### Key Features:
- Responsive design (mobile-friendly)
- Smooth scrolling navigation
- Hamburger menu for mobile devices
- Contact form
- Animated sections
- Professional portfolio sections (About, Skills, Experience, Projects, Education)

## 🎨 Customization

To customize this portfolio for your own use:

1. **Personal Information**: Edit the content in `index.html`
   - Update name, title, and contact information
   - Modify About, Skills, Experience, Projects, and Education sections

2. **Styling**: Modify `style.css` to change colors, fonts, and layout
   - Update CSS variables for quick color scheme changes
   - Adjust responsive breakpoints if needed

3. **Profile Photo**: Replace `assets/profile.png` with your own photo
   - Recommended size: 300x300px or larger (square format)

4. **Resume**: Replace `assets/resume.pdf` with your own resume

5. **Interactivity**: Customize behavior in `script.js`
   - Modify menu behavior
   - Add custom animations or features

## 📧 Contact Form

Note: The contact form in this portfolio is currently front-end only. To make it functional:

1. Integrate with a backend service (e.g., FormSpree, EmailJS)
2. Use a serverless function (e.g., AWS Lambda, Netlify Functions)
3. Add a PHP mail handler if hosting supports it

## 🌐 Deployment

This static website can be deployed to:

- **GitHub Pages**: Push to a repository and enable GitHub Pages
- **Netlify**: Drag and drop the folder or connect to GitHub
- **Vercel**: Import the repository or deploy via CLI
- **Surge.sh**: Run `surge` in the project directory
- **Any web hosting**: Upload all files via FTP/SFTP

## 📄 License

This portfolio is created for personal use. Feel free to use it as a template for your own portfolio.

## 👤 Author

**Jeswin Jerard**
- Email: jeswinjerard@gmail.com
- LinkedIn: [Jeswin Jerard](https://www.linkedin.com/in/jeswin-jerard-7ab01a332)
- Phone: +91 8075475312

---

*Last updated: 2025*

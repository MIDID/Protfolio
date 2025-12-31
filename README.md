# Portfolio Website - Jeswin Jerard

A professional portfolio website showcasing AI/ML engineering and backend development skills.

## 🌐 Live Site

This portfolio is automatically deployed to GitHub Pages: `https://midid.github.io/Protfolio/`

## 🚀 GitHub Pages Deployment

This repository is configured to automatically deploy to GitHub Pages using GitHub Actions.

### Automatic Deployment

Every push to the `main` branch will automatically trigger a deployment to GitHub Pages.

### Manual Deployment

You can also manually trigger a deployment from the Actions tab in GitHub.

### Setup Instructions

To enable GitHub Pages for this repository:

1. Go to your repository on GitHub
2. Click on **Settings**
3. Navigate to **Pages** in the left sidebar
4. Under **Build and deployment**, set:
   - **Source**: GitHub Actions
5. Save the changes

The workflow will automatically deploy your site on the next push to the `main` branch.

## 📁 Project Structure

```
Protfolio/
├── index.html          # Main HTML file
├── style.css           # Stylesheet
├── script.js           # JavaScript functionality
├── assets/             # Images and resources
│   └── profile.png     # Profile photo
└── .github/
    └── workflows/
        └── deploy.yml  # GitHub Actions deployment workflow
```

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)
- GitHub Pages
- GitHub Actions

## 📝 Local Development

To test the website locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/MIDID/Protfolio.git
   ```

2. Open `index.html` in your web browser, or use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js
   npx http-server
   ```

3. Navigate to `http://localhost:8000` in your browser

## 📧 Contact

- Email: jeswinjerard@gmail.com
- LinkedIn: [Jeswin Jerard](https://www.linkedin.com/in/jeswin-jerard-7ab01a332)

## 📄 License

This project is open source and available for personal use.

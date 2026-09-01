# City University - Academic Portal (Batch 62)

## 🌐 Live Preview

**Live Deployed Website:** [https://YOUR-GITHUB-USERNAME.github.io/YOUR-REPOSITORY-NAME/](https://YOUR-GITHUB-USERNAME.github.io/YOUR-REPOSITORY-NAME/)

*(Replace `YOUR-GITHUB-USERNAME` and `YOUR-REPOSITORY-NAME` with your actual GitHub username and repository name after pushing.)*

---

## 📑 Pages Included

1. **Home (`index.html`)** - University hero section, academic department hierarchy tree (CSE, EEE, Civil), and campus facilities.
2. **About Us (`about.html`)** - Mission, vision, university statistics, milestone timeline, and Batch 62 spotlight.
3. **Contact (`contact.html`)** - Campus headquarters details, admissions office hours, emergency contact, and inquiry form.
4. **Sign Up (`signup.html`)** - Student registration form featuring 14+ HTML5 input types (`text`, `email`, `password`, `number`, `tel`, `date`, `time`, `url`, `file`, `radio`, `checkbox`, `color`, `range`, `reset`, `submit`, `<select>`, `<textarea>`).
5. **Login (`login.html`)** - Standard student & faculty sign-in portal with remember me and demo login info.

---

## 🎨 Styling

- External stylesheet located at `css/style.css`.
- Responsive layout using modern CSS Grid and Flexbox.
- Modern color scheme with responsive navigation and active page indicators.

---

## 🚀 Automatic GitHub Deployment Instructions

1. Create a new repository on GitHub.
2. Initialize and push your project:
   ```bash
   git init
   git add .
   git commit -m "Initial commit for University Web Course HW"
   git branch -M main
   git remote add origin https://github.com/YOUR-GITHUB-USERNAME/YOUR-REPOSITORY-NAME.git
   git push -u origin main
   ```
3. In your GitHub repository:
   - Go to **Settings** > **Pages**.
   - Under **Build and deployment** > **Source**, select **GitHub Actions**.
4. The workflow in `.github/workflows/deploy.yml` will automatically build and deploy your site on every push.

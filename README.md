<div align="center">

# 🌐 Personal Portfolio Website

### A responsive, customizable, single-page website built with HTML, CSS & JavaScript

[![HTML5](https://img.shields.io/badge/HTML5-Structure-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-Styling-1572B6?logo=css&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-Interactions-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![GitHub Pages](https://img.shields.io/badge/Hosting-GitHub%20Pages-222?logo=github)](https://pages.github.com/)

**No framework · No package manager · No build step**

[Explore the Code](#-project-structure) · [Run Locally](#-run-it-locally) · [Customize](#-make-it-yours) · [Publish](#-publish-your-website) · [FAQ](#-frequently-asked-questions)

</div>

---

## ✨ About This Project

A simple starting point for anyone who wants to create a personal website to showcase their background, experience, skills, projects, and contact information. Everything lives in a single `index.html` file, with styles and scripts embedded directly in that file. You can edit it with any text editor and open it in a browser.

> **Try it yourself:** Fork this repository, replace the sample content with your own information, and publish your own version for free.

## 🧭 Explore the Website

| Section | What it shows | What to customize |
| --- | --- | --- |
| **Home** | Introductory headline, call-to-action buttons, social links | Name, headline, resume, profiles |
| **About** | Personal introduction and profile photo | Biography and portrait |
| **Experience** | Professional background | Roles, employers, dates, accomplishments |
| **Skills** | Areas of expertise | Your skills and tools |
| **What I Do** | Visual service / capability cards | Descriptions and card images |
| **Contact** | Contact call-to-action | Email and social profiles |

**Included interactions:** responsive navigation, active navigation highlighting while scrolling, scroll-triggered section effects, and repository cards loaded from the public GitHub API.

## 🧰 Technology

- **HTML5** for content and page structure
- **CSS3** for layout, colors, responsiveness, and visual effects
- **Vanilla JavaScript** for interactive behavior
- **Google Fonts (Inter)** for typography
- **Font Awesome** for icons
- **GitHub REST API** for the repository showcase

Google Fonts, Font Awesome, and live GitHub content require internet access. The page's local HTML and image content can still be previewed without those services.

## 📁 Project Structure

```text
sample-portfolio-website-main/
├── index.html                              # Entire website: HTML + embedded CSS + JS
├── README.md                               # Project guide
├── profile_avatar.jpg                      # Profile picture
├── iconf.png                               # Browser tab icon
├── devops-master-architecture.png          # Illustration asset
├── Cloud-Infrastructure-and-Architecture.png
├── CICD-Pipeline-Automation.png
├── Containerization-and-Orchestration.png
├── Infrastructure-as-Code-IaC.png
├── Monitoring-Logging-and-Observability.png
├── Performance-Optimization-and-Cost-Management.png
└── System-Reliability-and-Incident-Management.png
```

> **Resume note:** The current HTML links to `devops_zeeshan_resume.pdf`, but that file was **not included** in the uploaded project archive. Add a PDF with that filename to the repository root, or update the link in `index.html` to your own resume filename.

## 🚀 Run It Locally

<details open>
<summary><strong>Option A — Download the ZIP (easiest)</strong></summary>

1. On GitHub, click **Code → Download ZIP**.
2. Extract the ZIP to a folder.
3. Double-click `index.html` to open it in your browser.
4. Edit `index.html`, save it, and refresh the browser to see your changes.

No installation is needed.

</details>

<details>
<summary><strong>Option B — Clone with Git</strong></summary>

```bash
git clone https://github.com/zeeshanizm/sample-portfolio-website.git
cd sample-portfolio-website
```

Open `index.html` in your browser, or use the Live Server extension in Visual Studio Code for automatic refresh.

</details>

<details>
<summary><strong>Option C — Run a simple local server (optional)</strong></summary>

If Python is already installed:

```bash
python -m http.server 8000
```

Visit **http://localhost:8000**. Stop the server with **Ctrl+C**.

</details>

## 🎨 Make It Yours

<details open>
<summary><strong>1. Update your name, headline, and introduction</strong></summary>

Open `index.html` and edit the text in the `home` and `about` sections. You can also update the page title inside `<title>...</title>`.

</details>

<details>
<summary><strong>2. Replace your profile image and card illustrations</strong></summary>

Replace `profile_avatar.jpg` with your own image, keeping the same filename, or change the image path in `index.html`. Do the same for the illustration PNG files. Use optimized images for faster loading.

</details>

<details>
<summary><strong>3. Update your experience, skills, and services</strong></summary>

Find the sections with these IDs in `index.html`: `experience`, `skills`, and `work`. Replace the sample entries with your own achievements, skills, and service descriptions. Keep the section IDs unchanged unless you also update the navigation links.

</details>

<details>
<summary><strong>4. Connect your own GitHub profile</strong></summary>

Find the GitHub API URL in the JavaScript near the bottom of `index.html`:

```javascript
fetch('https://api.github.com/users/zeeshanizm/repos?sort=updated')
```

Replace `zeeshanizm` with **your GitHub username**. Also update the GitHub profile link in the page. The showcase currently displays up to six repositories. Public API rate limits may occasionally affect loading.

</details>

<details>
<summary><strong>5. Update social links, email, and resume</strong></summary>

Search `index.html` for `linkedin.com`, `github.com`, `mailto:`, and the resume filename. Replace each with your own links. Add your resume PDF to the repository and ensure the download link matches its exact filename (including capitalization).

</details>

<details>
<summary><strong>6. Adjust colors, fonts, and spacing</strong></summary>

Edit the CSS inside the `<style>` block in `index.html`. Test desktop and mobile widths after making changes. The Inter font is loaded from Google Fonts.

</details>

## 🌍 Publish Your Website

<details open>
<summary><strong>Option A — GitHub Pages (free static hosting)</strong></summary>

1. Create a GitHub repository, or fork this one.
2. Make sure `index.html` is in the repository root.
3. Push your changes to the `main` branch.
4. Open **Repository → Settings → Pages**.
5. Under **Build and deployment**, select **Deploy from a branch**.
6. Select **main** and **/(root)**, then click **Save**.
7. Wait for the deployment and open the published link shown in Pages settings.

For a normal project repository, the URL is typically:

```text
https://YOUR_USERNAME.github.io/YOUR_REPOSITORY/
```

For a special repository named `YOUR_USERNAME.github.io`, the URL is typically:

```text
https://YOUR_USERNAME.github.io/
```

**Note:** A Pages project URL includes a repository path. If your website uses root-relative paths (starting with `/`), adjust them for project-site hosting.

[Official GitHub Pages documentation](https://docs.github.com/en/pages/quickstart)

</details>

<details>
<summary><strong>Option B — Vercel (free personal hosting)</strong></summary>

1. Sign in at [vercel.com](https://vercel.com/) using GitHub.
2. Choose **Add New → Project**.
3. Import the repository containing `index.html`.
4. Choose **Other** if a framework is requested.
5. Use the repository root as the project directory; no npm installation or build command is needed for this static HTML site.
6. Deploy and open the generated `vercel.app` URL.

If Vercel requests an output directory, use the project root for the static files or configure the project for a no-build static deployment. Do **not** use `npm install` unless you have added a `package.json` and an actual build process.

[Vercel documentation](https://vercel.com/docs)

</details>

## 🔄 Update Your Published Website

After editing the files, commit and push:

```bash
git add .
git commit -m "Update portfolio content"
git push origin main
```

GitHub Pages or a Git-connected Vercel project will publish the updated site after its deployment finishes.

## 🛠️ Troubleshooting

<details>
<summary><strong>Images are missing</strong></summary>

Check filenames and capitalization. GitHub Pages runs on a case-sensitive environment. Ensure image files were committed and paths match the files in the repository.

</details>

<details>
<summary><strong>The resume download doesn't work</strong></summary>

Add the missing resume PDF to the repository root or update the resume link to point to an existing PDF file. Verify the filename exactly.

</details>

<details>
<summary><strong>GitHub repository cards are empty</strong></summary>

Confirm the GitHub username in the API URL, check that the account has public repositories, and inspect the browser's developer console for network or rate-limit errors.

</details>

<details>
<summary><strong>The website works locally but not after publishing</strong></summary>

Verify that `index.html` is at the published root, hosting is configured for the correct branch, and all image and document paths are valid for the published URL.

</details>

## ❓ Frequently Asked Questions

<details>
<summary><strong>Do I need Node.js or npm?</strong></summary>

No. The supplied website is plain HTML, CSS, and JavaScript. You can open it directly in a browser.

</details>

<details>
<summary><strong>Can I use this as a starting point for my own portfolio?</strong></summary>

You can inspect and fork the repository. Reuse and redistribution permissions depend on the repository's license. The current uploaded archive does not include a license file; the owner should add one if they want to explicitly permit reuse.

</details>

<details>
<summary><strong>Can I connect a custom domain?</strong></summary>

Yes. Both GitHub Pages and Vercel support custom domains. You'll need to own the domain and configure its DNS records according to your hosting provider's instructions.

</details>

## 🤝 Contributing

Suggestions and improvements are welcome through GitHub Issues and pull requests. For significant changes, open an issue first to discuss the idea.

## 📄 License

**No license file is included in the supplied project archive.** If you intend others to copy, modify, and distribute this project, add an appropriate license (for example, MIT) after confirming you have rights to all included code and assets.

---

<div align="center">

**Build something personal. Make it your own. Share it with the world.**

[Back to top](#-personal-portfolio-website)

</div>

# Dinithi Samarathunga - Personal Developer Portfolio

Welcome to the official repository for **Dinithi Samarathunga's** developer portfolio website, deployed on GitHub Pages.

**Live Website:** [https://Dinithi717.github.io/](https://Dinithi717.github.io/)

---

## 🌟 About the Portfolio

This portfolio showcases the academic background, core technical skills, and featured projects of **Dinithi Samarathunga**, an undergraduate pursuing a **BSc (Hons) in Information Technology specializing in Data Science** at the **Sri Lanka Institute of Information Technology (SLIIT)**.

### Tech Stack
Built strictly adhering to pure web standards:
- **HTML5**: Semantic tags, accessible landmarks, Open Graph SEO metadata.
- **CSS3**: Modern custom properties, responsive grids, glassmorphism, fluid typography, subtle gradient glow, and smooth animations (Zero CSS frameworks like Bootstrap or Tailwind).
- **Vanilla JavaScript**: Lightweight ES6+ DOM manipulation for interactive project category filtering, responsive mobile navigation, scroll-reveal animations, dynamic copyright year, and accessible image modals (Zero JS frameworks like React, Vue, or jQuery).

---

## 📁 Repository Structure

```
Dinithi717.github.io/
│
├── index.html                   # Semantic HTML5 single-page structure
├── README.md                    # Project documentation & GitHub Pages deployment guide
│
├── CSS/
│   └── style.css                # Premium modern dark navy theme & responsive layouts
│
├── JS/
│   └── script.js                # Pure Vanilla JS interactivity & filtering logic
│
├── Assets/
│   ├── images/
│   │   └── My.png                       # Profile photograph
│   ├── CV/
│   │   └── Dinithi_Samarathunga_CV.pdf   # Downloadable curriculum vitae
│   ├── Certificate/                     # Course certificate PDFs
│   │   ├── AIML stage1/
│   │   ├── Frontend Development/
│   │   ├── pyhton/
│   │   └── web/
│   └── Projects/                        # Real screenshots for featured projects
│       ├── AI powered Job recommendation system/
│       ├── Ecom DWBI/
│       ├── SCMS/
│       ├── SCMS mobile app/
│       └── Student retention analysis system/
│
└── Projects/                            # Preserved projects folder
    └── README.md
```

---

## 💻 How to Preview Locally in VS Code

You can preview the website locally on your computer using either of the following straightforward methods:

### Method 1: Using the VS Code "Live Server" Extension (Recommended)
1. Open **VS Code**.
2. Press `Ctrl + Shift + X` (or click the Extensions icon on the left sidebar).
3. Search for **Live Server** (by *Ritwick Dey*) and click **Install**.
4. Open the `Dinithi717.github.io` folder in VS Code (`File > Open Folder...`).
5. Right-click on `index.html` in the file explorer and select **"Open with Live Server"** (or click **"Go Live"** in the bottom status bar).
6. Your browser will automatically open `http://127.0.0.1:5500/index.html` with real-time auto-reload upon edits.

### Method 2: Using Built-in Python HTTP Server (No Extensions Needed)
If you have Python installed:
1. Open your terminal or PowerShell in the repository root directory:
   ```powershell
   cd c:\Users\HP\Desktop\Dinithi717.github.io
   ```
2. Start the lightweight local server:
   ```powershell
   python -m http.server 8000
   ```
3. Open your browser and navigate to:
   ```
   http://localhost:8000
   ```

---

## 🚀 How to Deploy to GitHub Pages

Because this website is completely static, it requires zero build steps or servers and deploys directly from your GitHub repository.

### Step 1: Commit and Push Your Changes
Open your terminal inside the project directory and run:

```bash
# Check status
git status

# Stage all files
git add .

# Create your commit
git commit -m "Build premium personal developer portfolio website"

# Push to your main branch on GitHub
git push -u origin main
```

### Step 2: Configure GitHub Pages (One-Time Setup)
1. Navigate to your repository on GitHub: `https://github.com/Dinithi717/Dinithi717.github.io`
2. Click on **Settings** (top tabs).
3. In the left sidebar, click on **Pages** (under the "Code and automation" section).
4. Under **Build and deployment**:
   - **Source**: Select `Deploy from a branch`.
   - **Branch**: Select `main` and keep the folder set to `/ (root)`.
5. Click **Save**.
6. Wait 1-2 minutes. GitHub Pages will build and deploy the site.
7. Your portfolio will be live at:
   👉 **`https://Dinithi717.github.io/`**

---

## 👤 Personal Information & Links

- **Name:** Dinithi Samarathunga
- **Degree:** BSc (Hons) in Information Technology
- **Specialization:** Data Science
- **University:** Sri Lanka Institute of Information Technology (SLIIT)
- **Email:** [sdinithisamarathunga@gmail.com](mailto:sdinithisamarathunga@gmail.com)
- **LinkedIn:** [linkedin.com/in/dinithi-samarathunga-043316326](https://linkedin.com/in/dinithi-samarathunga-043316326)
- **GitHub:** [github.com/Dinithi717](https://github.com/Dinithi717)

---

## 📸 Updating Your Profile Picture Later
To replace the avatar visual with your personal photograph:
1. Save your photograph as `profile.jpg` or `profile.png`.
2. Place the file inside the `Assets/images/` directory:
   ```
   Assets/images/profile.jpg
   ```
3. The website's hero section will automatically detect and render your photo with a sleek neon glowing border!

# Ultra-Premium Personal Developer Portfolio

An elite-level, futuristic personal portfolio website engineered for **Vishal Singh Rajpuurohit** (Computer Science Engineer, AI Developer, Full Stack Developer, and Problem Solver) built with **ONLY HTML5, CSS3, and Vanilla JavaScript**.

![Portfolio Preview](assets/profile.jpg)

---

## 🌟 Key Highlights & Design Aesthetic

- **Design Systems Inspired By**: Linear.app, Vercel Developer Platform, and Apple Product UI.
- **Glassmorphism & Cyber Aesthetics**: Dark theme backdrop filters (`backdrop-filter: blur(16px)`), neon cyan & violet glow overlays, and dynamic lighting.
- **Pure Web Technologies**: Zero frameworks (No React, No Next.js, No Tailwind, No Bootstrap, No JQuery).
- **Interactive Canvas API**: Interactive particle constellation background responding dynamically to cursor movement.
- **3D Parallax Tilt Effects**: Physics-based card tilt on mouse hover for projects, skills, and coding profiles.
- **Interactive Modals & Project Galleries**: Category filtering tabs (*All*, *AI*, *Web*, *Backend*) and detail overlay popups.

---

## 📁 Project Directory Structure

```
portfolio/
│
├── index.html                # Semantic HTML5 layout with high SEO microdata & accessibility
├── style.css                 # Custom CSS3 stylesheet, glassmorphism design system & responsiveness
├── script.js                 # Modular Vanilla ES6+ JavaScript handling interactive logic
│
├── assets/
│   ├── profile.jpg           # High-resolution futuristic professional profile avatar
│   ├── resume.pdf            # Instant downloadable PDF resume document
│   └── projects/
│       ├── electricity_optimizer.png # Screenshot for AI Electricity Consumption Optimizer
│       ├── insurance_fraud.png      # Screenshot for Insurance Fraud Detection System
│       ├── smart_attendance.png     # Screenshot for Smart Attendance System
│       └── url_shortener.png        # Screenshot for URL Shortener Microservice
│
└── README.md                 # Technical documentation & deployment instructions
```

---

## 🚀 Key Features Breakdown

1. **Hero Landing Section**:
   - Dynamic Typewriter text rotator for role titles (*Computer Science Engineer*, *AI Developer*, *Full Stack Developer*, *Problem Solver*).
   - High resolution profile image with glowing pulse status badge (*Open to Work*).
   - Action buttons for **View Projects**, direct **Download Resume**, and **LinkedIn Connection**.

2. **About Me & Interactive Timeline**:
   - Education details (B.Tech Computer Science Engineering) & Career Objectives.
   - 5-Phase animated timeline showing progress from core education to AI Development.

3. **Technical Skills Dashboard**:
   - Categorized skills: *Programming Languages*, *Frontend*, *Backend Frameworks*, *Database*, *AI/ML*, and *Developer Tools*.
   - Skill tag badges with proficiency indicators (*Expert*, *Advanced*, *Proficient*).

4. **Project Showcase & Modal Overlays**:
   - **Project 1: AI Electricity Consumption Optimizer** (HTML, CSS, JS, ML, AI)
   - **Project 2: Insurance Fraud Detection System** (Python, Flask, Machine Learning, Scikit-learn)
   - **Project 3: Smart Attendance System** (Python, OpenCV, SQL Database, Face Recognition)
   - **Project 4: High Performance URL Shortener** (Python, Flask, SQL, REST API)
   - Filter buttons for category sorting and interactive deep-dive modal view.

5. **Coding Profiles & Verified Badges**:
   - Cards linking directly to **GitHub**, **LinkedIn**, **LeetCode**, **CodeChef**, **HackerRank**, and **GeeksforGeeks**.

6. **Milestones & Animated Counters**:
   - IntersectionObserver powered animated counters: **150+ DSA Solved**, **10+ Projects Built**, **5+ Certifications**, **10+ Technologies Learned**.

7. **Resume & Contact Section**:
   - Resume preview breakdown card with direct PDF download trigger.
   - Contact form with client-side validation and toast notifications.
   - Direct `mailto:` and `tel:` buttons.

---

## 💻 How to Run Locally

You can preview the portfolio locally using any simple web server:

### Option 1: Python HTTP Server (Recommended)
Open your terminal in the `portfolio` folder and run:
```bash
python -m http.server 8000
```
Then open `http://localhost:8000` in your web browser.

### Option 2: VS Code Live Server
1. Open the `portfolio` folder in VS Code.
2. Click **Go Live** from the bottom bar or right-click `index.html` and select **Open with Live Server**.

---

## 🌐 Deployment to GitHub Pages

1. Create a new GitHub repository named `portfolio` or `<your-username>.github.io`.
2. Push all contents of the `portfolio` directory:
   ```bash
   git init
   git add .
   git commit -m "Initial commit of elite developer portfolio"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```
3. In your GitHub repository settings:
   - Navigate to **Settings** > **Pages**.
   - Under **Source**, select `main` branch and `/ (root)` folder.
   - Click **Save**.
4. Your website will be live at `https://<your-username>.github.io/<repo-name>/`!

---

© 2026 Vishal Singh Rajpuurohit. All Rights Reserved.

# 🌙 Badr El Ghazaoui — Portfolio

Personal portfolio website built with React, Three.js, and Framer Motion.

🔗 **Live:** [badrelghazaoui.com](https://badrelghazaoui.com/)  
✍️ **Blog:** [moondiscoveries.com](https://moondiscoveries.com/)

---

## 🛠️ Built With

- [React](https://react.dev/) — UI framework
- [Three.js](https://threejs.org/) + [React Three Fiber](https://docs.pmnd.rs/react-three-fiber) — 3D graphics
- [Framer Motion](https://www.framer.com/motion/) — animations
- [Tailwind CSS](https://tailwindcss.com/) — styling
- [EmailJS](https://www.emailjs.com/) — contact form
- [Vite](https://vitejs.dev/) — build tool

---

## 🚀 Deploy Your Own

### 1. Fork & Clone
\`\`\`bash
git clone https://github.com/YOUR_USERNAME/YOUR_USERNAME.github.io.git
cd YOUR_USERNAME.github.io
\`\`\`

### 2. Install Dependencies
\`\`\`bash
npm install
\`\`\`

### 3. Set Up Environment Variables
\`\`\`bash
cp .env.example .env.local
\`\`\`

Fill in your keys in `.env.local`:
\`\`\`
VITE_EMAILJS_SERVICE_ID=your_service_id
VITE_EMAILJS_TEMPLATE_ID=your_template_id
VITE_EMAIL_JS_ACCESS_TOKEN=your_public_key
VITE_RECAPTCHA_SITE_KEY=your_recaptcha_key
\`\`\`

> Get EmailJS keys at [emailjs.com](https://emailjs.com)  
> Get reCAPTCHA key at [google.com/recaptcha](https://www.google.com/recaptcha/admin)

### 4. Run Locally
\`\`\`bash
npm run dev
\`\`\`

### 5. Build & Deploy to GitHub Pages
\`\`\`bash
npm run build
npx gh-pages -d dist
\`\`\`

Then go to your repo **Settings → Pages → Branch → gh-pages → Save**.

---

## ✏️ Customize

All personal info (name, experience, education, projects, skills) is in one file:

\`\`\`bash
src/constants/index.js
\`\`\`

---

## 📬 Contact

- 📧 [Badr@moondiscoveries.com](mailto:Badr@moondiscoveries.com)
- 💼 [linkedin.com/in/badr-el-ghazaoui](https://linkedin.com/in/badr-el-ghazaoui)
- 🐙 [github.com/BadrrElGhazaoui](https://github.com/BadrrElGhazaoui)

---

> Forked from [sunnypatell/react-threejs-portfolio](https://github.com/sunnypatell/react-threejs-portfolio) and customized.

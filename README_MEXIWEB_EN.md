
# 🚀 MexiWeb

**MexiWeb** is a digital agency that builds modern, optimized, and visually appealing websites. This repository contains the source code of the official site, built with Astro and ready for deployment on Netlify.

---

## 📦 Technologies

- ⚡ Astro
- 🎨 TailwindCSS
- 🌐 Netlify (Deployment)
- 🧠 Basic SEO optimization
- 🧩 Custom SVG icons and favicons

---

## 🚧 Getting Started Locally

### 1. Clone the repository

```bash
git clone https://github.com/your-user/mexiweb.git
cd mexiweb
```

### 2. Install dependencies

```bash
npm install
```

### 3. Run the local server

```bash
npm run dev
```

Visit: [http://localhost:4321](http://localhost:4321)

---

## 🚀 Deploy on Netlify

1. **Push the project to GitHub** (if not already done).
2. **Go to [Netlify](https://app.netlify.com/)** and choose "Import from Git".
3. **Select your repository**.
4. **Set the following build settings:**
   - Build command: `npm run build`
   - Publish directory: `dist`
5. **Done!** Netlify will build and deploy your site.

> Make sure the `netlify.toml` file is in the root directory.

---

## 📁 Project Structure

```
📁 public/              → Public assets (icons, images, favicon, etc.)
📁 src/
 ┣ 📁 components/       → Reusable Astro components
 ┣ 📁 layouts/          → Base layout with global slot
 ┣ 📁 pages/            → All site pages (index, contact, etc.)
 ┣ 📁 styles/           → Custom styles
📄 astro.config.mjs     → Astro config
📄 tailwind.config.js   → Tailwind config
📄 netlify.toml         → Netlify deployment config
📄 package.json         → Dependencies and scripts
```

---

## ✨ Credits

Project developed by [Augusto Bernabé](https://www.linkedin.com/achinchurreta), founder of [MexiWeb](https://mexiweb.com), and creator of **Stuntlife**, a biker community with +40K followers.

---

## 📬 Contact

Have a project or idea? Contact us at: **contacto@mexiweb.com**

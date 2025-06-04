

## 🚀 Publishing Your Hugo Site to GitHub Pages

This project is built with **Hugo** and uses **GitHub Pages** for deployment.

### ✅ How to Publish Updates

Follow these steps whenever you want to publish a new version of the website:

---

### 1. **Build the Static Site**

In the root of your Hugo project (where `hugo.toml` lives), run:

```bash
hugo
```

This will generate the updated static site in the `public/` folder.

---

### 2. **Deploy to GitHub Pages**

If you're publishing from the `gh-pages` branch:

```bash
cd public
git add .
git commit -m "Publish updated site"
git push origin gh-pages
cd ..
```

If you're deploying from the `main` branch (e.g., using `/docs`):

```bash
git add .
git commit -m "Update site content and styling"
git push origin main
```

---

### 3. **Wait for GitHub Pages to Rebuild**

It usually takes about 30–60 seconds. Then visit your site:

📍 **[https://yuvalbloch.com](https://yuvalbloch.com)**

---

### 4. **Confirm GitHub Pages Settings**

Go to your repo → **Settings** → **Pages**:

* **Source:** should be `gh-pages` (or `main/docs`, if configured that way)
* **Custom domain:** `yuvalbloch.com`
* ✅ Make sure it says: **"Your site is live"**

---

### 🔁 Need to Rebuild?

If you make changes to the theme, content, or config files, just repeat the steps above.

---

Let me know if you want this styled as a Hugo page or included in a PDF cheat sheet.

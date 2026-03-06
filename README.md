# Roots Consulting Website

This is the static HTML website for Roots Consulting, ready to deploy on **GitHub Pages** for free.

---

## 📁 Files

| File | Description |
|------|-------------|
| `index.html` | Home page |
| `about.html` | About Us page |
| `impact.html` | Impact Fund page |
| `services.html` | Services page |
| `apply.html` | Apply page |
| `contact.html` | Contact page |
| `style.css` | All styles (shared across pages) |
| `nav.js` | Mobile menu toggle |

---

## 🚀 How to Deploy on GitHub Pages

### Step 1 — Create a GitHub Repository
1. Go to [github.com](https://github.com) and sign in (create a free account if needed)
2. Click the **+** button → **New repository**
3. Name it exactly: `rootsconsulting` (or any name you like)
4. Make it **Public**
5. Click **Create repository**

### Step 2 — Upload the Files
1. In your new repository, click **uploading an existing file**
2. Drag and drop ALL the files from this folder (index.html, about.html, impact.html, services.html, apply.html, contact.html, style.css, nav.js)
3. Click **Commit changes**

### Step 3 — Enable GitHub Pages
1. Go to your repository **Settings**
2. Click **Pages** in the left sidebar
3. Under **Source**, select **Deploy from a branch**
4. Under **Branch**, select `main` and folder `/root`
5. Click **Save**

Your site will be live at: `https://yourusername.github.io/rootsconsulting`

---

## 🌐 Connect Your Custom Domain

1. In **Settings → Pages**, enter your domain (e.g. `rootsconsulting.com`) in the **Custom domain** field
2. Click **Save**
3. At your domain registrar (where you bought the domain), add these DNS records:

**For apex domain (rootsconsulting.com):**
```
Type: A    Name: @    Value: 185.199.108.153
Type: A    Name: @    Value: 185.199.109.153
Type: A    Name: @    Value: 185.199.110.153
Type: A    Name: @    Value: 185.199.111.153
```

**For www subdomain:**
```
Type: CNAME    Name: www    Value: yourusername.github.io
```

DNS changes can take up to 24 hours to propagate.

---

## ✉️ Contact Form

The contact form uses [FormSubmit.co](https://formsubmit.co) (free). The first time someone submits the form, you'll receive a confirmation email at `rootsconsulting2025@gmail.com` to activate it. No account needed.

---

## ✏️ Making Updates

To update content, simply edit the relevant HTML file and re-upload it to GitHub. The site will update within seconds.

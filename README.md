# Zexplore GeoConsult — Website

**Live URL:** https://zexploregeoconsult.com

---

## 📁 Folder Structure

```
zexploregeoconsult/
├── index.html        ← Main website file
├── images/           ← Put ALL your photos here
│   └── about.jpg     ← About Us section photo (add this!)
└── README.md
```

---

## 📸 How to Add Your About Us Photo

1. Save your photo as `images/about.jpg` (also supports `.png` or `.webp`)
2. Open `index.html` in a text editor
3. Find this block (search for "PLACEHOLDER"):
   ```html
   <!-- PLACEHOLDER — remove this div when you have your photo -->
   <div class="about-img-placeholder"> ... </div>
   ```
4. **Delete** that entire `<div class="about-img-placeholder">` block
5. **Uncomment** the line below it:
   ```html
   <!-- <img src="images/about.jpg" alt="Zexplore GeoConsult team at work" /> -->
   ```
   → Remove the `<!--` and `-->` so it becomes:
   ```html
   <img src="images/about.jpg" alt="Zexplore GeoConsult team at work" />
   ```
6. Save and push to GitHub ✅

---

## 🚀 GitHub Pages Deployment (Step by Step)

### First Time Setup

1. **Create a GitHub account** at https://github.com if you don't have one

2. **Create a new repository**
   - Go to https://github.com/new
   - Repository name: `zexploregeoconsult` (or any name you like)
   - Set to **Public**
   - Click **Create repository**

3. **Upload your files**
   - Click **"uploading an existing file"** link on the new repo page
   - Drag and drop `index.html` and the `images/` folder
   - Click **Commit changes**

4. **Enable GitHub Pages**
   - Go to your repo → **Settings** → **Pages** (left sidebar)
   - Under **Source**, select **Deploy from a branch**
   - Branch: `main` | Folder: `/ (root)`
   - Click **Save**

5. **Connect your custom domain** (`zexploregeoconsult.com`)
   - Still in Settings → Pages, enter your domain in the **Custom domain** field
   - Click **Save**
   - Go to your domain registrar (where you bought the domain)
   - Add these DNS records:

   | Type  | Name | Value               |
   |-------|------|---------------------|
   | A     | @    | 185.199.108.153     |
   | A     | @    | 185.199.109.153     |
   | A     | @    | 185.199.110.153     |
   | A     | @    | 185.199.111.153     |
   | CNAME | www  | your-username.github.io |

6. Wait 10–30 minutes for DNS to propagate. Your site will be live! 🎉

---

## ✏️ Common Edits

| What to change | Where in index.html |
|---|---|
| Phone numbers | Search `8981629749` |
| Email address | Search `zexplore.geoconsult` |
| Stats (100+, 50+) | Search `stat-num` |
| Services text | Search `service-card` |
| About Us text | Search `about-content` |

---

*Built for Zexplore GeoConsult · www.zexploregeoconsult.com*

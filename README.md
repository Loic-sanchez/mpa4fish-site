# MP4Fish — Project Website

This repository contains the source files for the MP4Fish project website, built with [Jekyll](https://jekyllrb.com/) and hosted on [GitHub Pages](https://pages.github.com/).

---

## 🚀 How to publish this site (step by step)

### Step 1 — Create a GitHub account
If you don't already have one, go to [github.com](https://github.com) and sign up for a free account.

### Step 2 — Create a new repository
1. Click the **+** button in the top right → **New repository**
2. Name it: `mp4fish-site` (or any name you like)
3. Set it to **Public**
4. Click **Create repository**

### Step 3 — Upload the files
1. In your new repository, click **Add file** → **Upload files**
2. Drag and drop all the files from this folder:
   - `_config.yml`
   - `index.md`
   - `about.md`
   - `team.md`
   - `news.md`
   - `contact.md`
   - `README.md`
3. Click **Commit changes**

### Step 4 — Enable GitHub Pages
1. Go to your repository → **Settings** (top menu)
2. In the left sidebar, click **Pages**
3. Under **Source**, select **Deploy from a branch**
4. Under **Branch**, select `main` and `/ (root)`
5. Click **Save**

### Step 5 — Your site is live! 🎉
After a minute or two, your site will be available at:
```
https://YOUR-GITHUB-USERNAME.github.io/mp4fish-site/
```

> ⚠️ Don't forget to update `_config.yml` with your actual GitHub username in the `url` field.

---

## ✏️ How to edit the site

Each `.md` file corresponds to a page:

| File | Page |
|------|------|
| `index.md` | Home |
| `about.md` | About the Project |
| `team.md` | Partners & Team |
| `news.md` | News & Results |
| `contact.md` | Contact |

To edit a page:
1. Click on the file in GitHub
2. Click the **pencil icon** (Edit)
3. Make your changes
4. Click **Commit changes**

The site updates automatically within a minute.

---

## 🎨 Changing the theme

The site uses Jekyll's default `minima` theme. You can change it in `_config.yml`:
```yaml
theme: minima
```

Other themes supported by GitHub Pages: `cayman`, `slate`, `minimal`, `leap-day`, `time-machine`, `merlot`, `hacker`.
See the full list at [pages.github.com/themes](https://pages.github.com/themes/).

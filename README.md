# Lia Jun — Portfolio

Personal portfolio site. Deployed with **GitHub Pages**.

## Live site

After you push to GitHub and turn on Pages, your site will be at:

- **https://liaj7.github.io/liajun.com/**

(Your live site: **https://liaj7.github.io/liajun.com/**)

## Hero photo

The hero section uses `IMG_3326.JPG`. To show your photo online, add that file to this folder (same folder as `index.html`) and commit it.

## Deploy with GitHub Pages

### 1. Set Git identity (one-time, if not already set)

```bash
git config --global user.email "liabia927@gmail.com"
git config --global user.name "Your Name"
```

### 2. Create a new repo on GitHub

- Go to [github.com/new](https://github.com/new).
- Name it e.g. `portfolio` or `lia-jun`.
- Leave "Add a README" **unchecked**. Create the repo.

### 3. Commit and push (run in this project folder)

Git is already initialized and `index.html` + `README.md` are staged. Run:

```bash
git commit -m "Add portfolio site"
git branch -M main
git remote add origin https://github.com/liaj7/liajun.com.git
git push -u origin main
```

(Using username `liaj7` and repo `liajun.com`.)

### 4. Turn on GitHub Pages

- On the repo page: **Settings → Pages** (left sidebar).
- Under **Source**, choose **Deploy from a branch**.
- Branch: **main**, Folder: **/ (root)**. Click **Save**.

### 5. Your shareable link

After 1–2 minutes your site will be live at:

**https://liaj7.github.io/liajun.com/**

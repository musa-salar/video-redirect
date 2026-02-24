# Video Redirect

A simple, free URL redirect solution using GitHub Pages.

## 🎯 Purpose

This repository creates a static redirect link that you can share. When people visit your GitHub Pages URL, they'll automatically be redirected to your YouTube video (or any other URL you specify).

## 🚀 Setup Instructions

### 1. Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the **+** icon in the top right and select **New repository**
3. Name it something like `video-redirect` or `video`
4. Make it **Public**
5. Click **Create repository**

### 2. Upload Files

1. In your new repository, click **Add file** → **Upload files**
2. Upload the `index.html` file from this folder
3. Commit the changes

### 3. Enable GitHub Pages

1. Go to your repository **Settings**
2. Scroll down to **Pages** section (in the left sidebar)
3. Under **Source**, select **main** branch
4. Click **Save**
5. Wait a few minutes for deployment

### 4. Get Your URL

Your redirect will be available at:
```
https://YOUR-USERNAME.github.io/video-redirect/
```

For example: `https://johnsmith.github.io/video-redirect/`

## 🔄 How to Update the Video

To change where the redirect points:

1. Go to your repository on GitHub
2. Click on `index.html`
3. Click the **pencil icon** (Edit this file)
4. Find **both** instances of the YouTube URL:
   - In the `<meta http-equiv="refresh"...>` tag (around line 5)
   - In the `window.location.href` line (around line 36)
   - In the fallback link (around line 29)
5. Replace with your new URL
6. Click **Commit changes**

Changes typically take 1-2 minutes to go live.

## 💡 Tips

- **Short URL**: You can use a custom domain or GitHub's URL shortening
- **Multiple Redirects**: Create multiple HTML files like `video1.html`, `video2.html` etc.
- **Analytics**: Add Google Analytics or other tracking codes to see click statistics
- **Custom Domain**: Configure a custom domain in GitHub Pages settings for branded URLs

## 📝 Current Video

Currently redirects to: `https://youtu.be/PitWyNSm6r8`

---

**Free, no expiration, full control!** 🎉

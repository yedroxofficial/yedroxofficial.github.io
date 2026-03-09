# Yedrox — Static Website (GitHub Pages)

This repository contains the Yedrox one-page site with your provided logo and background.

Required image files
- images/yedrox-logo.png  — logo (use the logo image you uploaded)
- images/yedrox-bg.jpg    — background/theme image (use the large artwork)

How to publish (quick steps)
1. Create the repository on GitHub named exactly: `yedroxofficial/yedroxofficial.github.io`.
   - If you prefer, create it via the GitHub web UI: New → Repository → set the name above → Public.
2. Add the files above to the repository root and create an `images/` folder with the two image files listed above.
3. Local git push (recommended):
   ```bash
   git init
   git add .
   git commit -m "Initial Yedrox site with logo and background"
   git branch -M main
   git remote add origin https://github.com/yedroxofficial/yedroxofficial.github.io.git
   git push -u origin main
   ```
4. Because this is a user site repository named `yedroxofficial.github.io`, GitHub Pages will serve the site automatically at:
   > https://yedroxofficial.github.io/
   Wait a few minutes for the site to become live.
5. Optional: In the repository Settings → Pages you can confirm the site source (should be main / root) and see the public URL.

Image optimization tips
- Resize and compress `yedrox-bg.jpg` for faster page loads. Aim for ~200–400 KB for good quality on desktop; create a smaller mobile version if desired.
- Provide a transparent PNG or SVG for the logo if you need crisp edges on different backgrounds.

If you want me to create and push the repo for you
- I can create it and push these files if you either:
  - Add me as a collaborator to your GitHub account, or
  - Provide explicit temporary access to create the repo (web UI invite).
- Otherwise follow the steps above and tell me when you’ve pushed; I’ll verify the live site and do final CSS tweaks if needed.
# Personal Portfolio

A clean, minimalist personal portfolio website built with plain HTML, CSS, and JavaScript. Designed to showcase my projects, skills, and experience.

## Features

- **Responsive Design** — Looks great on desktop, tablet, and mobile
- **Smooth Animations** — Fade-in effects on scroll
- **Sticky Navigation** — Fixed navbar with active section highlighting
- **Mobile Menu** — Hamburger menu for small screens
- **Fast & Lightweight** — No frameworks, no build step, no dependencies

## Sections

- **Hero** — Introduction and call to action
- **About** — Brief bio and background
- **Projects** — Showcase of work with links to demos and source code
- **Skills** — Technical skills organized by category
- **Resume** — Work experience and education timeline
- **Contact** — Email, GitHub, and LinkedIn links

## Getting Started

Simply open `index.html` in a browser — no build step required.

## Customization

1. Edit `index.html` to update your personal information, projects, and links
2. Customize colors and fonts in `style.css` (CSS variables at the top)
3. Replace placeholder content with your own details

## Deploying to GitHub Pages

1. Push this repository to GitHub (already done ✅)
2. Go to **Settings** → **Pages** in your repository
3. Under **Build and deployment**, select **Source**: "Deploy from a branch"
4. Set the branch to `master` and folder to `/` (root)
5. Wait a few minutes — GitHub will build and deploy your site
6. Your site will initially be available at `https://jakaboliver.github.io/Personal-website/`

## Custom Domain (jakaboliver.hu)

A `CNAME` file is already included in this repository for custom domain support.

1. After enabling GitHub Pages (steps above), go to **Settings** → **Pages**
2. Under **Custom domain**, enter `jakaboliver.hu` and click **Save**
3. In your domain registrar's DNS settings for `jakaboliver.hu`, add the following records:
   - **A record**: Point `@` to GitHub's IPs:
     - `185.199.108.153`
     - `185.199.109.153`
     - `185.199.110.153`
     - `185.199.111.153`
   - **CNAME record** (for `www`): Point `www` to `JakabOliver.github.io`
4. Check the **Enforce HTTPS** box in GitHub Pages settings after DNS propagates (may take up to 48 hours)
5. Your site will then be live at `https://jakaboliver.hu`

## License

This project is open source and available for personal use.

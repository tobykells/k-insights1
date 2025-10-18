# K Insights - Expert Network Platform

This is the source code for the K Insights expert network website, built with Astro.js and Tailwind CSS.

## ⚠️ Important: Replace Placeholder Logo

The current logo (`public/images/logo.svg`) is a **temporary placeholder**. Please replace it with your actual K Insights logo:

1. Add your logo file to `public/images/` (can be .png, .jpg, or .svg)
2. If using a different filename or format, update the reference in `src/components/Header.astro`

## Project Structure

- `src/pages/` - Website pages
  - `index.astro` - Homepage with hero section
  - `client.astro` - For Clients page
  - `expert.astro` - Join Expert Network page
  - `contact.astro` - Contact form
  - `login.astro` - Login page
- `src/components/` - Reusable components (Header, Footer, etc.)
- `src/layouts/` - Page layouts with Gowun Batang font
- `public/` - Static assets (images, etc.)
- `netlify/` - Netlify-specific functions and configurations

## Customization

The website uses:
- **Font**: Gowun Batang (from Google Fonts)
- **Colors**: 
  - Primary Dark: `#221d1e`
  - Accent: `#a06372`
- **Framework**: Astro v5.14.3 with React integration
- **Styling**: Tailwind CSS v4

## Development Commands

All commands are run from the root of the project:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:5000`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |

## Pushing to GitHub

This code is ready to push to: **`https://github.com/tobykells/k-insights1`**

### Option 1: Using Replit's Git Panel (Recommended)

1. Click the **Version Control** icon in the left sidebar (branch icon)
2. Click **Connect to GitHub** if not already connected
3. Select your `k-insights1` repository
4. Stage your changes (click + next to files you want to commit)
5. Write a commit message (e.g., "Initial K Insights website")
6. Click **Commit & Push**

### Option 2: Using Shell Commands

```bash
git remote set-url origin https://github.com/tobykells/k-insights1.git
git add .
git commit -m "Initial K Insights website"
git push -u origin main
```

## Deploying to Netlify

After pushing to GitHub:

1. Log into your [Netlify dashboard](https://app.netlify.com)
2. Click "Add new site" → "Import an existing project"
3. Connect to GitHub and select your `k-insights1` repository
4. Netlify will auto-detect the build settings from `netlify.toml`
5. Click "Deploy site"

Your site will be live in a few minutes!

## What This Repository Contains

This is a **recreation of your deployed K Insights website** with fully editable source code:

✅ All K Insights branding and content  
✅ Custom navigation (Clients, Experts, Contact, Log in)  
✅ Your color scheme and typography  
✅ All page layouts from your deployment  
✅ Proper Astro source files (not just built HTML)  

Now you can:
- Edit the code in Replit
- Push changes to GitHub
- Deploy updates to Netlify
- Maintain full control over your website

## Need Help?

- [Astro Documentation](https://docs.astro.build)
- [Netlify Documentation](https://docs.netlify.com)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)

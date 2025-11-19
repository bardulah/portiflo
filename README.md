# Portiflo - Interactive Portfolio Website

A modern, animated portfolio website starter with party vibes!

## Features

- Smooth scroll animations
- Interactive project cards
- Particle effects background
- Responsive design
- No build tools required - pure HTML/CSS/JS

## Getting Started

Simply open `index.html` in your browser!

```bash
# Or use a local server
python -m http.server 8000
# Then visit http://localhost:8000
```

## Customization

Edit the following sections in `index.html`:
- Your name and bio in the hero section
- Projects in the portfolio grid
- Contact information in the footer

Customize colors and animations in `styles.css`!

## Party Mode

Click the party button for some extra fun! 🎉

## Deployment

This is a static site with no build process required, making it easy to deploy anywhere!

### GitHub Pages

1. Push your code to a GitHub repository
2. Go to repository Settings > Pages
3. Under "Build and deployment", select "GitHub Actions" as the source
4. The included workflow will automatically deploy on push to main/master

Alternatively, you can select "Deploy from a branch" and choose your main branch.

### Netlify

**Option 1: Using Netlify CLI**
```bash
# Install Netlify CLI
npm install -g netlify-cli

# Deploy
netlify deploy --prod
```

**Option 2: Using Netlify UI**
1. Go to [netlify.com](https://netlify.com) and sign in
2. Click "Add new site" > "Import an existing project"
3. Connect your git repository
4. Netlify will automatically detect the configuration from `netlify.toml`
5. Click "Deploy site"

**Option 3: Drag and Drop**
1. Go to [netlify.com/drop](https://app.netlify.com/drop)
2. Drag the entire project folder
3. Your site is live instantly!

### Vercel

**Option 1: Using Vercel CLI**
```bash
# Install Vercel CLI
npm install -g vercel

# Deploy
vercel --prod
```

**Option 2: Using Vercel UI**
1. Go to [vercel.com](https://vercel.com) and sign in
2. Click "Add New Project"
3. Import your git repository
4. Vercel will automatically detect the static site
5. Click "Deploy"

### Other Platforms

Since this is a simple static site, you can deploy it anywhere:

- **Cloudflare Pages**: Connect your repo and deploy
- **AWS S3 + CloudFront**: Upload files to S3 bucket with static hosting
- **Azure Static Web Apps**: Deploy via GitHub Actions or Azure Portal
- **DigitalOcean App Platform**: Connect repo and deploy
- **Surge.sh**: Run `surge` in the project directory

## Live Demo

Once deployed, your portfolio will be live at:
- GitHub Pages: `https://yourusername.github.io/portiflo/`
- Netlify: `https://your-site-name.netlify.app`
- Vercel: `https://your-project-name.vercel.app`

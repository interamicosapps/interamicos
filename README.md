# Inter Amicos LLC Website

A professional landing page for Inter Amicos LLC, built with HTML and CSS.

## Overview

This is a simple, static website designed to meet Apple App Store requirements for business verification. It includes information about Inter Amicos LLC and the Bar Fest mobile application.

## Files

- `index.html` - Main landing page
- `global.css` - Design system and styling
- `README.md` - This file

## Local Development

To view the website locally:

1. Clone or download this repository
2. Open `index.html` in a web browser
3. Or use a local server:
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Node.js (if you have http-server installed)
   npx http-server
   ```
4. Navigate to `http://localhost:8000` in your browser

## Deployment Options

### Option 1: GitHub Pages (Recommended)

**Prerequisites:**
- GitHub account
- Git installed on your computer

**Steps:**

1. Create a new repository on GitHub (e.g., `inter-amicos-website`)

2. Initialize git in your project folder:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   ```

3. Connect to your GitHub repository:
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/inter-amicos-website.git
   git branch -M main
   git push -u origin main
   ```

4. Enable GitHub Pages:
   - Go to your repository on GitHub
   - Click **Settings** → **Pages**
   - Under **Source**, select **main** branch and **/ (root)** folder
   - Click **Save**
   - Your site will be available at `https://YOUR_USERNAME.github.io/inter-amicos-website`

5. **Add Custom Domain** (after purchasing):
   - In the same Pages settings, enter your custom domain (e.g., `interamicos.com`)
   - Add a `CNAME` file to your repository root with your domain name
   - Configure DNS records at your domain registrar:
     - Add an A record pointing to GitHub Pages IPs: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
     - Or add a CNAME record pointing to `YOUR_USERNAME.github.io`
   - Wait for DNS propagation (can take up to 48 hours)

### Option 2: Netlify

**Prerequisites:**
- Netlify account (free)
- GitHub account (optional, for automatic deployments)

**Steps:**

1. **Option A: Drag and Drop**
   - Go to [netlify.com](https://netlify.com) and sign up/login
   - Drag and drop your project folder onto the Netlify dashboard
   - Your site will be live immediately at a `your-site-name.netlify.app` URL

2. **Option B: Connect GitHub** (Recommended for updates)
   - Push your code to GitHub (see GitHub Pages steps 1-3)
   - Go to Netlify dashboard → **Add new site** → **Import an existing project**
   - Connect your GitHub repository
   - Netlify will automatically deploy your site

3. **Add Custom Domain** (after purchasing):
   - Go to **Site settings** → **Domain management**
   - Click **Add custom domain**
   - Enter your domain name
   - Follow Netlify's DNS configuration instructions
   - Netlify will automatically provision SSL certificate

### Option 3: Vercel

**Prerequisites:**
- Vercel account (free)
- GitHub account (optional)

**Steps:**

1. Install Vercel CLI (optional):
   ```bash
   npm i -g vercel
   ```

2. **Option A: Via CLI**
   - Run `vercel` in your project directory
   - Follow the prompts

3. **Option B: Via GitHub**
   - Push your code to GitHub
   - Go to [vercel.com](https://vercel.com) and sign up/login
   - Click **Add New Project**
   - Import your GitHub repository
   - Vercel will automatically deploy

4. **Add Custom Domain** (after purchasing):
   - Go to **Project Settings** → **Domains**
   - Add your custom domain
   - Configure DNS as instructed by Vercel

## Domain Registration

To meet Apple App Store requirements, you'll need to purchase a custom domain. Recommended options:

### Recommended Registrars

1. **Namecheap** (~$10-12/year for .com)
   - Visit [namecheap.com](https://namecheap.com)
   - Search for `interamicos.com` or `interamicosllc.com`
   - Complete purchase

2. **Cloudflare Registrar** (~$8-10/year for .com)
   - At-cost pricing (no markup)
   - Visit [cloudflare.com](https://cloudflare.com/products/registrar)

3. **Google Domains** (~$12/year for .com)
   - Visit [domains.google](https://domains.google)

### Domain Name Suggestions

- `interamicos.com`
- `interamicosllc.com`
- `interamicos-llc.com`

## Updating Content

To update the website content:

1. Edit `index.html` with your preferred text editor
2. Update contact information (replace placeholders):
   - Email: `contact@interamicos.com`
   - Phone: `(123) 456-7890`
   - Business Address
3. Commit and push changes:
   ```bash
   git add .
   git commit -m "Update contact information"
   git push
   ```
4. Changes will automatically deploy (if using GitHub Pages, Netlify, or Vercel with GitHub integration)

## Apple App Store Requirements

This website meets Apple's requirements:

- ✅ Publicly accessible website
- ✅ Domain matches organization (once custom domain is configured)
- ✅ Shows legitimate business information
- ✅ Professional appearance
- ✅ Contact information displayed

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

Copyright © Inter Amicos LLC. All rights reserved.

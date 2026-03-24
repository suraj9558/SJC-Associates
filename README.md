# SJC & Associates – Website

## 🚀 Deploy on Vercel (Free)

1. Create account at https://vercel.com
2. Install Vercel CLI: `npm install -g vercel`
3. In this folder, run: `vercel`
4. Follow prompts → your site goes live instantly!

OR via GitHub:
1. Push this folder to a GitHub repo
2. Go to vercel.com → "New Project" → Import your repo
3. Click Deploy → Done!

## 🌐 Deploy on Netlify (Free)

1. Go to https://netlify.com → "Add new site"
2. Drag & drop this entire folder onto the page
3. Your site is live in seconds!

## 📁 Deploy on any Web Hosting (cPanel/GoDaddy/Hostinger)

1. Upload `index.html` to your `public_html` folder via File Manager or FTP
2. Upload `vercel.json` as well (optional, only needed for Vercel)
3. Point your domain `sjcassociates.in` to the hosting

## Files in this package:
- `index.html` — Complete website (self-contained, no external dependencies except Google Fonts)
- `vercel.json` — Vercel deployment config
- `README.md` — This file

## Custom Domain (sjcassociates.in):
After deploying on Vercel → Project Settings → Domains → Add `sjcassociates.in`
Then update your domain's DNS: Add CNAME record pointing to `cname.vercel-dns.com`

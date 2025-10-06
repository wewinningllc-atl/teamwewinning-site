# Team We Winning — Static Site

This is the static website for **Team We Winning** — streetwear, events, and culture.

## 🚀 Deployment
- Hosted on **GitHub Pages**
- Branch: `main`
- Folder: `/` (root)

GitHub Pages automatically deploys whenever changes are pushed to `main`.

Live URL:  
[https://wewinningllc-atl.github.io/teamwewinning-site/](https://wewinningllc-atl.github.io/teamwewinning-site/)

Custom domain: **teamwewinning.com**

## 🔧 Editing Content
- `index.html` → Site layout and scripts
- `config.json` → Products, events, and tagline
- `README.md` → Project documentation

### Products
- Classic Tees → $25
- Hats → $25
- Limited Edition Tees → $45
- Hoodies (Unseen Atlanta & Team We Winning) → $45
- Limited Edition Hoodies → $60

### Events
- Managed in `config.json` under `"events"`
- Events with past dates are automatically hidden
- Add new events with `date`, `title`, `where`, `time`, and `href` for ticket links

## 📝 Commit Flow
1. Update `config.json` for new products/events
2. Commit changes with clear messages
3. GitHub Pages auto-deploys in ~1 minute
4. Verify live site and custom domain

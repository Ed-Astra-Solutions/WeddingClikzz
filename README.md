# WeddingClikz - User Frontend

This is the customer-facing booking interface for WeddingClikz.

## GitHub Pages Deployment

1. Create a new GitHub repository (e.g., `weddingclikz-user` or use your main domain repo)

2. **Update the API URL** in `index.html`:
   - Find the line: `const API_BASE = 'https://your-backend-server.com';`
   - Replace with your actual backend URL (e.g., `https://api.weddingclikz.com`)

3. Push all files to the repository:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR_ORG/YOUR_REPO.git
   git push -u origin main
   ```

4. Enable GitHub Pages:
   - Go to repository Settings → Pages
   - Source: Deploy from branch
   - Branch: main, / (root)
   - Save

5. Your site will be available at:
   - `https://YOUR_ORG.github.io/YOUR_REPO/`
   - Or configure a custom domain

## Custom Domain Setup

1. Add a `CNAME` file with your domain:
   ```
   www.weddingclikz.com
   ```

2. Configure DNS:
   - Add a CNAME record pointing to `YOUR_ORG.github.io`
   - Or A records pointing to GitHub's IPs

## Files

- `index.html` - Main booking application
- `logo.png` - WeddingClikz logo
- `slider_1.png`, `slider_2.png` - Background images
- `favicon.ico`, `apple-touch-icon.png` - Favicons

# Deploying MPOP to GitHub Pages

## Step-by-Step (5 minutes)

### 1. Create GitHub Account
Go to https://github.com and sign up free.

### 2. Create New Repository
- Click the **+** icon (top right) → **New repository**
- Repository name: `mpop`
- Set to **Public**
- Do NOT initialize with README (we have our own)
- Click **Create repository**

### 3. Upload Files
On the repository page:
- Click **"uploading an existing file"**
- Drag and drop the entire `MPOP_Site` folder contents
- Write commit message: `Initial release — MPOP v1.0.0`
- Click **Commit changes**

### 4. Enable GitHub Pages
- Go to **Settings** tab of your repository
- Scroll to **Pages** section in left sidebar
- Under **Source**: select `Deploy from a branch`
- Branch: `main` | Folder: `/ (root)`
- Click **Save**

### 5. Your Site is Live!
After 1-2 minutes, your site will be at:
```
https://yourusername.github.io/mpop
```

---

## Custom Domain (Optional)

To use your own domain (e.g. getmpop.com):

1. Buy domain at Namecheap (~$10/year)
2. In GitHub Pages settings, add your custom domain
3. In Namecheap DNS settings, add:
   - Type: CNAME
   - Host: www
   - Value: yourusername.github.io
4. Wait 10-30 minutes for DNS to propagate

---

## Updating the Site

To update after changes:
1. Go to your GitHub repository
2. Click the file you want to update (e.g. `index.html`)
3. Click the pencil ✏️ icon to edit
4. Make changes → Commit
5. Site updates automatically in ~1 minute

---

## Support
📧 we.kurtsaz@gmail.com

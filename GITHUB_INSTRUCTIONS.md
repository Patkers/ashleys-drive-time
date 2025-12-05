# How to Put Ashley's Drive Time on GitHub

## Option 1: Using GitHub Website (Easiest!)

### Step 1: Create a GitHub Account
1. Go to https://github.com
2. Click "Sign up" (if you don't have an account)
3. Follow the signup process

### Step 2: Create a New Repository
1. Click the "+" icon (top right) → "New repository"
2. Repository name: `ashleys-drive-time`
3. Description: "Real-time travel time calculator with interactive maps"
4. Choose "Public" (so it can be hosted free)
5. Check "Add a README file"
6. Click "Create repository"

### Step 3: Upload Your Files
1. Click "Add file" → "Upload files"
2. Drag and drop OR click "choose your files"
3. Select these files from the unzipped folder:
   - index.html
   - README.md
   - SETUP_GUIDE.md
   - .gitignore
4. Scroll down, add commit message: "Initial commit"
5. Click "Commit changes"

### Step 4: Enable GitHub Pages (Make it Live!)
1. Click "Settings" tab (top of repository)
2. Click "Pages" in left sidebar
3. Under "Source" → Select "main" branch
4. Click "Save"
5. Wait 1-2 minutes
6. Your site will be live at: `https://YOUR-USERNAME.github.io/ashleys-drive-time/`

🎉 Done! Your app is now live on the internet!

---

## Option 2: Using Git Command Line (Advanced)

### Prerequisites
- Install Git: https://git-scm.com/downloads
- Have a GitHub account

### Steps

1. **Unzip the file**
   ```bash
   unzip ashleys-drive-time.zip
   cd ashleys-drive-time
   ```

2. **Initialize Git**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Ashley's Drive Time"
   ```

3. **Create GitHub Repository**
   - Go to https://github.com/new
   - Name: `ashleys-drive-time`
   - DON'T initialize with README (you already have one)
   - Click "Create repository"

4. **Push to GitHub**
   ```bash
   git remote add origin https://github.com/YOUR-USERNAME/ashleys-drive-time.git
   git branch -M main
   git push -u origin main
   ```

5. **Enable GitHub Pages**
   - Go to repository Settings → Pages
   - Source: main branch
   - Save

---

## Important Notes

### Before Making Public
⚠️ **REMOVE YOUR API KEY** before uploading to GitHub!

1. Open `index.html`
2. Find line 399: `const API_KEY = 'AIzaSy...'`
3. Change it to: `const API_KEY = 'YOUR_API_KEY_HERE';`
4. Save and upload

Add this to your README:
```markdown
## Setup Required
This app requires a Google Maps API key. See SETUP_GUIDE.md for instructions.
```

### Why Remove the API Key?
- Your API key should stay private
- Public keys can be abused by others
- Could cost you money if misused
- Anyone visiting your GitHub can see public files

### Alternative: Environment Variables (Advanced)
You can use GitHub Secrets with GitHub Actions, but that's more complex. For a simple static site, just have users add their own key.

---

## Updating Your App

### Via GitHub Website:
1. Click the file you want to edit
2. Click the pencil icon (Edit)
3. Make changes
4. Scroll down → "Commit changes"

### Via Git Command Line:
```bash
git add .
git commit -m "Description of changes"
git push
```

Changes will appear on your live site in 1-2 minutes!

---

## Sharing Your App

Once it's on GitHub Pages, share this link:
`https://YOUR-USERNAME.github.io/ashleys-drive-time/`

People can:
- Use it directly (if they add their own API key via browser console)
- Fork your repo and add their own key
- Clone it for local use

---

## Need Help?

- GitHub Docs: https://docs.github.com
- Git Basics: https://git-scm.com/doc
- GitHub Pages: https://pages.github.com

Good luck! 🚀

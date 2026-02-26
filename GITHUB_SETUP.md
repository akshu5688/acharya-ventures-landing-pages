# Push to GitHub & Deploy on Vercel

## Step 1: Create GitHub Repository

1. Go to **https://github.com/new**
2. Repository name: `acharya-ventures-landing-pages` (or any name you prefer)
3. Description: `Acharya Ventures & Startup Gurukul landing pages`
4. Choose **Public**
5. **Do NOT** check "Add a README" or any other files
6. Click **Create repository**

## Step 2: Push Your Code

In terminal, run (replace `YOUR_USERNAME` with your GitHub username):

```bash
cd "c:\Users\aksha\OneDrive\Desktop\Acharya Ventures 2 Landing Page"

git remote add origin https://github.com/YOUR_USERNAME/acharya-ventures-landing-pages.git
git branch -M main
git push -u origin main
```

If prompted, sign in with your GitHub credentials or use a Personal Access Token.

## Step 3: Deploy on Vercel

1. Go to **https://vercel.com** and sign in (use "Continue with GitHub")
2. Click **Add New** → **Project**
3. Import your `acharya-ventures-landing-pages` repository
4. Vercel will auto-detect it as a static site
5. Click **Deploy**

Your site will be live at `https://your-project.vercel.app`

---

**Already done:** Git is initialized, all files are committed, ready to push.

# Setup Instructions for Privacy Policy GitHub Pages

## Step 1: Create GitHub Repository

1. Go to: https://github.com/new
2. Fill in the details:
   - **Repository name:** `Privacy-Guardian-Policy`
   - **Description:** `Privacy policy for Privacy Guardian Android app`
   - **Visibility:** ✅ **PUBLIC** (required for free GitHub Pages)
   - **Initialize:** ❌ Do NOT check any boxes (no README, no .gitignore, no license)
3. Click **Create repository**

## Step 2: Push Local Code to GitHub

After creating the repo, GitHub will show you commands. Use these instead:

```bash
cd /c/Sarowar/ASTREON-TOP/Privacy-Guardian-Policy
git remote add origin https://github.com/CodeRover98/Privacy-Guardian-Policy.git
git branch -M main
git push -u origin main
```

## Step 3: Enable GitHub Pages

1. Go to your new repository: https://github.com/CodeRover98/Privacy-Guardian-Policy
2. Click **Settings** tab
3. Click **Pages** in the left sidebar
4. Under "Build and deployment":
   - **Source:** Deploy from a branch
   - **Branch:** main
   - **Folder:** / (root)
5. Click **Save**
6. Wait 1-2 minutes for deployment

## Step 4: Get Your Privacy Policy URL

After GitHub Pages is enabled, your privacy policy will be live at:

**https://coderover98.github.io/Privacy-Guardian-Policy/**

## Step 5: Update Contact Email (Before Going Live)

1. Open `index.html`
2. Find: `privacy@example.com`
3. Replace with your actual email
4. Commit and push:
   ```bash
   git add index.html
   git commit -m "Update contact email"
   git push
   ```

## What You'll Have

✅ Public privacy policy repository (only policy, no app code)
✅ Main app code stays private in Personal-Data-Broker repo
✅ Free GitHub Pages hosting
✅ Professional URL for Play Store submission
✅ Easy to update anytime

---

**Ready?** Follow Steps 1-4 now, then let me know when it's live!

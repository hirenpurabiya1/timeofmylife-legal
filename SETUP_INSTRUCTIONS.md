# Setup Instructions for GitHub Pages

## Step 1: Create GitHub Repository

1. Go to: https://github.com/new
2. Repository name: `timeofmylife-legal`
3. Description: `Legal pages (Privacy Policy & Terms of Service) for Time of My Life app`
4. **Visibility**: Select **Public** ✅
5. **DO NOT** initialize with README (we already have files)
6. Click **Create repository**

## Step 2: Push Files to GitHub

Run these commands in the `timeofmylife-legal` directory:

```bash
cd "/Users/hirenpurabiya/Documents/AI Tech Startups/apps/timeofmylife-legal"

# Add your GitHub username (replace with your actual username)
git remote add origin https://github.com/hirenpurabiya1/timeofmylife-legal.git

# Push to GitHub
git branch -M main
git push -u origin main
```

## Step 3: Enable GitHub Pages

1. Go to your repository: https://github.com/hirenpurabiya1/timeofmylife-legal
2. Click **Settings** (top menu)
3. Scroll down to **Pages** (left sidebar)
4. Under **Source**, select:
   - **Branch**: `main`
   - **Folder**: `/ (root)`
5. Click **Save**

## Step 4: Wait for Deployment

- GitHub will build your site (takes 1-2 minutes)
- You'll see a green checkmark when ready
- Your site URL will be: `https://hirenpurabiya1.github.io/timeofmylife-legal/`

## Step 5: Verify URLs Work

Test these URLs in your browser:

- **Privacy Policy**: https://hirenpurabiya1.github.io/timeofmylife-legal/privacy-policy.html
- **Terms of Service**: https://hirenpurabiya1.github.io/timeofmylife-legal/terms-of-service.html

Both should show formatted, readable pages.

## Step 6: Use in Oura Form

Once URLs are working, use them in your Oura application form:

- **Privacy Policy URL**: `https://hirenpurabiya1.github.io/timeofmylife-legal/privacy-policy.html`
- **Terms of Service URL**: `https://hirenpurabiya1.github.io/timeofmylife-legal/terms-of-service.html`
- **Redirect URI**: `timeofmylife://oura/callback`

## ✅ Done!

Your legal pages are now hosted publicly, and your main code repository stays private!


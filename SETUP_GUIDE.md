# Quick Setup Guide

Follow these steps to get your portfolio live in 30 minutes!

## 📋 What You Have

You now have all these files ready:
1. ✅ `index.html` - Your complete portfolio website
2. ✅ `README.md` - Documentation
3. ✅ `.gitignore` - Git configuration
4. ✅ This setup guide

## 🎯 What You Need

- [ ] GitHub account ([create one](https://github.com/join))
- [ ] Your profile photo (300x300px minimum, square format)
- [ ] 30 minutes of time

## 🚀 Step-by-Step Setup

### Step 1: Prepare Your Files (10 minutes)

#### 1.1 Create Folder Structure

On your computer, create this structure:

```
[yourusername].github.io/
├── index.html
├── README.md
├── .gitignore
└── assets/
    └── images/
        └── profile.jpg
```

**Example:** If your GitHub username is `kumam`, create folder named `kumam.github.io`

#### 1.2 Save the Files

1. **Copy `index.html`** → Save to root folder
2. **Copy `README.md`** → Save to root folder
3. **Copy `.gitignore`** → Save to root folder
4. **Add your profile photo**:
   - Name it exactly: `profile.jpg`
   - Place in: `assets/images/profile.jpg`
   - Must be square (1:1 ratio)
   - Recommended: 500x500px

#### 1.3 Customize index.html

Open `index.html` in a text editor and find/replace:

| Find | Replace With |
|------|--------------|
| `[Your Name]` | Your actual name |
| `[yourusername]` | Your GitHub username |
| `your.email@example.com` | Your email |
| `{'<YN />'}` | Your initials (like `{'<JD />'}`) |

**Quick customization checklist:**
- [ ] Line ~17: Update page title
- [ ] Line ~130: Update logo with your initials
- [ ] Line ~143-145: Update social media links
- [ ] Line ~151: Update email
- [ ] Line ~158-161: Update hero section text
- [ ] Line ~184-200: Update about text
- [ ] Line ~222-280: Update experience section
- [ ] Line ~295-350: Update projects
- [ ] Line ~370-410: Update skills
- [ ] Line ~429: Update email

---

### Step 2: Create GitHub Repository (5 minutes)

#### 2.1 Go to GitHub

1. Visit [github.com](https://github.com)
2. Sign in to your account
3. Click the **"+"** icon (top right)
4. Select **"New repository"**

#### 2.2 Configure Repository

- **Repository name:** `[yourusername].github.io`
  - ⚠️ Must be EXACTLY this format
  - Example: `kumam.github.io`
- **Description:** "Personal portfolio website"
- **Visibility:** ✅ Public (required for free GitHub Pages)
- **Initialize:** ✅ Check "Add a README file"
- Click **"Create repository"**

---

### Step 3: Upload Your Files (10 minutes)

#### Method A: Using GitHub Web Interface (Easiest)

**3.1 Upload index.html**
1. In your repository, click **"Add file"** → **"Upload files"**
2. Drag `index.html` or click to browse
3. Scroll down, add message: `Add portfolio website`
4. Click **"Commit changes"**

**3.2 Create assets folder and upload photo**
1. Click **"Add file"** → **"Upload files"**
2. In the "Name your file..." box, type: `assets/images/`
3. Now drag/upload your `profile.jpg`
4. Commit message: `Add profile photo`
5. Click **"Commit changes"**

**3.3 Update README**
1. Click on `README.md` in your repo
2. Click the **pencil icon** ✏️ (Edit)
3. Delete default content
4. Paste your customized README content
5. Commit message: `Update README`
6. Click **"Commit changes"**

**3.4 Add .gitignore**
1. Click **"Add file"** → **"Create new file"**
2. Name it: `.gitignore`
3. Paste the .gitignore content
4. Commit message: `Add gitignore`
5. Click **"Commit changes"**

#### Method B: Using Git (Advanced)

```bash
cd path/to/[yourusername].github.io
git init
git add .
git commit -m "Initial portfolio commit"
git remote add origin https://github.com/[yourusername]/[yourusername].github.io.git
git branch -M main
git push -u origin main
```

---

### Step 4: Enable GitHub Pages (2 minutes)

1. In your repository, click **"Settings"** tab
2. Scroll down left sidebar to **"Pages"**
3. Under **"Source"**:
   - Select: **"Deploy from a branch"**
   - Branch: **"main"**
   - Folder: **"/ (root)"**
4. Click **"Save"**

🎉 You'll see: "Your site is live at https://[yourusername].github.io"

---

### Step 5: Wait and Verify (3 minutes)

1. **Wait 5-10 minutes** for initial deployment
   - GitHub needs time to build and deploy
   - This only happens on first deployment
   - Future updates take 1-2 minutes

2. **Check deployment status**:
   - Go to repository **"Actions"** tab
   - Should see a green checkmark ✅
   - Or orange dot 🟠 (still deploying)

3. **Visit your site**: `https://[yourusername].github.io`

4. **Test everything**:
   - [ ] Page loads correctly
   - [ ] Profile image displays
   - [ ] Navigation works
   - [ ] All links work
   - [ ] Mobile menu works (resize browser)
   - [ ] Smooth scrolling functions

---

## ✅ Post-Launch Checklist

### Content Verification
- [ ] All `[placeholders]` replaced
- [ ] Profile photo shows correctly
- [ ] Email link opens mail client
- [ ] Social media links go to correct profiles
- [ ] No typos in text
- [ ] All experience/projects filled in

### Technical Verification
- [ ] Site loads in under 3 seconds
- [ ] Works on mobile phone
- [ ] Works in Chrome, Firefox, Safari
- [ ] No console errors (F12 Dev Tools)
- [ ] Navigation smooth scrolls
- [ ] Mobile menu opens/closes

### SEO & Sharing
- [ ] Test share on LinkedIn (check preview)
- [ ] Page title shows in browser tab
- [ ] Profile photo has alt text
- [ ] Meta descriptions filled

---

## 🎨 Next Steps

### Immediate (Day 1)
1. **Share your portfolio**:
   - Update LinkedIn profile with URL
   - Add to email signature
   - Share announcement post
   - Add to resume

2. **Test thoroughly**:
   - Send link to 3 friends for feedback
   - Test on actual mobile device
   - Try different browsers

### Short-term (Week 1)
1. **Refine content**:
   - Improve project descriptions
   - Add more specific achievements
   - Quantify impact where possible

2. **Gather testimonials**:
   - Ask colleagues for recommendations
   - Add quotes to portfolio (optional)

### Long-term (Monthly)
1. **Regular updates**:
   - Add new projects
   - Update skills
   - Refresh experience section
   - Keep profile photo current

2. **Track performance**:
   - Add Google Analytics (optional)
   - Monitor visitor engagement
   - Update based on feedback

---

## 🔧 Common Issues & Solutions

### Issue: Site shows 404 error
**Solutions:**
- Wait 10 minutes (initial deployment takes time)
- Verify repository is Public
- Check repository name is exactly `[username].github.io`
- Ensure `index.html` is in root (not in subfolder)

### Issue: Profile image not showing
**Solutions:**
- Check path: Must be `assets/images/profile.jpg`
- Verify image actually uploaded to GitHub
- Check file name exactly (case-sensitive)
- Try hard refresh: Ctrl+F5 (Win) or Cmd+Shift+R (Mac)

### Issue: Changes not appearing
**Solutions:**
- Wait 1-2 minutes for deployment
- Hard refresh browser (Ctrl+F5 or Cmd+Shift+R)
- Try incognito/private browsing mode
- Clear browser cache
- Check Actions tab for deployment status

### Issue: Mobile menu not working
**Solutions:**
- Check JavaScript console (F12) for errors
- Ensure all HTML tags properly closed
- Verify Font Awesome loaded
- Test in different mobile browsers

### Issue: Links not working
**Solutions:**
- Check URLs are correct and complete
- For social links, use full URLs with `https://`
- Test each link individually
- Verify email link format: `mailto:your@email.com`

---

## 📚 Additional Resources

### Learning
- [GitHub Pages Docs](https://docs.github.com/en/pages)
- [HTML/CSS Tutorials](https://www.w3schools.com/)
- [Git Guide](https://rogerdudler.github.io/git-guide/)

### Tools
- [TinyPNG](https://tinypng.com/) - Compress images
- [Squoosh](https://squoosh.app/) - Image optimization
- [Can I Use](https://caniuse.com/) - Browser compatibility
- [PageSpeed Insights](https://pagespeed.web.dev/) - Performance testing

### Design Inspiration
- [DevFolio](https://devfolio.co/)
- [Awwwards](https://www.awwwards.com/websites/portfolio/)
- [GitHub Portfolio Sites](https://github.com/topics/portfolio-website)

---

## 🆘 Need Help?

### Quick Help
1. **Check this guide again** - Most issues covered above
2. **GitHub Community** - [github.community](https://github.community/)
3. **Stack Overflow** - Search "GitHub Pages" + your issue

### Can't Figure It Out?
- Double-check all file names (case-sensitive!)
- Verify repository settings (Public, Pages enabled)
- Wait full 10 minutes for initial deployment
- Try deleting and re-uploading files

---

## 🎉 Success!

Once your site is live:

1. **Celebrate!** 🎊 You just built and deployed a professional portfolio!

2. **Share everywhere**:
   - LinkedIn profile → Featured section
   - LinkedIn post with screenshot
   - Twitter/X bio
   - Email signature
   - GitHub profile README
   - Resume header

3. **Keep building**:
   - Your portfolio is never "done"
   - Update regularly with new projects
   - Keep skills current
   - Refresh content quarterly

---

**Questions or stuck?** Remember:
- Wait 10 minutes for initial deployment
- Hard refresh browser (Ctrl+F5)
- Check repository is Public
- Verify file paths are correct

**You've got this! 🚀**

---

Last updated: October 2025
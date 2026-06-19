# 🚀 YAKUZA Electric Scooters - GitHub Deployment Guide

Complete step-by-step guide to deploy your website on GitHub Pages for FREE hosting.

---

## 📋 Prerequisites

Before starting, you need:
- ✅ GitHub account (free at github.com)
- ✅ Your website HTML file (yakuza-deploy.html)
- ✅ Git installed on your computer (optional but recommended)

---

## ⚡ Quick Start (5 Minutes)

### Step 1: Create a GitHub Account (if you don't have one)

1. Go to **https://github.com**
2. Click **"Sign up"** button
3. Enter your email address
4. Create a password
5. Choose a username (e.g., `yakuza-godda`)
6. Complete the verification
7. Click **"Create account"**

---

### Step 2: Create a New Repository

1. After logging in, click the **"+"** icon in the top-right corner
2. Select **"New repository"**
3. Fill in the details:
   - **Repository name:** `yakuza-electric-scooters`
   - **Description:** "YAKUZA Electric Scooters - Radhe Motors Official Website"
   - **Visibility:** Select **"Public"** (important for GitHub Pages)
   - **Initialize with README:** Check this box
4. Click **"Create repository"**

---

### Step 3: Upload Your Website File

#### Method A: Using GitHub Web Interface (Easiest)

1. In your new repository, click **"Add file"** → **"Upload files"**
2. Drag and drop your `yakuza-deploy.html` file OR click to browse
3. In the filename field, change it to **`index.html`** (important!)
4. Scroll down and click **"Commit changes"**
5. Add a commit message: `"Add YAKUZA website"`
6. Click **"Commit changes"** button

#### Method B: Using Git Command Line

```bash
# Clone the repository to your computer
git clone https://github.com/YOUR-USERNAME/yakuza-electric-scooters.git

# Navigate to the folder
cd yakuza-electric-scooters

# Copy your HTML file and rename it to index.html
cp yakuza-deploy.html index.html

# Add the file to git
git add index.html

# Commit the changes
git commit -m "Add YAKUZA website"

# Push to GitHub
git push origin main
```

---

### Step 4: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **"Settings"** (top menu)
3. Scroll down to **"Pages"** section (left sidebar)
4. Under **"Source"**, select:
   - **Branch:** `main`
   - **Folder:** `/ (root)`
5. Click **"Save"**
6. Wait 1-2 minutes for GitHub to deploy

---

### Step 5: Access Your Live Website

Your website is now live! Access it at:

```
https://YOUR-USERNAME.github.io/yakuza-electric-scooters
```

**Example:**
- If your username is `radhe-motors`, your URL will be:
- `https://radhe-motors.github.io/yakuza-electric-scooters`

---

## 🎯 Verification Checklist

After deployment, verify everything works:

- ✅ Website loads without errors
- ✅ All images display correctly
- ✅ WhatsApp button works (opens WhatsApp)
- ✅ Phone button works (opens dialer)
- ✅ Forms are functional
- ✅ Mobile responsive design works
- ✅ All links navigate correctly

---

## 🔧 Making Updates to Your Website

### To Update Your Website:

1. **Edit the file locally** (on your computer):
   - Open `index.html` in a text editor
   - Make your changes
   - Save the file

2. **Upload the updated file to GitHub**:
   - Go to your repository
   - Click the `index.html` file
   - Click the **pencil icon** (Edit)
   - Make changes in the editor
   - Scroll down and click **"Commit changes"**

3. **Wait for deployment** (usually 1-2 minutes)

4. **Refresh your website** to see the changes

---

## 🌐 Connect a Custom Domain (Optional)

Want a professional domain like `yakuza-godda.com`? Follow these steps:

### Step 1: Purchase a Domain

Options:
- GoDaddy (godaddy.com)
- Namecheap (namecheap.com)
- Google Domains (domains.google.com)
- Hostinger (hostinger.com)

**Cost:** Usually ₹300-500/year

### Step 2: Configure Domain Settings

After purchasing, go to your domain provider's dashboard:

1. Find **DNS Settings** or **Nameservers**
2. Add these DNS records:

```
Type: A
Name: @
Value: 185.199.108.153

Type: A
Name: @
Value: 185.199.109.153

Type: A
Name: @
Value: 185.199.110.153

Type: A
Name: @
Value: 185.199.111.153

Type: CNAME
Name: www
Value: YOUR-USERNAME.github.io
```

### Step 3: Update GitHub Settings

1. Go to your repository **Settings** → **Pages**
2. Under **Custom domain**, enter your domain name
3. Click **"Save"**
4. Check **"Enforce HTTPS"**
5. Wait 5-10 minutes for DNS propagation

Your website will now be accessible at your custom domain!

---

## 📊 Monitoring Your Website

### Check GitHub Pages Status

1. Go to your repository
2. Click **"Settings"** → **"Pages"**
3. Look for the green checkmark and live URL

### View Deployment History

1. Go to your repository
2. Click **"Deployments"** (right sidebar)
3. See all deployment attempts and their status

---

## 🐛 Troubleshooting

### Website Not Loading?

**Problem:** Getting 404 error
- **Solution:** Make sure your file is named `index.html` (not `yakuza-deploy.html`)

**Problem:** Website loads but looks broken
- **Solution:** Clear your browser cache (Ctrl+Shift+Delete) and refresh

**Problem:** WhatsApp button not working
- **Solution:** Check internet connection and ensure WhatsApp is installed

### Changes Not Appearing?

1. Hard refresh your browser: **Ctrl+Shift+R** (Windows) or **Cmd+Shift+R** (Mac)
2. Clear browser cache
3. Wait 5 minutes for GitHub to rebuild
4. Check deployment status in Settings → Pages

---

## 📱 Mobile Optimization

Your website is already mobile-responsive! Test it:

1. Open your website on a mobile phone
2. Verify:
   - Text is readable
   - Buttons are clickable
   - Images display correctly
   - Forms work on mobile

---

## 🔐 Security & Best Practices

### GitHub Pages Security

✅ GitHub automatically provides HTTPS (secure connection)
✅ Your website is protected with SSL certificate
✅ Data is encrypted in transit

### Website Best Practices

1. **Backup your files** - Keep a local copy of your HTML file
2. **Version control** - Use meaningful commit messages
3. **Regular updates** - Keep your content fresh
4. **Monitor performance** - Check GitHub Pages status regularly

---

## 📈 Sharing Your Website

### Share on Social Media

**Facebook:**
```
Check out YAKUZA Electric Scooters at:
https://YOUR-USERNAME.github.io/yakuza-electric-scooters

Book your test ride today! 🏍️⚡
```

**WhatsApp:**
```
YAKUZA Electric Scooters - Radhe Motors
Visit our website: https://YOUR-USERNAME.github.io/yakuza-electric-scooters
Book test ride, check pricing, and more!
```

**Instagram Bio:**
```
🏍️ YAKUZA Electric Scooters
⚡ Eco-Friendly Mobility
🔗 [Your Website URL]
```

---

## 💡 Pro Tips

1. **Use a custom domain** - Looks more professional than github.io
2. **Add Google Analytics** - Track visitor statistics
3. **Optimize images** - Compress images for faster loading
4. **Update regularly** - Keep content fresh and current
5. **Test on mobile** - Ensure mobile-friendly experience

---

## 📞 Support & Help

### If You Get Stuck:

1. **GitHub Help:** https://docs.github.com/en/pages
2. **GitHub Community:** https://github.community
3. **Stack Overflow:** Search for your issue at stackoverflow.com

### Common Questions:

**Q: Is GitHub Pages hosting really free?**
A: Yes! GitHub Pages is completely free for public repositories.

**Q: Can I use a custom domain?**
A: Yes, you can connect any domain you own.

**Q: How long does deployment take?**
A: Usually 1-2 minutes after you commit changes.

**Q: Can I have multiple websites?**
A: Yes! Create multiple repositories and enable Pages for each.

---

## ✅ Final Checklist

Before considering your website live:

- [ ] Repository created on GitHub
- [ ] Website file uploaded as `index.html`
- [ ] GitHub Pages enabled
- [ ] Website accessible at your GitHub URL
- [ ] All links and buttons working
- [ ] Mobile responsive design verified
- [ ] WhatsApp integration tested
- [ ] Phone number link tested
- [ ] Website shared on social media
- [ ] Backup of HTML file saved locally

---

## 🎉 Congratulations!

Your YAKUZA Electric Scooters website is now live on GitHub Pages! 

**Next Steps:**
1. Share your website URL with customers
2. Add it to your business cards
3. Post on social media
4. Update it regularly with new information
5. Monitor visitor engagement

---

## 📞 Contact Information

**YAKUZA Electric Scooters - Radhe Motors**
- 📍 Opposite Van Heusen, Nahar Chowk Road, Godda
- 📞 +91 79923 81124
- 💬 WhatsApp: +91 79923 81124
- 🕐 Hours: 9:30 AM – 8:00 PM Daily

---

**Document Version:** 1.0
**Last Updated:** June 2026
**Status:** Ready for Deployment ✅

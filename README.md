# TheHeadChef Website

A professional mock website for TheHeadChef premium terpene wellness products, designed to showcase wax melts, room sprays, and nasal inhalers. Built for easy deployment on GitHub Pages.

## 🚀 Quick Start

### Step 1: Create GitHub Repository

1. Go to [GitHub.com](https://github.com) and sign in to your account
2. Click the "+" icon in the top-right corner and select "New repository"
3. Name your repository (e.g., `theheadchef-website`)
4. Make sure it's set to **Public** (required for free GitHub Pages)
5. Check "Add a README file"
6. Click "Create repository"

### Step 2: Upload Website Files

**Option A: Using GitHub Web Interface (Recommended for beginners)**

1. In your new repository, click "uploading an existing file"
2. Drag and drop all files from the `/site` folder:
   - `index.html`
   - `css/styles.css`
   - `js/script.js`
   - `images/` folder with all image files
3. Write a commit message: "Add TheHeadChef website files"
4. Click "Commit changes"

**Option B: Using Git Command Line**

```bash
# Clone your repository
git clone https://github.com/yourusername/theheadchef-website.git
cd theheadchef-website

# Copy all files from the /site folder to the repository root
# (Copy index.html, css/, js/, images/ folders)

# Add and commit files
git add .
git commit -m "Add TheHeadChef website files"
git push origin main
```

### Step 3: Enable GitHub Pages

1. In your repository, go to **Settings** (top menu)
2. Scroll down to **Pages** in the left sidebar
3. Under "Source", select **Deploy from a branch**
4. Choose **main** branch and **/ (root)** folder
5. Click **Save**
6. Wait 5-10 minutes for deployment

### Step 4: Access Your Live Website

Your website will be available at:
```
https://yourusername.github.io/theheadchef-website/
```

Replace `yourusername` with your actual GitHub username and `theheadchef-website` with your repository name.

## 📁 File Structure

```
site/
├── index.html              # Main website file
├── css/
│   └── styles.css          # All styling and responsive design
├── js/
│   └── script.js           # Interactive functionality
├── images/
│   ├── room-spray-placeholder.svg
│   ├── wax-melts-placeholder.svg
│   ├── nasal-inhaler-placeholder.svg
│   └── placeholder-generator.html
└── README.md               # This file
```

## 🎨 Design Features

### Inspired by terpenes-uk.co.uk:
- Clean, minimalist black and white design
- Professional typography using Inter font
- Grid-based product layout
- Responsive design for all devices
- Subtle hover effects and animations

### TheHeadChef Branding:
- Premium terpene wellness focus
- Product categories: Wax Melts, Room Sprays, Nasal Inhalers
- "Coming Soon" launch theme
- TikTok Challenge integration
- Professional investor-ready appearance

## 📱 Responsive Design

The website is fully responsive and tested for:
- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (320px - 767px)

## 🔧 Customization

### Updating Product Images
1. Replace the SVG placeholder files in `/images/` with your actual product photos
2. Ensure images are optimized for web (recommended: 600x600px, under 200KB each)
3. Update the image paths in `index.html` if needed

### Changing Colors
Edit `/css/styles.css` and modify these CSS variables:
```css
/* Primary colors */
#1a1a1a (Black)
#ffffff (White)
#f8f8f8 (Light gray)
#666666 (Medium gray)
```

### Adding Real Links
Replace placeholder links (`href="#"`) in:
- Navigation menu
- Social media links
- Footer links
- Contact information

### Email Integration
To make the newsletter form functional:
1. Sign up for a service like Mailchimp, ConvertKit, or Formspree
2. Replace the form action in the newsletter section
3. Update the JavaScript in `/js/script.js`

## 🌟 Features

### Interactive Elements:
- Mobile-friendly hamburger menu
- Smooth scrolling navigation
- Product notification buttons
- Newsletter subscription form
- Scroll-to-top button
- Custom notification system

### SEO Optimized:
- Semantic HTML structure
- Meta descriptions
- Alt tags for images
- Clean URL structure
- Fast loading times

## 🔄 Updates & Maintenance

### Regular Updates:
1. Replace placeholder images with real product photos
2. Update product information and pricing
3. Add real contact information
4. Connect social media accounts
5. Set up analytics (Google Analytics recommended)

### Before Launch:
- [ ] Replace all placeholder images
- [ ] Update contact information
- [ ] Set up social media accounts
- [ ] Configure email newsletter service
- [ ] Add Google Analytics
- [ ] Test all forms and links
- [ ] Optimize for search engines

## 🆘 Troubleshooting

### Website Not Loading:
- Check that GitHub Pages is enabled in repository settings
- Ensure `index.html` is in the root directory
- Wait 10-15 minutes after enabling GitHub Pages

### Images Not Showing:
- Verify image file paths are correct
- Check that images are uploaded to the repository
- Ensure image files are web-compatible formats (JPG, PNG, SVG)

### Mobile Menu Not Working:
- Check that `script.js` is properly linked
- Verify there are no JavaScript errors in browser console

## 📞 Support

For GitHub Pages specific issues:
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [GitHub Community Forum](https://github.community/)

For website customization:
- Refer to the code comments in each file
- Test changes locally before pushing to GitHub

## 🎯 Next Steps

1. **Content Updates**: Replace all placeholder content with real information
2. **Image Replacement**: Use high-quality product photography
3. **Form Integration**: Connect newsletter and contact forms
4. **Analytics**: Add Google Analytics for traffic monitoring
5. **SEO Optimization**: Add metadata and optimize for search engines
6. **Performance**: Optimize images and enable caching

---

**Ready to launch TheHeadChef to the world! 🚀**

*This website is designed to be investor-ready and professional from day one.*
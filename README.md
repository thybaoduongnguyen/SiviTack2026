# SiviHack 2026 - Hackathon Website

A modern, energetic single-page website for your hackathon, designed to be deployed on GitHub Pages.

## 🚀 Quick Deploy to GitHub Pages

### Option 1: New Repository
1. Create a new repository on GitHub (e.g., `my-hackathon`)
2. Upload `index.html` to the repository
3. Go to Settings → Pages
4. Under "Source", select "Deploy from a branch"
5. Select `main` branch and `/ (root)` folder
6. Click Save
7. Your site will be live at `https://yourusername.github.io/my-hackathon`

### Option 2: User/Organization Site
1. Create a repository named `yourusername.github.io` (must match exactly)
2. Upload `index.html` to the repository
3. Your site will automatically be live at `https://yourusername.github.io`

## ✏️ Customization Guide

### Basic Information
Edit the following sections in `index.html`:

1. **Hackathon Name** (Line 7, 38, and others)
   - Replace "HACKVISION" and "HackVision 2025" with your event name

2. **Event Details** (Lines 220-234)
   - Date: `September 25-27, 2026`
   - Location: `Frankfurt`
   - Participants: `100 Vietnamese Hackers`

3. **Tagline** (Line 218)
   - Change "36 hours of innovation, collaboration and creation"

4. **Stats** (Lines 267-286)
   - Update numbers for Hours, Participants, Prize Pool, Projects

5. **Schedule** (Lines 292-344)
   - Add/remove/edit schedule items with times and descriptions

6. **Prizes** (Lines 350-368)
   - Update prize amounts and descriptions

7. **FAQ** (Lines 373-388)
   - Customize questions and answers

8. **Contact Info** (Line 398)
   - Change email to `hello@hackvision.dev`

9. **Social Media Links** (Lines 392-397)
   - Update href="#" with your actual social media URLs

### Color Scheme
Change colors in the CSS variables (Lines 9-14):
```css
--primary: #00ff88;    /* Neon green */
--secondary: #ff0080;  /* Hot pink */
--dark: #0a0e27;       /* Dark blue background */
--light: #f0f4ff;      /* Light text */
--accent: #7b2cbf;     /* Purple accent */
```

### Fonts
Current fonts are:
- **Display**: Bebas Neue (headers)
- **Body**: JetBrains Mono (body text)

To change fonts, replace the Google Fonts link (Line 8) and update font-family values.

### Registration Button
Update the registration link (Line 237):
```html
<a href="#register" class="btn btn-primary">Register Now</a>
```
Replace `#register` with your actual registration form URL (e.g., Google Forms, Typeform, etc.)

## 🎨 Design Features

- **Animated gradient background** with glowing effects
- **Smooth scroll animations** that reveal sections
- **Responsive design** works on mobile, tablet, and desktop
- **Interactive hover effects** on cards and buttons
- **Grid overlay** for tech aesthetic
- **No external dependencies** - pure HTML/CSS/JS

## 📱 Mobile Responsive

The website is fully responsive and adapts to:
- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (320px - 767px)

## 🔧 Advanced Customization

### Add More Sections
Copy this template for a new section:
```html
<section id="new-section" class="reveal">
    <h2>Section Title</h2>
    <div class="about-content">
        <!-- Your content here -->
    </div>
</section>
```

### Change Animation Speed
Modify animation durations in the CSS:
```css
animation: slideUp 1s ease-out;  /* Change 1s to desired speed */
```

### Add Sponsors Section
Insert before the FAQ section:
```html
<section id="sponsors" class="reveal">
    <h2>Sponsors</h2>
    <div class="about-content">
        <!-- Add sponsor logos/cards here -->
    </div>
</section>
```

## 🐛 Troubleshooting

**Site not showing up?**
- Wait 5-10 minutes after enabling GitHub Pages
- Check repository settings → Pages
- Ensure file is named `index.html` (lowercase)

**Animations not working?**
- Clear browser cache
- Check browser console for errors

**Mobile layout broken?**
- Ensure viewport meta tag is present (Line 6)

## 📄 License

Free to use and modify for your hackathon event!

## 🤝 Need Help?

Feel free to customize this template however you need. The design is built to be easily modified while maintaining a strong visual identity.

---

**Built with**: HTML5, CSS3, Vanilla JavaScript
**Fonts**: Google Fonts (Bebas Neue, JetBrains Mono)
**No frameworks required** - just upload and deploy!

# 📊 Fairway Nine Mall - Tenant Calling Campaign Report

Interactive dashboard for analyzing Meta Ads performance for tenant recruitment campaigns at Fairway Nine Mall.

## 🎯 Campaign Overview

This dashboard provides comprehensive insights into two major tenant calling campaigns:
- **🎄 Frosty Christmas Market** (December 2025)
- **🧧 Golden Lunar Serenity** (January - February 2026)

**Target Audience**: Business owners and entrepreneurs interested in opening tenants/booths at mall events.

## 📈 Key Metrics Tracked

- **Budget Allocation & Usage**: Rp 500,000 total budget with detailed breakdown
- **Reach & Impressions**: Track audience exposure across campaigns
- **Click-Through Rates (CTR)**: Measure ad effectiveness
- **Cost Per Click (CPC)**: Optimize ad spending
- **Demographics Analysis**: Age and gender distribution of interested tenants
- **Ad Format Performance**: Compare static posts vs video ads

## 🚀 Features

- **Multi-page Navigation**: 3 interactive pages (Dashboard, Frosty Market, Golden Lunar)
- **Real-time Budget Tracking**: Visual budget bars with precise calculations
- **Demographic Insights**: Identify prime target audience segments
- **Performance Comparisons**: Side-by-side campaign analysis
- **Leads Evidence**: Direct link to inquiry screenshots documentation
- **Brand Customization**: Fairway Nine Mall color scheme
- **Responsive Design**: Works on desktop, tablet, and mobile

## 🎨 Brand Colors

```css
Primary:    #234748 (Dark Teal)
Title:      #A98250 (Gold)
Secondary:  #E7E3DB (Light Beige)
Accent:     #DAC2AA (Warm Beige)
```

## 📥 Installation

### Option 1: GitHub Pages (Recommended)

1. **Fork or Clone this repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/fairway-nine-campaign-report.git
   cd fairway-nine-campaign-report
   ```

2. **Enable GitHub Pages**
   - Go to repository Settings
   - Navigate to Pages section
   - Select branch: `main` (or `master`)
   - Select folder: `/ (root)`
   - Click Save

3. **Access your dashboard**
   ```
   https://YOUR_USERNAME.github.io/fairway-nine-campaign-report/
   ```

### Option 2: Local Development

1. **Download the HTML file**
   ```bash
   git clone https://github.com/YOUR_USERNAME/fairway-nine-campaign-report.git
   ```

2. **Open in browser**
   - Simply double-click `tenant-calling-campaign-report.html`
   - Or use a local server:
     ```bash
     python -m http.server 8000
     # Then visit: http://localhost:8000
     ```

## 🔧 Customization

### 1. Replace Logo

**Current line in HTML (around line 730):**
```html
<img src="YOUR_LOGO_URL_HERE" alt="Fairway Nine Mall" class="logo">
```

**Steps to add your logo:**

#### Option A: Using Imgur (Easiest)
1. Go to [imgur.com](https://imgur.com)
2. Upload your logo
3. Right-click image → "Copy image address"
4. Replace `YOUR_LOGO_URL_HERE` with the URL

#### Option B: Using GitHub
1. Create an `assets` folder in your repo
2. Upload logo: `assets/logo.png`
3. Replace with: `src="assets/logo.png"`

#### Option C: Using Google Drive
1. Upload logo to Google Drive
2. Right-click → Share → "Anyone with link can view"
3. Get file ID from share link
4. Use format: `https://drive.google.com/uc?export=view&id=FILE_ID`

**Example:**
```html
<img src="https://i.imgur.com/abcd1234.png" alt="Fairway Nine Mall" class="logo">
```

### 2. Update Campaign Data

To update with new campaign data, modify these sections in HTML:

**Budget Stats (around line 800):**
```html
<div class="budget-bar-value">Rp 500,000</div>
```

**Performance Metrics (around line 850):**
```html
<div class="stat-value">13,502</div> <!-- Update reach -->
<div class="stat-value">17,306</div> <!-- Update impressions -->
```

**Demographics (around line 950):**
```html
<div class="bar-fill" style="width: 38.8%;"> <!-- Update percentage -->
    <span class="bar-percentage">85 clicks</span> <!-- Update clicks -->
</div>
```

### 3. Customize Colors

Find the `:root` CSS variables (around line 30):
```css
:root {
    --primary: #234748;        /* Change main color */
    --title-gold: #A98250;     /* Change highlight color */
    --secondary-light: #E7E3DB;
    --secondary-warm: #DAC2AA;
}
```

### 4. Update Leads Evidence Link

Replace Google Drive link (around line 820):
```html
<a href="YOUR_GOOGLE_DRIVE_FOLDER_LINK" 
   target="_blank" 
   class="leads-evidence-button">
```

## 📊 Campaign Results Summary

### Overall Performance
- **Budget Efficiency**: 99.9996% utilization (Rp 2 remaining)
- **Total Reach**: 13,502 potential tenant owners
- **Total Engagement**: 219 clicks
- **Average CPC**: Rp 2,057

### Key Insights
✅ Female entrepreneurs (25-44) = 72% of engagement  
✅ Frosty Market: Higher CTR (2.08%) & lower CPC  
✅ Golden Lunar: 2.3x larger reach, better for scale  
⚠️ Conversion gap: 219 clicks with no lead capture

### Strategic Recommendations
1. Focus targeting on female entrepreneurs aged 25-44
2. Optimize landing page for lead conversion
3. Leverage seasonal events (Christmas, Lunar New Year)
4. Implement retargeting strategy for clickers
5. Static posts outperform video (85% clicks, lower CPM)

## 🛠️ Technology Stack

- **HTML5**: Structure and content
- **CSS3**: Styling and animations
- **Vanilla JavaScript**: Navigation and interactions
- **Google Fonts**: Typography (Outfit, Bebas Neue, Archivo Black)

## 📱 Browser Support

- ✅ Chrome/Edge (Recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🔒 Privacy & Security

- No external data collection
- No cookies or tracking
- All data is static (hardcoded in HTML)
- Google Drive link opens in new tab for security

## 📄 File Structure

```
fairway-nine-campaign-report/
├── tenant-calling-campaign-report.html  # Main dashboard file
├── README.md                            # This file
└── assets/                              # Optional: for images/logos
    └── logo.png                         # Your logo here
```

## 🤝 Contributing

This is a custom campaign report for Fairway Nine Mall. For modifications:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 Support

For questions or issues:
- Open an issue on GitHub
- Contact Fairway Nine Mall marketing team

## 📋 Changelog

### Version 1.0 (February 2026)
- Initial release
- Dashboard with 3 pages (Overview, Frosty Market, Golden Lunar)
- Budget tracking with tax breakdown
- Demographics and performance analysis
- Leads evidence integration
- Brand color customization

## 📝 License

This project is proprietary to Fairway Nine Mall. All rights reserved.

---

**Made with ❤️ for Fairway Nine Mall** | Last Updated: February 2, 2026

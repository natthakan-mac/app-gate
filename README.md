# BIO Application Portal

A modern, minimal web portal for BIO Thailand Group's application ecosystem. Built with vanilla HTML, CSS, and JavaScript for optimal performance and simplicity.

## 🌟 Features

- **Clean & Minimal Design** - White/dark theme with smooth transitions
- **iOS App Store-Style Modals** - Professional app preview with screenshots
- **Dark Mode Support** - Automatic theme switching with manual toggle
- **Responsive Layout** - Works seamlessly on desktop and mobile devices
- **Organized Categories** - Apps grouped by function (General, Stock & Inventory, CRM, IT, Production)
- **Interactive Help System** - Built-in tooltip with AppSheet instructions and contact information

## 📱 Applications

### General
- **Webmail** - Corporate email system

### Stock and Inventory
- **BIO IVM** - Inventory management for BIO Inno Tech
- **BIO TH IVM** - Factory inventory management for BIO Inno Tech (Thailand)
- **BIO Green World IVM** - Inventory management for BIO Green World

### Customer Relation Management
- **BIO CRM** - Sales reporting system for BIO Inno Tech

### IT
- **NMS Uptime Kuma** - Network monitoring system
- **Speedtest Tracker** - Internet speed monitoring

### Production
- **ERP NEXT** - Enterprise resource planning system

## 🚀 Quick Start

1. Clone the repository:
```bash
git clone https://github.com/yourusername/app-gate.git
cd app-gate
```

2. Open `index.html` in your browser:
```bash
# On Windows
start index.html

# On macOS
open index.html

# On Linux
xdg-open index.html
```

Or simply drag and drop `index.html` into your browser.

## 🎨 Customization

### Adding a New Application

1. Add the app icon to the `icons/` folder
2. Add screenshots to `screenshots/[app-name]/` folder
3. Update `index.html`:

```html
<!-- Add to the appropriate section -->
<a href="#" class="link" onclick="openModal('modalX'); return false;">
  <img src="icons/your-icon.png" alt="App Icon" class="link-icon">
  <div class="link-content">
    <div class="link-name">Your App Name</div>
    <div class="link-description">App description</div>
    <span class="appsheet-badge">AppSheet</span>
  </div>
</a>

<!-- Add modal -->
<div id="modalX" class="modal">
  <!-- Modal content here -->
</div>
```

### Changing Theme Colors

Edit CSS variables in the `:root` section:

```css
:root {
  --title: #00796b;
  --txt: #2b2b2b;
  --muted: #666;
  /* ... more variables */
}
```

## 📂 Project Structure

```
app-gate/
├── index.html          # Main application file
├── README.md           # Project documentation
├── icons/              # Application icons
│   ├── app1-icon.png
│   ├── app2-icon.png
│   └── ...
└── screenshots/        # Application screenshots
    ├── bio-ivm/
    ├── bio-th-ivm/
    └── ...
```

## 🛠️ Technologies

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS variables and animations
- **JavaScript** - Vanilla JS for interactions
- **Font Awesome 6.4.0** - Icon library
- **Google Fonts** - Noto Sans Thai font

## 🌐 Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License

© 2025 BIO Thailand Group. All rights reserved.

## 👥 Credits

**Developed by:** ITDS (Information Technology & Digital Services)  
**Organization:** BIO Thailand Group  
**Department:** ฝ่ายเทคโนโลยีสารสนเทศและบริการดิจิทัล

## 📞 Contact

- **Phone:** 096-926-7701
- **Email:** it@bioinnotech.co.th
- **Line OA:** [https://lin.ee/rEf6BGP](https://lin.ee/rEf6BGP)

---

Made with ❤️ by BIO Thailand Group ITDS Team

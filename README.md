# Advocate Subhangini Trivedi — Official Website

A modern, elegant, and fully responsive website for **Advocate Subhangini Trivedi**, designed for legal practice representation with a refined luxury aesthetic (Navy, Ivory & Gold).

![Website Preview](images/hero-advocate.jpg)

---

## 🌟 Key Features

- **📱 100% Mobile Responsive:** Optimized for all devices including small mobile screens (320px–360px), smartphones (iPhone, Galaxy, Pixel), tablets, and ultra-wide desktops.
- **⚡ Mobile Floating Action Bar:** Quick "Call Now" and "Consultation" buttons pinned on smartphones for immediate client inquiries.
- **🧭 Interactive Mobile Drawer Menu:** Smooth animated navigation drawer with direct contact buttons and outside-tap dismiss.
- **⚖️ Practice Areas Carousel:** Horizontal swipeable/draggable practice areas with interactive modal dialogs for details.
- **📜 Professional Timeline:** Dynamic scroll-progress timeline showing career milestones.
- **✨ 3D Hero Atmosphere:** Subtle 3D perspective hero with custom legal scales insignia and advocate portrait.
- **📝 Validated Consultation Form:** Client enquiry form with live client-side validation.
- **♿ Accessibility & Performance:** Safe-area insets for notched devices, reduced-motion preferences, tap target compliance, and zero dependencies.

---

## 📁 Project Structure

```
├── images/
│   ├── hero-advocate.jpg       # Advocate portrait for hero section
│   └── presence-green.jpg      # Traditional attire portrait
├── index.html                  # Single-file complete website (HTML, CSS, JS)
├── README.md                   # Project documentation
└── README.txt                  # Original developer notes
```

---

## 🚀 How to Run Locally

1. **Directly in Browser:**
   Double-click `index.html` to open it in any web browser (Chrome, Safari, Edge, Firefox).

2. **Using a Local Web Server:**
   ```bash
   # Using Python 3
   python -m http.server 8000

   # Using Node.js npx
   npx serve .
   ```
   Open [http://localhost:8000](http://localhost:8000) in your browser.

---

## ✏️ How to Customize Website Content

All site content is centralized in the `SITE` JavaScript object near the bottom of `index.html`:

```javascript
const SITE = {
  name: "Subhangini Trivedi",
  phone: "9335 157231",
  email: "your-email@example.com",
  location: "Add office location",
  // Update stats, practice areas, milestones & testimonials here
};
```

---

## 🌐 Deploy to GitHub Pages

1. Go to repository **Settings** on GitHub.
2. Select **Pages** in the left sidebar.
3. Under **Branch**, select `main` and `/ (root)`, then click **Save**.
4. Your website will be live in minutes at `https://<username>.github.io/<repository-name>/`.

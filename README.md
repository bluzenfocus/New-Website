# Bluzen Website

A static website for Bluzen — an online mental health service helping fast minds slow down and focus.

## 🌐 Live Site

This is a static website built with HTML, Tailwind CSS (via CDN), and Google Fonts. It's ready for deployment to any static hosting platform.

## 📁 Project Structure

```
New-Website/
├── index.html          # Home page - main landing page
├── program.html        # 8-Week Focus Program details and pricing
├── library.html        # Bluzen Library overview (client-only access)
├── about.html          # About Bluzen and how it works
├── privacy.html        # Privacy Policy
├── terms.html          # Terms of Service
├── 404.html            # Custom 404 error page
├── assets/
│   └── logo.svg        # Bluzen logo
└── README.md           # This file
```

## 🎨 Design & Technology

- **Framework**: Pure HTML with Tailwind CSS via CDN
- **Fonts**: Montserrat from Google Fonts
- **Color Scheme**: 
  - Primary: Bluzen teal (`#64DED4`)
  - Background: Dark (`#05070a`)
  - Text: Light (`#e6f0f2`)
- **Responsive**: Mobile-first design, fully responsive across devices
- **Browser Support**: Modern browsers (Chrome, Firefox, Safari, Edge)

## 🚀 Deployment

### GitHub Pages

1. Go to your repository settings
2. Navigate to **Pages** section
3. Select branch: `main` (or your preferred branch)
4. Select folder: `/ (root)`
5. Click **Save**
6. Your site will be available at `https://[username].github.io/New-Website/`

### Netlify

1. Sign in to [Netlify](https://www.netlify.com/)
2. Click **Add new site** → **Import an existing project**
3. Connect to your GitHub repository
4. Configure build settings:
   - **Build command**: (leave empty - no build needed)
   - **Publish directory**: `/` (root)
5. Click **Deploy site**
6. Your site will be live at a generated URL (customizable)

### Vercel

1. Sign in to [Vercel](https://vercel.com/)
2. Click **Add New** → **Project**
3. Import your GitHub repository
4. Configure project:
   - **Framework Preset**: Other
   - **Build Command**: (leave empty)
   - **Output Directory**: `./`
5. Click **Deploy**
6. Your site will be live at a generated URL (customizable)

### General Static Hosting

This site is pure HTML/CSS/JavaScript and can be deployed to any static hosting service:
- Upload all files to your hosting provider's public directory
- Ensure `index.html` is recognized as the default page
- Configure custom 404 page to use `404.html` (if supported)

## 🛠️ Local Development

No build process required! Simply:

1. Clone the repository:
   ```bash
   git clone https://github.com/bluzenfocus/New-Website.git
   cd New-Website
   ```

2. Open in your browser:
   - **Option 1**: Double-click `index.html`
   - **Option 2**: Use a local server (recommended):
     ```bash
     # Python 3
     python -m http.server 8000
     
     # Python 2
     python -m SimpleHTTPServer 8000
     
     # Node.js (if you have http-server installed)
     npx http-server
     ```
   - Navigate to `http://localhost:8000`

## ✏️ Adding/Editing Content

### Adding a New Page

1. Create a new HTML file in the root directory (e.g., `contact.html`)
2. Copy the structure from an existing page (like `about.html`)
3. Update the content within the `<main>` section
4. Add navigation links to your new page in the header/footer of all pages

### Adding Assets

- Place images, icons, or other assets in the `assets/` directory
- Reference them using relative paths: `assets/your-file.ext`

### Updating Styles

The site uses Tailwind CSS via CDN. To customize:
- Modify inline Tailwind classes in HTML
- Add custom CSS in the `<style>` section of each page
- To change the primary color, update the `bluzen` color value in the Tailwind config

## 📋 Pages Overview

- **index.html**: Main landing page with hero section, focus quiz placeholder, and program overview
- **program.html**: Detailed information about the 8-Week Focus Program, pricing, and FAQ
- **library.html**: Overview of the Bluzen Library (client-only digital resource)
- **about.html**: Information about Bluzen, what it is/isn't, and how it fits with therapy
- **privacy.html**: Privacy policy explaining data handling
- **terms.html**: Terms of service for using Bluzen
- **404.html**: Custom error page for missing pages

## 🔗 Navigation Structure

All pages include:
- **Header**: Logo, main navigation (Program, Library, About), and mobile menu
- **Footer**: Quick links, contact information, and legal links (Privacy, Terms)

## 📝 Placeholder Content

Some features are marked as "coming soon":
- Focus quiz embed (Typeform/Carrd integration)
- Email signup form (MailerLite integration)
- Booking calendar (Calendly or similar)
- Payment integration (Stripe/PayPal)

These can be added later by embedding the relevant service's code snippets.

## 🔒 Notes

- No backend or database required
- No build process needed
- All dependencies loaded via CDN (no npm/package management)
- Fully self-contained and portable

## 📧 Contact

For questions about the website: [info@bluzenfocus.com](mailto:info@bluzenfocus.com)

---

Built with ❤️ in Ireland | © 2024 Bluzen

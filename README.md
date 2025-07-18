# CEDR Consulting Website

Professional website for CEDR Consulting - Gaming & AML Risk Management Experts

## Project Structure

```
cedr-consulting-website/
├── index.html              # Main HTML file
├── assets/
│   ├── css/
│   │   └── styles.css      # All CSS styles
│   ├── js/
│   │   └── script.js       # JavaScript functionality
│   └── images/
│       ├── cedr-logo.png   # Add your logo here
│       └── favicon.ico     # Add your favicon here
├── README.md               # This file
└── .gitignore             # Git ignore file (optional)
```

## Setup Instructions

### 1. Local Development

1. **Clone the repository** (if you haven't already):
   ```bash
   git clone https://github.com/markkelly123/cedr-consulting-website.git
   cd cedr-consulting-website
   ```

2. **Add your logo**:
   - Place your CEDR logo as `assets/images/cedr-logo.png`
   - Recommended size: 200px wide, transparent background
   - The CSS will automatically resize it to fit the header

3. **Open in VS Code**:
   ```bash
   code .
   ```

4. **Preview locally**:
   - Install Live Server extension in VS Code
   - Right-click `index.html` → "Open with Live Server"
   - Or open `index.html` directly in your browser

### 2. Making Changes

**Edit content**: Modify `index.html`
**Edit styles**: Modify `assets/css/styles.css`
**Edit functionality**: Modify `assets/js/script.js`

### 3. Deploying Changes

After making changes:

```bash
# Check what's changed
git status

# Add all changes
git add .

# Commit with a message
git commit -m "Updated website content"

# Push to GitHub (auto-deploys to Vercel)
git push origin main
```

## Key Features

- **Responsive Design**: Works on desktop, tablet, and mobile
- **Professional Styling**: Modern gradient design with clean typography
- **Contact Form**: Integrated with Formspree for submissions
- **SEO Optimized**: Proper meta tags and structure
- **Fast Loading**: Optimized CSS and JavaScript
- **Easy to Edit**: Clean, commented code structure

## Common Tasks

### Adding New Content
- Edit `index.html` for content changes
- Edit `assets/css/styles.css` for style changes

### Changing Colors
- Main brand colors are defined in `styles.css`:
  - Primary: `#1e3c72` (dark blue)
  - Secondary: `#2a5298` (lighter blue)

### Adding Images
- Place images in `assets/images/`
- Reference them as `assets/images/filename.jpg`

### Updating Contact Form
- Form submits to: `https://formspree.io/f/mdkdkgqk`
- To change, update the `action` attribute in the form

## Deployment

- **GitHub**: [https://github.com/markkelly123/cedr-consulting-website](https://github.com/markkelly123/cedr-consulting-website)
- **Live Site**: Auto-deployed to Vercel from main branch
- **Any push to main automatically updates the live site**

## Support

For questions about the code or deployment, refer to this README or ask for assistance.
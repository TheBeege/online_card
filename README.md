# Online Business Card

A clean, Linktree-style business card website for Bryan Berry.

## Features

- Responsive design that works on all devices
- Clean, modern UI with gradient background
- SVG icons for all links
- QR code placeholder for easy updates
- Optimized for GitHub Pages hosting

## Deployment to GitHub Pages

1. Push this repository to GitHub
2. Go to your repository Settings
3. Navigate to Pages (under Code and automation)
4. Under "Source", select "Deploy from a branch"
5. Select the `main` branch and `/ (root)` folder
6. Click Save
7. Your site will be available at `https://yourusername.github.io/repository-name/`

## Updating the QR Code

To add your QR code:

1. Generate a QR code that points to your page URL
2. Save the QR code image (recommended: PNG format, 300x300px or larger)
3. Replace the QR code placeholder in `index.html`:

Replace this:
```html
<div class="qr-code-placeholder">
    <div class="qr-placeholder-text">QR Code</div>
</div>
```

With this:
```html
<div class="qr-code-placeholder">
    <img src="qr-code.png" alt="QR Code" style="width: 100%; height: 100%; border-radius: 16px;">
</div>
```

4. Add your QR code image file to the repository

## Customization

- Colors: Edit the gradient and theme colors in `styles.css`
- Links: Modify the links in `index.html`
- Icons: SVG icons are embedded and can be customized or replaced

## Files

- `index.html` - Main HTML structure
- `styles.css` - Styling and layout
- `README.md` - This file

## License

Free to use and modify as needed.

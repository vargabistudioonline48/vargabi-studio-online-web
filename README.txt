Vargabi Studio & Online — static website

Folder structure
vargabi-studio/
├── index.html
├── style.css
├── script.js
└── images/
    ├── logo/
    ├── services/
    └── gallery/

Local test
1. Keep the folder structure unchanged.
2. Open index.html directly in a browser.
3. For best browser behavior, you can also run: python -m http.server 8000
   from inside this folder, then open http://localhost:8000/

Deployment
- GitHub Pages: upload the folder contents to a repository and enable Pages.
- Render Static Site: connect the repository; publish directory is the repository root.
- Netlify: drag the whole folder (or a ZIP of it) into Netlify Drop.

All website images used by the original single-file build have been extracted into local WebP files; there are no image data-URI dependencies left in index.html or script.js. External links retained are WhatsApp, Google Maps, wa.me, and schema.org metadata.

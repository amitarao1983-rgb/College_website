# Deployment Package Guide

## Ready package
- File: `mrcp-website-deploy.zip`
- Contains: `index.html`, `mandatory-disclosure.html`, `styles.css`, and the full `assets` folder

## How to deploy
1. Open your hosting panel (cPanel/File Manager or FTP).
2. Go to your website root folder (`public_html` or equivalent).
3. Upload `mrcp-website-deploy.zip`.
4. Extract the zip in the same folder.
5. Confirm `index.html` is at root (not inside a nested folder).

## Post-deployment checklist
- Open home page and test all navigation links.
- Open `mandatory-disclosure.html` and verify PDF downloads.
- Verify images load in Facilities, Laboratories, Student Support, and Committees sections.
- Replace committee placeholder names with official names/designations.
- Update Google Map embed URL to exact college location pin if needed.

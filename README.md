# Best Buy Properties Portal

A unified real estate website for multiple property listings:

- `/eastwood.html` — Eastwood City Condo For Sale
- `/baesa.html` — Baesa Quezon City House & Lot For Sale
- `/san-juan.html` — San Juan Batangas Highway Lot For Sale

## Render Deployment

Use these settings:

- Runtime: Node
- Build Command: leave blank or use `echo no build needed`
- Start Command: `npm start`
- Node Version: 20

This is a static HTML/CSS/JS website with a simple Node server, so it avoids Next.js build dependency problems.

## Facebook Traffic URLs

- Eastwood: `https://your-domain.onrender.com/eastwood.html`
- Baesa: `https://your-domain.onrender.com/baesa.html`
- San Juan: `https://your-domain.onrender.com/san-juan.html`

Replace Messenger and phone links inside the HTML files if needed.


## V2 Portal Updates
- Homepage hero now uses a sliding image carousel for Eastwood, Baesa, and San Juan.
- San Juan location advantage text now has readable contrast.
- Eastwood, Baesa, and San Juan pages now include Google Maps embed sections.
- San Juan page includes both embedded Google map and locator-map image.

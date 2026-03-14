Happy Trails Pony Rides Website

A simple, fast single-page website built with Vite.

Quick Start

cd pony-website
npm install
npm run dev

Open http://localhost:5173 in your browser.

Build for Production

npm run build

The dist folder contains your deployable files.

Deploy to DigitalOcean

- Run npm run build

- Upload the dist folder contents to DigitalOcean Spaces or App Platform

Adding Your Own Photos

- Place images in public/images/

- Edit index.html - find the gallery section

-
Replace the image URLs with your own:

<img src="/images/your-photo.jpg" alt="Description">

Customizing Content

 What to Change File Location

 Business Name index.html Search "Happy Trails"

 Phone/Email index.html Contact section

 Services/Pricing index.html Services section

 Colors src/style.css :root variables at top

 About Text index.html About section

File Structure

pony-website/
├── index.html      # Main page (edit content here)
├── src/
│   ├── style.css   # All styles (colors, fonts, layout)
│   └── main.js     # Simple interactions
├── public/
│   └── images/     # Your photos go here
└── package.json

That's it! Simple and easy to maintain.
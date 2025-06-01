Vee Collection Website
Overview
Vee Collection is a single-page React.js website for a premium salon and barbershop offering nail, spa, and barber services. Inspired by zvinailsandspa.com, it features a responsive design with custom CSS, elegant animations, and a pink, black, and white color scheme for a luxurious experience. Includes WhatsApp integration and a demo booking form.
Features

Responsive Design: Custom CSS with media queries for mobile, tablet, and desktop.
Sections:
Home: Hero with call-to-action.
About: Team profiles and mission.
Services: Nail, spa, and barber services with pricing.
Promotions: Special offers.
Gallery: Image showcase with lightbox, featuring 12 unique nail, spa, and barber images.
Testimonials: Client reviews.
Booking: Demo appointment form.
Contact: Contact details with WhatsApp and map.


Animations: Fade-in and slide-in effects.
Color Scheme: Pink (#FF69B4, #FFF0F5), black (#000000), white (#FFFFFF).
WhatsApp: Contact via +254743652006.
Typography: "Great Vibes" font for branding.
Images: Optimized Unsplash images for gallery, team, and map; replace with custom visuals for branding.
Frontend-Only: Static content; booking form directs to phone/WhatsApp.

Project Structure
vee-collection/
├── src/
│   ├── components/
│   │   ├── Navbar.js       # Navigation with smooth scrolling
│   │   ├── Hero.js         # Hero section
│   │   ├── About.js        # About section with team
│   │   ├── Services.js     # Nail, spa, barber services
│   │   ├── Promotions.js   # Special offers
│   │   ├── Gallery.js      # Image gallery with lightbox
│   │   ├── Testimonials.js # Client testimonials
│   │   ├── Booking.js      # Demo booking form
│   │   ├── Contact.js      # Contact info and WhatsApp
│   │   ├── Footer.js       # Footer with links and socials
│   ├── data/
│   │   ├── servicesData.js     # Service data
│   │   ├── teamData.js         # Team data
│   │   ├── testimonialsData.js # Testimonial data
│   │   ├── promotionsData.js   # Promotion data
│   ├── App.js              # Main app with React Router
│   ├── index.js            # React entry point
│   ├── styles.css          # Custom CSS styles
├── README.md               # This file
├── package.json            # Dependencies and scripts

Prerequisites

Node.js (v16+)
npm or yarn

Setup Instructions

Create Project:
npx create-react-app vee-collection
cd vee-collection

Or with Vite:
npm create vite@latest vee-collection -- --template react
cd vee-collection


Install Dependencies:
npm install react-router-dom


Set Up Files:

Copy src/ files (App.js, index.js, styles.css, components/, data/) into the project’s src/ directory.
Place README.md in the root directory.
Ensure styles.css includes Google Fonts import.


Run the App:
npm start

Or for Vite:
npm run dev

Visit http://localhost:3000.

Customize:

Images: Replace Unsplash images in teamData.js, Gallery.js, and Contact.js with your own (optimize to <1MB, e.g., use ?w=800 for Unsplash).
Details: Update contact info in Contact.js and Footer.js.
Content: Edit servicesData.js, teamData.js, testimonialsData.js, promotionsData.js.



Customization Options

Backend: Add Node.js/Express, Firebase, or Calendly for booking in Booking.js.
Animations: Extend styles.css with keyframes or use Framer Motion.
SEO: Add meta tags in public/index.html.
Social Media: Update links in Footer.js.
Branding: Adjust colors or fonts in styles.css.

Technologies

React.js: Component-based frontend.
React Router: Section navigation.
Custom CSS: Responsive styling.
Google Fonts: "Great Vibes" typography.
Unsplash: Free, optimized images.

Notes

Booking form is a demo; integrate a backend for functionality.
WhatsApp uses +254743652006; verify or update.
Gallery images are unique and optimized; test locally to confirm loading.
Self-host Google Fonts for production.
If images fail to load, check URLs or network; replace with local assets if needed.

License
For demonstration; uses Unsplash images under their license. Replace for commercial use.

Contact the developer or repository issues for support.

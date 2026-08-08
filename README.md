MG Air Cargo Website

A responsive website developed for MG Air Cargo to provide a professional online presence and present information about the company's services.

Project Overview

The MG Air Cargo website is a static frontend project built using native web technologies.

The entire website is contained in a single HTML file. HTML, CSS, JavaScript, and the required image resources are included within the same file.

Technologies Used

- HTML5 — Structure and content
- CSS3 — Styling, layout, responsiveness, and animations
- JavaScript — Interactivity and client-side functionality
- Embedded Images — Visual content included within the HTML file

No frontend framework or backend server is required for the current version.

Project Structure

mg-air-cargo/
│
├── 📄 README.md
├── 🌐 index.html


"index.html"

The "index.html" file contains the complete website, including:

- HTML structure
- CSS styles
- JavaScript functionality
- Image resources

This approach keeps the project self-contained and easy to run.

Website Sections

The website includes:

- Navigation
- Hero section
- About section
- Services
- Contact section
- Footer

Features

Responsive Design

The website is designed to adapt to different screen sizes, including:

- Desktop
- Tablet
- Mobile

Interactive Elements

JavaScript provides client-side interactions throughout the website.

Visual Design

CSS is used to create the layout, typography, colors, spacing, responsive behavior, and visual effects.

Embedded Images

The images used by the website are included within the same HTML file rather than being stored in separate image files.

This means the website can be opened without needing a separate assets directory.

Architecture

The project follows a simple single-file architecture:

                MG AIR CARGO
                     │
                     ↓
                 index.html
                     │
          ┌──────────┼──────────┐
          ↓          ↓          ↓
         HTML       CSS    JavaScript
          │          │          │
          ↓          ↓          ↓
      Structure   Design   Interaction
                     │
                     ↓
              Embedded Images

How to Run

No installation or package manager is required.

Simply open:

index.html

in a modern web browser.

The complete website is contained in this file.

Deployment

Because the project is a static website, it can be deployed using static hosting platforms such as GitHub Pages, Netlify, or Vercel.

Advantages of the Single-File Approach

Keeping the project in one file makes it:

- Easy to share
- Easy to run
- Easy to demonstrate
- Portable
- Simple to deploy

Limitations

As the website becomes larger, maintaining HTML, CSS, JavaScript, and images in one file can become difficult.

For a larger version of the project, the structure could eventually be separated into:

index.html
css/style.css
js/script.js
assets/images/

Future Improvements

Possible future improvements include:
- Optimize image assets
- Add backend functionality
- Add cargo tracking
- Add online quotation requests
- Add a database
- Add an admin dashboard
- Add analytics

Project Status

Status: Completed

Author

Goodluck Prosper 

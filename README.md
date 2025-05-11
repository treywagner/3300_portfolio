# 3300_portfolio
Repository for my portfolio project

# Trey Wagner – Portfolio Website

This is a personal portfolio website created for a class project at the University of Iowa. It serves as both a demonstration of front-end web development skills and a platform to showcase my background, interests, and resume.

---

## 📌 Overview

- **Name:** Trey Wagner  
- **School:** University of Iowa  
- **Degrees:** B.A. in Accounting and Business Analytics & Information Systems  
- **Graduation:** December 2025  
- **Tools Used:** HTML, CSS (with Bootstrap), Font Awesome, Google Analytics, GitHub Pages / Azure Hosting

---

## 🧱 Project Structure
/assets
/img → Profile image, favicon, etc.
/docs → Resume PDF
/css
styles.css → Custom theme styles including University of Iowa colors
/js
scripts.js → Smooth scrolling, nav behavior, etc.
cookie-popup.js
index.html → Main content: About, Experience, Education, Interests
cookie-policy.html
privacy-policy.html
terms.html
README.md

---

## 🎨 Design

The site uses a **black and gold color scheme** inspired by the University of Iowa, with light customization on top of Bootstrap 5. Sections include:

- **About Me**
- **Experience**
- **Education**
- **Interests**
- **Social Media Links**
- **Resume Download (PDF)**

---

## 🍪 Privacy, Cookies, and Terms

This site uses [Google Analytics](https://analytics.google.com/) to track page traffic.  
Supporting pages include:

- [`cookie-policy.html`](cookie-policy.html)
- [`privacy-policy.html`](privacy-policy.html)
- [`terms.html`](terms.html)

Each page includes basic navigation links and is styled consistently.

---

## 📈 Google Analytics

Google Analytics 4 is integrated via the global site tag:

```html
<script async src="https://www.googletagmanager.com/gtag/js?id=G-NB5LGKYFZE"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){ dataLayer.push(arguments); }
  gtag('js', new Date());
  gtag('config', 'G-NB5LGKYFZE');
</script>

To verify tracking:

Visit GA4 > Reports > Realtime to see live session data

Use Google Tag Assistant

## 🚀 Deployment
This site can be hosted via:

GitHub Pages: Push the repository and enable GitHub Pages in repo settings.

Azure Static Web Apps: Used for the live deployment with custom domain via Namecheap.

Custom Domain
The site is linked to a custom Namecheap domain using:

A Records (@) pointing to Azure Static Web Apps Front Door IPs

CNAME (www) pointing to the Azure auto-generated domain

## 📄 License
This project was created for academic purposes and personal presentation. Content is © 2025 Trey Wagner. Reuse is not permitted without permission.

## 🙏 Acknowledgments
Bootstrap

Font Awesome

Google Fonts

Google Analytics

Class instruction and guidance from the University of Iowa faculty

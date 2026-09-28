# PixelForge — Studio Website

A one-page website for **PixelForge**, a digital studio offering web development, mobile app development, ERP/CRM software, UI/UX design, and creative design services (posters, company profiles, portfolios, etc.).

This project is built on a one-page portfolio HTML template (originally "Denzel — Onepage Personal Template") that has been repurposed into a studio/agency site.

---

## 📌 Project Overview

- **Business:** PixelForge
- **Type:** One-page freelance/agency website
- **Base template:** Bootstrap-based one-page portfolio template (jQuery + pagepiling.js scroll effect)
- **Goal:** Present PixelForge's services, past work, testimonials, and a contact form to convert visitors into leads

---

## 📁 Project Structure

```
pixelforge-site/
│
├── index.html              # Main page (all sections)
├── css/
│   ├── style.css           # Main stylesheet
│   └── jquery.pagepiling.min.css
├── js/
│   ├── jquery-1.12.4.min.js
│   ├── popper.min.js
│   ├── bootstrap.min.js
│   ├── jquery.validate.min.js
│   ├── jquery.magnific-popup.min.js
│   ├── jquery.pagepiling.min.js
│   ├── owl.carousel.min.js
│   └── interface.js
├── img/
│   ├── bg/                 # Section background images
│   ├── news/                # Blog/news thumbnails
│   ├── partners/            # Client/tech logos
│   └── ...                  # Profile & project images
└── README.md
```

---

## 🧭 Page Sections

| Section ID | Purpose |
|---|---|
| `#home` | Hero / intro with studio name & tagline |
| `#about` | Who PixelForge is + core specializations |
| `#experience` | Repurposed as **Services** (Web Dev, App Dev, ERP/CRM, UI/UX, Design) |
| `#skills` | Repurposed as **Our Expertise** with skill/progress bars |
| `#projects` | Portfolio / past work grid |
| `#partners` | Client logos or tech stack used |
| `#testimonials` | Client feedback/reviews |
| `#news` | Blog / insights articles |
| `#contact` | Contact details + contact form |

> Note: Section `id`s were kept the same as the original template (`#experience`, `#skills`, etc.) so the navigation menu and scroll-anchors continue to work — only the **visible text/content** was changed, not the structure.

---

## ✍️ Content Status

All section copy (headlines, service descriptions, testimonials, sample projects, blog titles, contact info) has been drafted and is ready to paste into the HTML. See `content-brief.md` (or the content shared separately) for the full copy.

**Still needs real data before launch:**
- [ ] Real contact email, phone number, address
- [ ] Real social media links (Facebook, Twitter, LinkedIn)
- [ ] Real project names + project images/case studies
- [ ] Real client testimonials
- [ ] Real client/technology logos
- [ ] Real blog posts (or remove the News section if not needed)
- [ ] Replace placeholder profile/about images with real photos or brand imagery
- [ ] Update page `<title>` and meta description tags

---

## 🛠️ Tech Stack

- HTML5 / CSS3
- Bootstrap (grid + components)
- jQuery
- Owl Carousel (experience & testimonial sliders)
- Pagepiling.js (full-page vertical scroll effect)
- Ionicons (icons)
- Google Fonts: Karla, Lato

---

## 🚀 Getting Started

1. Clone or download the project folder.
2. Open `index.html` in a browser to preview locally (no build step required — it's static HTML/CSS/JS).
3. Edit content directly inside `index.html` per section (see table above).
4. Replace placeholder images in `/img/` with real assets, keeping the same filenames or updating the `src` paths accordingly.
5. Update the contact form's backend/action (currently a front-end only form — needs a mail handler like Formspree, EmailJS, or a custom backend endpoint to actually send messages).

---

## 📋 To-Do / Next Steps

- [ ] Swap in final brand content (see Content Status above)
- [ ] Connect contact form to an email service
- [ ] Add real favicon and social preview (Open Graph) images
- [ ] Optimize images for web (compress before upload)
- [ ] Test responsiveness on mobile/tablet
- [ ] Set up hosting/domain (e.g., Netlify, Vercel, custom hosting)
- [ ] Add analytics (Google Analytics / Plausible) if needed
- [ ] SEO pass: title tags, meta descriptions, alt text on images

---

## 📄 License

Based on a purchased/licensed HTML template — check the original template's license terms before redistributing or reselling this site as-is.

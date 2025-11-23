# Catalat · PHP online catalog system with admin panel

![Preview of the Catalat public catalog and admin panel](https://cata.lat/catalat-preview.png)

Self-hosted PHP catalog script with modern design, multi-language support and SEO in mind.
Publish product, rental or service catalogs in minutes using a clean public site and a simple admin panel.

* Homepage: [https://cata.lat/](https://cata.lat/)
* Live demo (public + admin): [https://cata.lat/demo/](https://cata.lat/demo/)
* Developer: [https://pascoal.eti.br](https://pascoal.eti.br)

---

## Overview

> Turn your catalog into a single link you can share everywhere.

Catalat is a lightweight PHP script that creates:

* a **beautiful public catalog**, focused on mobile and SEO, and
* a **simple admin panel**, focused on speed and clarity.

You host it on your own server and keep full control: items, categories, pages, languages, images and colors.

### Highlights

* Per installation: **multiple catalogs** (one codebase for several projects)
* Main focus: **mobile experience + SEO**
* Languages: **EN, PT-BR, ES, FR**
* PWA ready: icons and manifest prepared

---

## Use cases

Catalat works well for:

* Product or service catalogs
* Rentals (party kits, equipment, etc.)
* Menus (bars, restaurants, coffee shops)
* Portfolios and price tables
* Simple “link-in-bio” style catalogs

Anywhere you need a **structured list** of items with images, text and categories.

---

## Features

### Public catalog

Friendly interface for visitors:

* Clean layout with **category filters**
* Full-text **search**
* **Highlight items** (featured products)
* **Item detail page** with gallery, description and price
* **WhatsApp shortcut** to request items
* **Institutional pages** (About, FAQ, policies, etc.)
* Footer with quick links, **language selector** and contact info
* Designed to look great on **smartphones and desktops**

### Admin panel

Fast and simple admin interface:

* Manage **categories**
* Register items with:

  * Title and description
  * Category selection
  * Multiple photos
  * Prices and highlight status
  * Visibility (show / hide)
* Manage **institutional pages** (About, FAQ, policies)
* Configure:

  * Logo and brand colors
  * Public texts (titles, descriptions)
  * Basic SEO options

### Multi-language & SEO ready

* Interface prepared in **EN, PT, ES, FR**
* Texts separated by language
* Meta tags, canonical URL and Open Graph already set
* JSON-LD schema:

  * SoftwareApplication
  * WebSite
  * Person (author)
* Structure designed to help search engines understand your catalog

### Ready for agencies & white-label

* Use one script as a base for **multiple client projects**
* Customize per installation:

  * Logo
  * Colors
  * Texts
  * Subdomain or folder
* Ideal as a **white-label catalog** solution

---

## Screenshots

Use these filenames (or adapt to your repo):

### Public catalog

* `catalat-preview.png` – Preview of public catalog + admin panel
* `filter.png` – Home with category filter
* `search-public.png` – Search results page
* `item-public.png` – Item detail page with gallery and WhatsApp link
* `home-footer.png` – Footer with navigation, languages and contact

### Admin panel

* `home-admin.png` – Admin dashboard with shortcuts
* `admin-item-list.png` – Item list with status and actions
* `admin-item-edit.png` – Edit item form (title, category, photos, prices, highlight)
* `admin-site-configuration.png` – Site configuration (logo, colors, SEO)
* `admin-page-list.png` – List of pages (About, FAQ, policies)
* `translate-PT-FR-EN-ES.png` – Translations screen (PT, EN, ES, FR)
* `script.png` – Tech/code preview

---

## Tech stack

Clean PHP code that runs well on common shared hosting.

### Backend

* PHP 8.x (no heavy frameworks)
* MySQL / MariaDB
* Tables for items, categories, pages and settings

### Frontend

* Bootstrap 5 responsive grid
* Modern CSS, mobile-first
* PWA layout with icons and manifest prepared

### SEO / Meta

* Canonical URL and hreflang (en, pt-BR, es, fr, x-default)
* Open Graph and Twitter Cards
* JSON-LD:

  * SoftwareApplication
  * WebSite
  * Person
* Geo meta tags pointing to Brazil

---

## Requirements

* PHP 8.x
* MySQL or MariaDB
* Typical shared hosting (if you run WordPress, you’re probably ready)

---

## Installation (high-level)

1. **Upload files**
   Upload the script files to your hosting (root or a subfolder like `/catalog/`).

2. **Create database**
   Create a MySQL/MariaDB database and a user with full permissions.

3. **Configure connection**
   In the config/installer, set:

   * DB host, name, user, password
   * Base URL (public catalog + admin)

4. **Run installation**

   * If you include an installer, access something like `https://yourdomain.com/install/`.
   * Or import the SQL manually and create the first admin user following the documentation.

5. **Access admin**

   * Go to `/admin/` (or your configured path)
   * Log in with the admin user
   * Configure logo, colors, languages and initial content

---

## Usage

1. **Configure your catalog**

   * Set site name, logo and colors
   * Configure languages and default locale
   * Add institutional pages (About, FAQ, policies)

2. **Create categories**

   * Create categories to organize your items
   * Mark featured items if needed

3. **Add items**

   * Title, description, price/label
   * Category
   * Multiple photos
   * Visibility (show/hide)

4. **Share the link**

   * Instagram / Facebook bio
   * WhatsApp profile
   * QR codes on printed materials
   * Business cards and flyers

---

## FAQ

### Do I need a powerful server?

No. Catalat is optimized for shared hosting with PHP 8.x and MySQL or MariaDB.
If you already host small sites or WordPress, you are probably ready.

### Is this a full e-commerce system?

No. Catalat is a **catalog and presentation layer**.
It focuses on showing products and gathering interest.

You can link each item or call-to-action to:

* WhatsApp
* External checkout links
* Any payment or booking system you prefer

---

## Contact

Want to use Catalat in your next project?
Send a message on WhatsApp to talk about licensing, installation and customization.

* WhatsApp: `+55 21 98472-5056`
* Direct link: [https://wa.me/5521984725056
* Site: [https://pascoal.eti.br](https://pascoal.eti.br)

---

## Author

**Pascoal Eti** — custom web development & PHP catalog solutions

* Website: [https://pascoal.eti.br](https://pascoal.eti.br)
* Project home: [https://cata.lat/](https://cata.lat/)

© 2025 Catalat. All rights reserved.

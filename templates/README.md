# Bgback Web Builder — Templates Library

> **266 ready-made HTML/CSS block templates** for the [Bgback Live Code Studio](https://bgback.com) — organized by category, hosted via jsDelivr CDN.

---

## 📦 Categories (30 total)

| File | Category | Templates |
|---|---|---|
| `navbar.json` | Navigation Bar | 38 |
| `hero.json` | Hero Section | 55 |
| `banner.json` | Banner | 33 |
| `carousel.json` | Carousel / Slider | 5 |
| `features.json` | Features / Benefits | 5 |
| `services.json` | Services Block | 5 |
| `about.json` | About Block | 5 |
| `post-grid.json` | Post Grid / Blog List | 10 |
| `post-cards.json` | Post Cards | 5 |
| `post-details.json` | Post Details | 5 |
| `product-grid.json` | Product Grid | 5 |
| `product-cards.json` | Product Cards | 5 |
| `product-details.json` | Product Details | 5 |
| `shopping-cart.json` | Shopping Cart | 5 |
| `checkout.json` | Checkout Form | 5 |
| `portfolio-grid.json` | Portfolio Grid | 5 |
| `portfolio-cards.json` | Portfolio Cards | 5 |
| `gallery.json` | Gallery | 5 |
| `testimonials.json` | Testimonials / Reviews | 5 |
| `pricing.json` | Pricing Tables | 5 |
| `team.json` | Team Section | 5 |
| `clients.json` | Client / Partner Logos | 5 |
| `faq.json` | FAQ / Accordion | 5 |
| `cta.json` | Call to Action (CTA) | 5 |
| `contact.json` | Contact Form | 5 |
| `login.json` | Login / Signup Form | 5 |
| `newsletter.json` | Newsletter Subscription | 5 |
| `search.json` | Search Bar | 5 |
| `sidebar.json` | Sidebar | 5 |
| `footer.json` | Footer | 5 |

---

## 🚀 CDN Usage (jsDelivr)

Load any category instantly via jsDelivr CDN:

```
https://cdn.jsdelivr.net/gh/shahfarooq255/bgback-Web-Builder-Template@main/templates/{category}.json
```

**Example:**
```javascript
fetch('https://cdn.jsdelivr.net/gh/shahfarooq255/bgback-Web-Builder-Template@main/templates/navbar.json')
  .then(res => res.json())
  .then(data => console.log(data.templates));
```

---

## 📁 File Structure

```
bgback-Web-Builder-Template/
├── README.md
└── templates/
    ├── index.json          ← Manifest of all categories
    ├── navbar.json
    ├── hero.json
    ├── banner.json
    └── ... (30 files total)
```

---

## 📋 JSON Format

Each file follows this structure:

```json
{
  "_meta": {
    "category": "navbar",
    "label": "Navigation Bar",
    "count": 38,
    "version": "1.0",
    "updated": "2026-07-19"
  },
  "templates": [
    {
      "id": "navbar-1",
      "name": "Modern Glass Navbar",
      "description": "Glassmorphism effect with gradient",
      "html": "<style>...</style><nav>...</nav>"
    }
  ]
}
```

---

## 🔗 Links

- **Live Tool**: [Bgback Live Code Studio](https://bgback.com)
- **CDN Manifest**: [index.json](https://cdn.jsdelivr.net/gh/shahfarooq255/bgback-Web-Builder-Template@main/templates/index.json)

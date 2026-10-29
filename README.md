# Al Hara Cafeteria — Frontend

The client-facing website and administrative interface for **Al Hara Cafeteria**.

## Features

- **Customer Website (`/`)**:
  - Interactive menu categorized by cravings with search filters
  - Signature favorites spotlight
  - Online ordering cart with WhatsApp integration
  - Dynamic branding, hours, announcement strip, and contact details
  - Photo gallery showcasing cafeteria specials
- **Admin Panel (`/admin/`)**:
  - Manage menu items, categories, and pricing
  - Update website content, social links, opening hours, and theme accents
  - Manage gallery photos and order submissions

## Directory Structure

```text
├── index.html          # Main customer-facing website
├── css/
│   └── style.css       # Main website styling & design tokens
├── js/
│   └── main.js         # Client-side dynamic data loader & cart logic
├── images/             # Illustrations and SVG assets
└── admin/
    ├── index.html      # Admin dashboard interface
    ├── admin.css       # Admin dashboard styles
    └── admin.js        # Admin panel interactivity & API client
```

## Running Locally

You can serve this frontend using any static file server, for example:

```bash
# Using Python
python -m http.server 3000

# Using Node.js npx serve
npx serve .
```

The frontend connects to the backend API endpoints (`/api/public`, `/api/admin/*`, `/api/login`).
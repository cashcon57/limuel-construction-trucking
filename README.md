# Limuel Construction & Trucking

Official website for **Limuel Construction & Trucking** — a bonded & insured construction and trucking company founded by Farris Limuel in 2007, serving Texas.

**Live Site:** [https://cashcon57.github.io/limuel-construction-trucking/](https://cashcon57.github.io/limuel-construction-trucking/)

## About

From heavy hauling to ground-up builds, Limuel Construction & Trucking has been delivering dependable services for nearly two decades. This site serves as the company's digital presence — showcasing services, portfolio work, and providing direct contact options.

## Services

### Trucking
- 18-Wheelers
- Flatbed
- Box Trucks
- Cement Trucks

### Construction
- Renovations
- Concrete
- Patios
- Roofing
- Landscaping

## Architecture

```
├── index.html              # Main landing page (hero, services, about, contact)
├── portfolio.html           # Project gallery with filtering and lightbox
├── LimuelTrknStruct.png     # Company logo (optimized)
├── README.md
├── .gitignore
├── .github/
│   └── workflows/
│       └── pages.yml        # GitHub Actions deploy workflow
└── assets/
    └── icons/
        ├── 18-wheeler.svg   # Custom detailed truck illustrations
        ├── flatbed.svg      #   (hand-drawn SVGs with cab, wheels,
        ├── box-truck.svg    #    exhaust stacks, rivets, etc.)
        ├── cement-truck.svg #
        ├── renovations.svg  # Lucide open-source icons (MIT)
        ├── concrete.svg     #   (hammer, castle, brick-wall,
        ├── patios.svg       #    house, tree-deciduous)
        ├── roofing.svg      #
        └── landscaping.svg  #
```

### Tech Stack

- **Pure HTML/CSS/JS** — no frameworks, no build step, no dependencies
- **Google Fonts** — Anton (headings), Oswald (UI labels), Inter (body)
- **CSS Custom Properties** — centralized color palette and design tokens
- **SVG Icons** — custom detailed illustrations for trucking; Lucide icons (1px stroke) for construction
- **GitHub Pages** — deployed via GitHub Actions (`actions/deploy-pages@v4`)

### Design

- Dark theme with crimson (`#A52020`) and gold (`#E0B44E`) accent palette
- Responsive layout with mobile nav, scroll-triggered fade-in animations
- Tabbed service categories (Trucking / Construction)
- Contact form with mailto and SMS prefill functionality
- Portfolio page with category filtering and image lightbox

## Contact

- **Phone:** (361) 308-0430
- **Email:** mr.farrislimueljr@gmail.com

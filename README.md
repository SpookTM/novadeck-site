# NovaDeck — Premium Digital Templates

A fully static digital product storefront with Stripe payment integration.

## Site Structure

```
novadeck-site/
├── index.html          ← Main storefront (homepage)
├── SETUP_GUIDE.html    ← Stripe + Netlify setup guide
└── products/
    ├── resume-pack.html
    ├── invoice-template.html
    ├── business-proposal.html
    ├── social-media-kit.html
    ├── notion-finance-os.html
    └── pitch-deck.html
```

## Deployment

Hosted on **Netlify** with auto-deploy from this GitHub repo.
Every push to `main` automatically updates the live site.

## Payments

Powered by **Stripe Buy Buttons** — embedded directly in the product modals.

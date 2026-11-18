# GoldBill 360 — Premium Jewellery Billing

A responsive jewellery billing workspace for two showrooms, redesigned with a charcoal, champagne-gold and ivory visual identity.

## Showrooms
- Natuva Sreenivasulu Jewellers
- Aabharan Gold and Diamonds

## Features
- New bills for gold, silver, diamond and other jewellery
- Automatic 10% making charge calculated on metal value
- Editable 24K, 22K, 18K and silver reference rates
- GST, discounts, payment method, amount received and balance due
- Two-shop selection and editable shop contact/tax details
- English and Telugu interface labels
- Saved bill history and customer/invoice search
- Print / Save as PDF
- Browser-local persistence for bills, rates and shop settings
- Responsive dashboard summaries

## Run locally
```bash
npm install
npm run dev
```

## Build
```bash
npm run build
npm run preview
```

## GitHub Pages
The repository contains a GitHub Actions workflow that builds Vite and deploys the `dist` folder. In GitHub, open **Settings → Pages** and set the source to **GitHub Actions**. Pushes to `main` then trigger deployment.

## Important data note
This version stores records in the current browser on the current device; it does not synchronize across devices or users. Export or back up important records before clearing browser data. Confirm GST invoice fields, hallmark/HUID details and applicable tax requirements with your accountant before business use.

# Quotero — Official Product Website & Landing Page

The official marketing landing page and web presence for **Quotero** (`quotero.app`), an agile estimate, quote, and commercial invoicing platform engineered for contractors, field service technicians, and independent professionals.

## Tech Stack & Architecture

- **Stack:** Pure Semantic HTML5 + Tailwind CSS + Lucide Icons + Google Fonts (Plus Jakarta Sans & JetBrains Mono)
- **Deployment:** Cloudflare Pages (Global Anycast Edge Network)
- **Domain:** [https://quotero.app](https://quotero.app)
- **Web Workstation:** [https://app.quotero.app](https://app.quotero.app)

## Deployment to Cloudflare Pages

1. In Cloudflare Dashboard, navigate to **Compute (Workers & Pages)** > **Create application** > **Pages** > **Connect to Git**.
2. Select repository `vertixlabs/quotero-landing`.
3. Build Settings:
   - Framework preset: `None`
   - Build output directory: `/`
4. Assign custom domains:
   - `quotero.app`
   - `www.quotero.app`

## License

© 2026 Vertix Labs LLC. All rights reserved.

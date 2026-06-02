# Minh Giao Website — https://minhgiao.khoa-nguynxun.workers.dev (minhgiao.com.vn - official link, will be ported over soon)

Redesign of the corporate website for **Minh Giao Technical and Trading Co., Ltd.** — a B2B distributor and integrator of M&E systems (busway, LV/MV switchgear, BMS, integrated security) for construction projects in Vietnam.

## Stack

- **Framework** — Next.js 15 (App Router, TypeScript strict)
- **Styling** — Tailwind CSS v4 + CSS variables
- **CMS** — Sanity.io
- **Deployment** — Cloudflare Workers via OpenNext
- **Email** — Resend
- **Analytics** — Google Analytics 4 (consent-gated)

## Pages

```
MinhGiao/
├── giai-phap/
│   ├── an-ninh/
│   ├── bms/
│   ├── busway/
│   ├── tu-dien-ha-the/
│   └── tu-trung-the/
├── san-pham/
│   └── [category]/
│       └── [slug]/
├── du-an/
│   └── [slug]/
├── tin-tuc/
│   └── [slug]/
├── tai-lieu/
├── gioi-thieu/
│   └── customers-partners/
├── tuyen-dung/
│   └── [slug]/
├── lien-he/
└── chinh-sach-bao-mat/
```

## Features

- Editor-driven hero carousel with per-slide CTA links (Sanity)
- 5 dedicated solution pages (Busway, LV Switchgear, MV Switchgear, Integrated Security, BMS)
- Full product catalog with category filtering and lightbox
- 39 real project case studies with gallery, YouTube embeds, and sector filtering
- News feed with external article support
- Recruitment listings with Portable Text job detail pages
- PDF catalogue downloads
- Contact form with rate limiting, honeypot, and server-side validation
- Cookie consent banner with consent-gated GA4
- Schema markup: Organization, LocalBusiness (3 locations), BreadcrumbList, Article
- Sitemap + robots.txt auto-generated at build time

---

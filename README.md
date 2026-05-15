# Apartments Lazarić — apartmentslopar.com

Statička web stranica za Apartmane Lazarić u Loparu, otok Rab.

## Struktura

```
.
├── index.html          # Hrvatska verzija (root)
├── en/index.html       # English verzija
├── de/index.html       # Deutsch verzija
├── images/             # Sve slike (optimizirane, ~6MB ukupno)
├── robots.txt          # Za search engine crawlers
├── sitemap.xml         # Za Google indexing
└── vercel.json         # Vercel konfiguracija (caching, security headers)
```

## Tehnologija

- Statički HTML/CSS/JS — bez frameworks-a, bez build koraka
- Multi-jezik: hrvatski (root), engleski, njemački
- SEO: title, meta description, Open Graph, Schema.org LodgingBusiness JSON-LD, hreflang tagovi
- Responsive (mobile, tablet, desktop)
- Lazy loading slika
- Mediteranska, profesionalna estetika

## Kontakt podaci

- Email: info@apartmentslopar.com
- Telefon: +385 98 194 86 09
- WhatsApp: https://wa.me/385981948609

## Lokalna preview

Otvori `index.html` u browseru. Slike su relativne, sve radi offline.

## Deploy na Vercel

1. Repo se automatski deploya na Vercel kad se napravi push
2. `vercel.json` postavlja cache headers za slike (1 godina) i security headers
3. Domena `apartmentslopar.com` se postavlja u Vercel dashboardu pod Domains

## Buduće izmjene

Sav sadržaj je u `content.json`. Generator `generate2.py` (van repa) gradi HTML-ove iz toga.

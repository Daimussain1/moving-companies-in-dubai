# Moving Company Dubai — Page Package

Ye package 4 files par mushtamil he jo aap apni site "movingcompanydubai" par upload kr sakte hain.

## Files

| File | Purpose |
|---|---|
| `index.html` | Main landing page — luxury/gold-and-navy theme, animated hero, 1400+ words semantic article targeting **"moving companies in dubai"**. |
| `robots.txt` | Search engines ko crawl allow krta he aur sitemap ka path deta he. |
| `sitemap.xml` | Ek hi URL (homepage) list karta he for search engine indexing. |
| `README.md` | Ye file — instructions. |

## Important before you upload

1. **Domain replace karein**: `robots.txt`, `sitemap.xml` aur `index.html` (canonical + og:url tags) me `https://www.movingcompanydubai.com/` likha hua he — isko apni asli domain se replace kr dein.
2. **Anchor link**: Second paragraph me anchor text **"Go here"** link kiya gaya he `https://easymovers.ae/` ke sath. Ye link sirf isi ek jagah he — page me kahi aur nahi.
3. **Phone number / call button**: Jaisa request kiya gaya tha, koi phone number ya call-to-action button add nahi kiya gaya.
4. **Word count**: `index.html` ka visible article content ab ~1,850 words he — H1/H2/H3, ek naya "White-Glove Care" luxury section, expanded Cost/Areas sections, 7-question FAQ, checklist aur process steps ke sath semantically structured.
5. **Images**: `index.html` me ab 4 real photos hain (hero Dubai skyline, packing-boxes room, luxury chandelier interior, Burj Khalifa skyline) — sab `images.unsplash.com` se, free-to-use under the Unsplash License (no attribution legally required, commercial use allowed). Direct hotlink kiya gaya he; production site ke liye behtar he ke aap inhe download kr ke apne server/CDN par host kr dein taake load speed aur uptime aap ke control me rahe. Service cards abhi bhi lightweight SVG icons use karte hain jo har jagah instantly load hote hain.
6. **Design**: Dark navy background (`#0A0E1A`) + gold accents (`#CBA135`/`#E9C766`) + emerald highlight — Cormorant Garamond (headings) + Manrope (body) fonts se premium/luxury look. Hero heading par shimmering gold animation, scroll-reveal animation, aur hover effects included hain — sab `prefers-reduced-motion` ko respect karte hain.
7. **Structured data**: `index.html` me `MovingCompany` schema (JSON-LD) included he for better search-engine understanding — koi phone number is me bhi shamil nahi kiya gaya.

## Deployment

Bas 4 files ko apne hosting root (ya subfolder) me upload kr dein — koi build step ki zaroorat nahi, ye plain static HTML he.

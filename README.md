# Tropical Barber Co. — Website

## 📁 File Structure
```
tropical-barber-co/
├── index.html          ← The entire website (all-in-one)
├── images/
│   ├── logo.jpg        ← Logo (already included)
│   ├── hero-bg.jpg     ← ⬅ YOU PROVIDE: botanical/shop background for hero
│   ├── shop-interior.jpg ← ⬅ YOU PROVIDE: shop interior (Services section)
│   └── barber-portrait.jpg ← ⬅ YOU PROVIDE: barber portrait (Story section)
└── README.md
```

## 🖼 Photos needed
Three image slots are ready and waiting:

1. **Hero background** (`images/hero-bg.jpg`)
   - A wide atmospheric shot: botanical wall, shop interior, or moody exterior
   - Wider than tall (landscape). Will be darkened/overlaid.

2. **Shop interior** (`images/shop-interior.jpg`)
   - Inside the shop: barber chair, plants, warm light
   - Portrait orientation preferred

3. **Barber portrait** (`images/barber-portrait.jpg`)
   - The barber at work or posed
   - Portrait orientation, black & white or colour

To add each photo: drop the file into the `images/` folder with the exact filename above.
Then in `index.html`, find the matching `<!-- PHOTO SLOT -->` comment and uncomment the `<img>` tag.

## 🔧 Things to update in index.html
Search for these and swap in real info:
- Hours (Tue–Fri 9–7, Sat 9–4) — update if different
- Address (139 Millennium Blvd) — confirm or update
- Phone/email — find the empty `.visit-contact` div and add details

## 🚀 Deploy via GitHub + Cloudflare Pages
Same process as your personal site:
1. Push this folder to a GitHub repo (e.g. `tropical-barber-co`)
2. In Cloudflare Pages → Connect to Git → select the repo
3. Build settings: none needed (static HTML)
4. Done — auto-deploys on every push

## ✅ What's live and working
- All booking buttons → tropicalbarberco.resurva.com
- Instagram link → @tropicalbarberco
- Mobile hamburger menu
- Scroll-triggered fade-in animations
- Sticky nav (transparent → forest green on scroll)
- Fully responsive (mobile + desktop)
- Google Maps embed (139 Millennium Blvd)

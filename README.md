FortunaPlay Lottery — React + Vite + Tailwind
===============================================

Run locally
-----------
npm install
npm run dev    # open the printed URL
npm run build
npm run preview

Payments
--------
- Included a **Test Checkout (Simulated)** button that records purchases without real payments.
- To enable **Stripe Checkout**, add a small server endpoint (e.g., Netlify function) to create a Checkout Session, then update the button handler to POST there and redirect to `session.url`.

Branding
--------
- FortunaPlay theme (brand blue #1e3a8a, accent #f59e0b) + SVG logo included.

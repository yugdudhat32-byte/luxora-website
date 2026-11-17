# LUXORA website

Single-file site: `index.html` (HTML, CSS and JavaScript together, no build step, no dependencies).

## Run
Open `index.html` in a browser, or upload it to any static host (Netlify, Vercel, GitHub Pages, shared hosting).

## Configure before launch
In the `<script>` block, edit:
    const CONFIG={email:"jayshreecreation32@gmail.com",whatsapp:"+91 9601359591"};
- email: your contact address (the form opens the visitor's email app with the enquiry filled in)
- whatsapp: digits with country code, e.g. 14165550123

The form does not store or send anything by itself. For real submissions, connect a form service or backend.

## Notes
- Pages use hash routing (#about, #pricing, ...).
- Fonts load from Google Fonts (Cormorant Garamond, Instrument Sans) with serif/sans fallbacks.
- Calculator prices (BASE, FEAT, INTG constants) are placeholders: set your real pricing.
- When deploying on your own domain, add sitemap.xml, robots.txt and canonical URLs.
- Portfolio projects are fictional concepts and are labelled as such.

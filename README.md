# Rixance Menswear storefront

Static demo storefront for Rixance, laid out like a premium tailoring site: home page with full-screen photography, collection pages with filters, and product pages with a scrolling photo column and sticky buy panel.

Open `index.html` in a browser, or serve the folder locally:

```bash
npx http-server@14.1.1 . -p 3610
```

Pages are hash routes: `#home`, `#c-<collection>` (e.g. `#c-suits`), `#p-<product>` (e.g. `#p-camel-overcoat`).
Checkout, Customize and accounts are not connected; contact details are placeholders.

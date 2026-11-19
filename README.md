# Easy & Perfect Engineering Construction — website

Animated one-page website for **Easy & Perfect Engineering Construction Limited** (RC 1266652), an infrastructure development company in Lagos, Nigeria.

Everything lives in a single file, `index.html`, with the logo embedded. There is no build step.

## Edit contact details

Open `index.html`, search for `const CONFIG`, and fill in:

```js
const CONFIG = {
  phone: "+234 ...",
  email: "info@...",
  whatsapp: "234..."   // digits only
};
```

The phone and email appear in the contact section automatically, and the enquiry form opens WhatsApp (or email) with the message filled in.

## Run locally

```bash
python -m http.server 8000
```

Then open http://localhost:8000.

## Deploy

The site is a static page. On Vercel, import this repository with the framework preset set to **Other**; every push to `main` redeploys.

## Libraries

Loaded from cdnjs: GSAP 3.12.5 with ScrollTrigger, and three.js r128. Fonts from Google Fonts (Archivo, IBM Plex Sans, JetBrains Mono).

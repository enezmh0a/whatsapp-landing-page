# WhatsApp Landing Page (Snapchat Ads Friendly)

A minimal, bilingual (Arabic/English) landing page that opens WhatsApp with a prefilled message.
Designed to comply with Snapchat policies by linking to a website (this page) rather than directly to a social platform.

## Live Goal
Use this page URL in your Snapchat ad (Objective: **Website Visits**). Users tap the button and are taken to WhatsApp to start a chat.

---

## Phone Number & Message
- **Current number:** `+966 53 733 0138` (E.164: `966537330138`)
- To change the number or message later, edit `index.html`:
  ```js
  var phone = "966537330138";
  var msg = encodeURIComponent("مرحبا 👋 أتيت من سناب شات. أود الاستفسار/الحجز.\nHello, I came from Snapchat and want to chat/booking.");
  ```

---

## Quick Start (Local Preview)
1. Download `index.html`.
2. Open it in your browser (double‑click).

> Note: The WhatsApp link will only open properly on devices with WhatsApp installed (mobile).

---

## Deploy Options

### Option A — GitHub Pages (free)
1. Create a repo named (for example) `whatsapp-landing-page`.
2. Add `index.html` to the repo root.
3. In GitHub: **Settings → Pages → Build and deployment**  
   - **Source:** `Deploy from a branch`  
   - **Branch:** `main` (or your default), folder `/ (root)`  
4. Your site will be published at:  
   `https://<your-username>.github.io/whatsapp-landing-page/`

> In Snapchat Ads Manager, paste that URL as the website link.

### Option B — Netlify (drag & drop)
1. Go to **app.netlify.com** → “Add new site” → “Deploy manually”.
2. Drag the folder containing `index.html`.
3. Copy the generated site URL (you can set a custom name under **Site settings → Domain management**).

### Option C — Vercel
1. Create a new project → **Import** your GitHub repo.
2. Framework preset: **Other** (since it's plain HTML).
3. Deploy → copy the live URL.

### Option D — Any cPanel / hosting
Upload `index.html` to your `public_html` (or web root) via File Manager or FTP.

---

## Snapchat Configuration Tips
- **Campaign Objective:** Website Visits
- **Attachment/URL:** your published page URL (GitHub Pages/Netlify/etc.)
- **Creative:** Image/Video + clear CTA “تواصل واتساب”
- Add a short privacy note on the page (already included).

---

## Privacy Note
This page only redirects to WhatsApp and does not collect or store personal data.

---

## Files
- `index.html` (the landing page)
- `README.md` (this file)

---

## License
This project is provided as‑is, for your own use. No warranty.

# Yoberry · يوبيري — link page

Static one-page site (Arabic first, English switch) for NFC cards, QR codes and the Instagram bio.

- Links live in the `CONFIG` block near the end of `index.html`. A link left empty is hidden.
- `yoberry.vcf` is the "Save contact" card; update its phone number if the WhatsApp number changes.
- `?lang=en` opens the English version. Add `?src=nfc` / `?src=qr` to tell channels apart in analytics.
- Hosted on Vercel: every push to `main` goes live automatically.

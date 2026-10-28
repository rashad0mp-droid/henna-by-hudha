# Henna by Hudha — website preview

A single-page preview site for Henna by Hudha, a mehendi artist in Kozhikode & Malappuram,
Kerala. Not yet the official website.

- Try-on: visitors take or upload a photo of their palm (or use the live camera) and see
  one of her designs placed on it. Hand tracking runs on the visitor's device with Google
  MediaPipe Hands (loaded from jsDelivr / Google storage); no photo is uploaded.
- Designs in `designs/` are line-only cut-outs of her own work, extracted from her photos.
- Photos: her own Instagram posts, kept with her watermark (WebP).
- Edit the brand spelling and WhatsApp number in the `SITE` config at the top of the
  script in index.html. The enquiry form opens WhatsApp with the details filled in.
- Everything unconfirmed shows a yellow [CONFIRM] tag on the page.

# SkinCheck AI — educational skin health website starter

Responsive frontend prototype for image upload/preview, screening workflow UI, ABCDE skin warning-sign guide, and medical disclaimer.

**Not a diagnostic tool.** The image-analysis model is not connected. The analyze button intentionally reports this and does not generate a risk score or diagnosis.

## Deploy to Vercel
1. Upload these files to a GitHub repository (keep `index.html`, `styles.css`, `app.js`, and `api/` at repository root).
2. Import the repository into Vercel.
3. Framework preset: Other.
4. Build command: leave blank.
5. Output directory: `.` (root).
6. Deploy.

## To connect a real model
Use a clinically validated model and a secure server-side API. Review model performance across skin tones, image types, age groups, and lesion categories; implement consent, encryption, retention/deletion policies, monitoring, and clinician referral guidance. Do not market as diagnosis or rely on this prototype for medical decisions. `api/analyze.js` is an intentional placeholder returning HTTP 501 until a model is configured.

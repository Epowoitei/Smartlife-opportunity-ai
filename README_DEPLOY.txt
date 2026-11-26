SMARTLIFE OPPORTUNITY AI — PROFESSIONAL FRONTEND UPDATE

1. Upload the CONTENTS of this folder to the ROOT of your existing Cloudflare Pages project.
2. Keep index.html at the root.
3. Keep manifest.webmanifest and the complete assets folder.
4. Do not delete or replace the existing Job Search Worker, Paystack Worker, or D1 database.

Changes in this update:
- Uses the new Smart Life Opportunity AI logo supplied by the owner.
- Uses the Smart Life Library photograph in the Library section.
- Removes the outdated country-count banner and improves the Job Centre status.
- Improves phone navigation, spacing, forms, buttons and result cards.
- Keeps the 10 browser-based planning tools, six income pathways, membership prices and existing API endpoints.
- Updates the Selar store link to the previously supplied store address.

Important:
- Job Centre search depends on the separate job-search provider and its API credentials.
- Membership checkout depends on the existing Paystack Worker and configured plan codes.
- This frontend does not itself provide user accounts, automatic premium access control, or a live AI model. Those require additional backend integration and testing.
- Test the website, job search and payment flow after deployment. Do not accept real payments until the live checkout and membership activation have been verified.

Brand asset update: The exact logo image supplied by the owner is now used in BOTH the header logo and the app cover/hero image. Keep assets/smartlife-logo.jpg and assets/smartlife-cover.jpg in the assets folder.

LIVE AI BACKEND:
A separate smartlife-ai-tools-worker folder is included. Deploy it as a NEW Worker, enable a Workers AI binding named AI, and verify its /health endpoint before testing the ten AI tools. Do not replace the existing Job Search or Paystack Workers.
Official Selar destination used in this build: https://selar.com/m/Smartlifeglobalinitiative

LATEST BRAND UPDATE (2026-11-24): The newest logo image supplied by the owner is used for BOTH the header logo and the homepage cover image. Keep assets/smartlife-logo.jpg and assets/smartlife-cover.jpg in place.

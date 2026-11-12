# DJM Installs – landing page

A static, responsive single-page DJM Installs website with About Us and contact form. No build dependencies.

## Deploy through GitHub + Netlify
1. Create a new GitHub repository (suggested: `djm-installs-website`) and upload all files in this folder to the repository root.
2. In Netlify, choose **Add new project → Import an existing project → GitHub**, and select the new repository.
3. Build command: leave blank. Publish directory: `.`.
4. Under Netlify **Forms**, enable form detection if needed, then redeploy and verify `djm-contact` is detected.
5. Under **Forms → Submission notifications**, add an email notification to `info@djminstalls.co.uk`. Netlify may require the recipient to be an active team member; use an authorised email or invite the mailbox as a team member before configuring the notification.
6. When ready, add the custom domain `djminstalls.co.uk` in Netlify. Point **only** DJM domain's web DNS records as Netlify directs. Preserve the DJM MX, SPF, DKIM, DMARC and other email records. Do not modify DNS of any other domain.
7. Test a genuine form submission and confirm it appears in Netlify Forms **and** arrives in the designated mailbox.

## Before production
- Confirm DJM Installs' actual business description and replace the deliberately neutral About Us copy if desired.
- Confirm the privacy-policy controller/legal entity and retention details, and remove the provisional note.
- Replace the text-based mark with the official DJM Installs logo if supplied.
- The form posts to Netlify Forms; it does **not** send mail directly from the website. Notifications must be configured in Netlify.

## Branding
Official supplied DJM Installs logo artwork is included as logo-light.png, logo-colour.png and logo-original.svg. The live page uses the supplied white logo against the branded navy background.

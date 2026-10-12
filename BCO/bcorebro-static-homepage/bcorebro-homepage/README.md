# BCÖ static homepage

A simple, responsive Swedish-language homepage for BCÖ (Bangladeshi Community in Örebro).

## Files
- `index.html` — complete static website, including styles.

## Before publishing
1. Confirm that `bcorebro.se` is registered and under BCÖ's control.
2. Create the real email inbox `info@bcorebro.se`, or change the email address in `index.html`.
3. Review the organisation description and replace placeholder event text with real information.
4. Confirm that the association is comfortable publishing the wording on this page.

## Preview locally
Open `index.html` in a modern web browser.

## Deploy to Cloudflare Pages
1. Put `index.html` in a GitHub repository.
2. In Cloudflare, open Workers & Pages and create a Pages project connected to that repository.
3. For a plain static HTML site, leave the build command empty and set the output directory to `/` (or the repository root, as prompted).
4. Deploy, then add `bcorebro.se` under the project's Custom domains.
5. Follow Cloudflare's DNS instructions. If email is hosted elsewhere, preserve the email provider's MX and TXT records.

This is a static homepage only; it does not yet include a working news/event admin panel or contact form.

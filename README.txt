BLESSED WOODS WEBSITE — PACKAGE CONTENTS
=========================================

index.html
  This is your entire website — one self-contained file (HTML, CSS,
  and JavaScript all in one). Open it by double-clicking it in any
  web browser (Chrome, Safari, Edge, Firefox) to preview it locally.

HOW TO PUT IT ONLINE
---------------------
Any basic web hosting will work since it's a single file. Easy free
options:
  - Netlify (netlify.com) — drag and drop the "index.html" file (or
    this whole folder) onto their "Deploy" page.
  - GitHub Pages — upload index.html to a GitHub repository and
    enable Pages in the repo settings.
  - Any shared hosting / cPanel — upload index.html into the
    public_html folder.

BEFORE YOU LAUNCH — THINGS TO UPDATE
--------------------------------------
1. WhatsApp number: search the file for "wa.me/60000000000" and
   replace it with your real WhatsApp number (with country code,
   no + or spaces, e.g. 60123456789).

2. Translations: the Malay, Chinese, and Tamil text is a first draft.
   It's worth having a native speaker review it before launch.

3. Contact form: right now the form just shows a "thank you" message
   — it does not actually send you an email yet, since that needs a
   backend service (e.g. Formspree, EmailJS, or your own server).
   Let me know if you'd like this connected to a real inbox.

4. Product photos: the site currently uses simple carved line-icons
   for each product instead of real photos. Once you have product
   photography, they can be swapped in.

HOW TO ADD NEW CONTENT (AND KEEP TRANSLATIONS WORKING)
---------------------------------------------------------
Every piece of text on the site has a "data-i18n" tag connecting it
to a translations list near the bottom of the file (search for
"const translations ="). To add new text:
  1. Add a data-i18n="yourNewKey" attribute to the new HTML element.
  2. Add "yourNewKey" with its translated text inside each of the
     four language sections (en, ms, zh, ta) in the translations list.
No other code needs to change — the switcher will pick it up
automatically.

Questions or want changes made? Just ask.

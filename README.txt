RAO UDMI RAM PALACE — FULL WEBSITE UPDATE

CRITICAL FIX
The earlier entrance.jpg file was actually encoded as WebP despite having a .jpg extension. Some browsers/CDNs can refuse to display it when served as JPEG. This package re-encodes all image assets as real JPEG files and uses cache-busting query strings.

UPLOAD THESE FILES TO THE ROOT OF YOUR GITHUB REPOSITORY (same level as index.html):
- index.html
- rurp-logo.jpg
- entrance.jpg
- stage.jpg
- night-entrance.jpg
- rurp-logo.svg (optional legacy asset)

Do not upload the ZIP itself, and do not put these files inside an extra nested folder. In GitHub click Add file > Upload files, select the files above, then Commit changes to main. If GitHub asks to replace existing files, replace them.

Then wait for GitHub Pages to redeploy and open the site with Ctrl+F5.

INCLUDED FEATURES
Responsive website, supplied Lord Ram logo, venue hero photo and gallery, add/remove local gallery controls, booking enquiry to WhatsApp, Instagram and YouTube buttons with inline icons, venue/map links.

LIMITATION
Gallery additions/removals are saved only in the visitor's own browser. To change the public photos for all visitors, upload the image files and commit them to GitHub.

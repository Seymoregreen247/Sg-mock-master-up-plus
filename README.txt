SG MOCKUP MASTER V31

New in V31: Text, labels & signature (sidebar section 3)
- Presets: SALE, ACT NOW, NEW DROP, LIMITED, Garment name, Signature. Or type your own (up to 80 characters, Enter for a second line).
- Styles: Badge, Sale sticker, Bold outlined text, Signature script.
- Text color, badge/outline color, size and tilt.
- "Add to all garments" puts the label on every card; "Add to one garment" uses the card you last tapped.
- Drag labels on any card. Tap a label to edit it; edits apply to that label on every garment. Arrow keys nudge, Delete removes it from that card.
- Type {garment} anywhere to print each card's garment name (T-shirt, Crewneck, Hoodie...).
- Labels show up in downloads, shares and collages, and save with projects and templates.
- Fonts are built in, so labels look the same offline.

Still in from V30
- See-through backgrounds on every garment, including the long sleeve arm gaps.
- Six colors per garment: Black, White, Gray, Green, Red, Blue (hoodie also has the Gray back view).
- All photos built into index.html, so shirts load from the Netlify link or the file itself.

Deploy (GitHub -> Netlify)
Upload these 7 files to the repo root (no folders): index.html, manifest.webmanifest, sw.js, README.txt, icon-180.png, icon-192.png, icon-512.png.
Netlify: build command empty, publish directory "."
After deploying, open the site and refresh once so the new version replaces the cached one.

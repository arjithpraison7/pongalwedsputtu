# #PongalWedsPuttu

Wedding website for Arjith Praison & Anjali Vijay S — Thiruvananthapuram, 27 January 2027.

Live: https://arjithpraison7.github.io/pongalwedsputtu/

- `index.html` — the whole site (no build step)
- `images/` — Ghibli-style portrait, the Wedding and Reception cards, Mehndi artwork, mini cartoon us, link-preview image (Kerala & Tamil Nadu outlines are inline SVG from geohacker/india state boundaries)
- `calendar/` — .ics files for Apple / Outlook calendars

Languages: English, Tamil and Malayalam (switch at the top). A link can open in one language with `?lang=ta` or `?lang=ml`.
Each event card has a QR code for its map location.

Personal invite links: add `?to=<name>` (URL-encoded), optionally with `&lang=ta|ml`, e.g.
`https://arjithpraison7.github.io/pongalwedsputtu/?lang=ml&to=Kochacchan%20%26%20Family`
shows "പ്രിയപ്പെട്ട Kochacchan & Family," above the names. The name is shown as plain text and cut at 80 characters.

Spreadsheet (Google Sheets, Excel, LibreOffice), name in A2 and language (en/ta/ml) in B2:
`="https://arjithpraison7.github.io/pongalwedsputtu/?lang="&B2&"&to="&ENCODEURL(A2)`

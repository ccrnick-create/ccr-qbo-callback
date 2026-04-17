# CCR · QuickBooks OAuth Callback

Static HTML page used as the OAuth 2.0 redirect URI for CCR's private
QuickBooks Online integrations (Asset Tracker, CFO dashboard).

**No secrets. No server. No tracking.** The page is pure client-side
JavaScript that reads `code`, `realmId`, and `state` from the URL
query string and displays them for the operator to copy into their
terminal.

Deployed via GitHub Pages at:
https://ccrnick-create.github.io/ccr-qbo-callback/

Registered as a redirect URI on the shared "CCR Asset Tracker Sync"
Intuit production app.

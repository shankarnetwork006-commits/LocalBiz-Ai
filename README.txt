WedSnap AI — installable PWA starter

Included:
- Responsive mobile-first wedding event dashboard
- Create/search events (event metadata saved in browser localStorage)
- Select and preview photos during the current session
- Download selected photos and use device share sheet
- Basic PWA manifest and service worker shell cache

Important limitations:
- No authentication, cloud object storage, server API, persistent photo upload, or real cross-device gallery sharing is connected.
- Browser-selected photo previews use temporary object URLs and may disappear when the page/session ends.
- Do not use this prototype as the only copy of irreplaceable wedding media.

Run locally:
Serve this folder over localhost or HTTPS (PWA install/service worker requires secure context), e.g. deploy static files to Vercel or another HTTPS host.

To make production-ready, connect a backend, authentication, private object storage, signed upload/download URLs, access control, retention policies, and independent backup. Never place server credentials in browser code.

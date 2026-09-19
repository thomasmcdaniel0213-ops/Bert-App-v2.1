BERT v2.3.3 — iOS SAFE AREA UPDATE

Fix:
- Prevents the Bert header from rendering underneath the iPhone status area / Dynamic Island.
- Changes the standalone iOS status bar from translucent overlay mode to normal/default.
- Adds safe-area padding to Home, Tournament Builder, and Round Robin.

Why:
The previous black-translucent status bar allowed app content to extend underneath the iOS system controls.

# Update 16.4 — Evidence quality

# RoadDex Update 16.4 — Evidence quality

Includes all Update 16.3 changes. Upload every file in this folder to the root of `7178543-collab/roaddex` on main, replacing existing files. Do not upload the enclosing folder.

- Standard photos: 1600 px long edge, JPEG quality 0.82.
- Batch photos: 1280 px long edge, JPEG quality 0.76.
- Non-blocking success and error messages for saves, proposals, votes and uploads.
- Failed sighting saves retain the same ID and uploaded-photo progress for retry in the current page session. Use RETRY or the original Save button. Keep the page open; this is not a durable offline queue.
- Batch retry retains original IDs. Already uploaded photos are skipped.
- Invalid/unsupported images report an error rather than silently hanging or uploading unprocessed originals.
- Own Profile → App diagnostics shows version, browser/OS, install mode, network state and service-worker status.
- iPhone install guidance retains Safari → Share → Add to Home Screen and explains Open as Web App.
- PWA shell cache bumped to v16-4.

Existing low-resolution uploads cannot be restored by this update; add a new copy from the original if needed.

Validation: JavaScript and service-worker syntax; mocked photo resize/quality, invalid image rejection, and uploaded-photo retry deduplication. Backend conflict keys and owner policies checked read-only. No database changes. Actual iPhone/Android capture, installed PWA, double-tap and viewer pinch/pan remain device checks. This package is prepared, not deployed.


## Update 16.3

- Added iPhone/Safari PWA install instructions.
- Disabled accidental double-tap page zoom via touch-action: manipulation.
- Preserved normal page scrolling and custom image-viewer pinch/pan.
- Bumped PWA shell cache to v16-3.

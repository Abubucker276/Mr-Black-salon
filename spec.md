# Specification

## Summary
**Goal:** Ensure every service item on the Services page has a premium, consistent-style image displayed.

**Planned changes:**
- Add image references for every service item in `frontend/src/data/services.ts`, ensuring each service includes an `image` field pointing to `/assets/generated/*.dim_800x600.jpg`.
- Add the missing service images as static assets under `frontend/public/assets/generated` using the required filenames.
- Verify `frontend/src/pages/ServicesPage.tsx` renders an image for every `ServiceCard` so there are no services shown without an image.

**User-visible outcome:** All service cards on the Services page display an associated image (no missing/blank service images).

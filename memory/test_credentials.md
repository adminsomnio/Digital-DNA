# Test Credentials - Somnio.Co Atelier

## Local Atelier seed accounts (login via `/api/auth/login`)
| Role | Email | Password |
|------|-------|----------|
| Admin | admin@somnio.co | Admin@2026 |
| Manufacturer | mfg@somnio.co | Mfg@2026 |
| Associate | associate@somnio.co | Assoc@2026 |
| Client | client@somnio.co | Client@2026 |

## Extra manufacturer accounts (all password `Mfg@2026`)
- shanghai@somnio.co / shenzhen@somnio.co / guangzhou@somnio.co
- Each has a linked `manufacturer_id` in the directory after bootstrap.

## Manufacturer directory
- 14 workshops in `manufacturers` collection (codes 01-14).
- Codes 01-05 mirrored from gem-gallery-193 (Floral 01 is BURNED — test data).
- Codes 06-13 pushed to gem-gallery from Somnio seeds.
- Code 14 (Session Test Atelier) is BURNED (test data).

## gem-gallery-193 admin (from env)
- URL: env `GEM_GALLERY_BASE_URL` (https://gem-gallery-193.preview.emergentagent.com)
- Creds: env `GEM_GALLERY_ADMIN_EMAIL` / `GEM_GALLERY_ADMIN_PASSWORD`
- Preview server may be sleepy; call `/api/admin/auth` once to warm up before real tests.

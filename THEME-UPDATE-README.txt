KBK ACADEMY — VISUAL REDESIGN PACKAGE

Design direction: Modern Gurukulam + Examination Command Centre
Palette: forest green, warm ivory, academic gold; Playfair Display headings + DM Sans body text.

FILES TO REPLACE IN THE ROOT OF YOUR EXISTING GITHUB REPOSITORY
1. index.html
2. login.html
3. student-dashboard.html
4. mentor-dashboard.html
5. admin.html
6. onboarding.html
7. student-test.html (test-only page)
8. dashboard.html

PHONE-FRIENDLY DEPLOYMENT
- Download and extract this ZIP on your phone.
- In GitHub, open each named file at repository root, choose Edit, replace all content with the matching extracted file, and Commit.
- Keep filenames exactly as listed.
- Do not upload this ZIP as a substitute for replacing the individual files.
- Test homepage, login, student login, assigned lesson and video, mentor login, onboarding and admin page after deployment.

IMPORTANT FUNCTIONALITY NOTES
- Existing homepage content and inline application scripts were preserved; the visual system is applied as CSS overrides.
- Login uses the existing Supabase project and publishable browser key; no service-role key is included. It does not automatically redirect an existing session, avoiding a blank-page loop while the portal is being tested.
- Student and mentor pages preserve the existing data logic. Mentor page remains a read-only overview; lesson upload/assignment UI is not added in this theme-only update.
- Admin page is visually styled but still needs separate Supabase authentication/RLS review before production use.
- This is a visual integration package, not a live deployment. GitHub files must be updated and committed by you.

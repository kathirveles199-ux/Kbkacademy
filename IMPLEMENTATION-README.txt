KBK ACADEMY — DESIGN IMPLEMENTATION PACKAGE
Theme: Modern Gurukulam + Examination Command Centre
Brand statement: KNOWLEDGE · BRILLIANCE · SKILL
Palette: Forest green #123C2D, academic gold #C4A45B, warm ivory #F7F5EF.

FILES
- index.html: Homepage reordered so the hero appears first, then ticker, then exam opportunities; horizontal SVG logo and brand palette applied.
- login.html: Refined login screen with the new emblem and favicon.
- student-dashboard.html / mentor-dashboard.html: Academy branding bar added; existing Supabase logic retained.
- admin.html, onboarding.html, student-test.html, dashboard.html: Brand emblem and favicon applied where appropriate.
- assets/kbk-emblem.svg: Scalable emblem.
- assets/kbk-logo-horizontal.svg: Horizontal header logo.
- favicon.svg: Browser icon.

DEPLOYMENT
1. Extract the ZIP.
2. In the GitHub repository root, replace the matching HTML files.
3. Upload the entire assets folder (preserve the folder name and file names).
4. Upload favicon.svg to the repository root.
5. Commit changes.
6. Wait for GitHub Pages to deploy, then open the site with ?v=design2.

NOTES
- This package does not deploy itself; it must be committed to the GitHub repository.
- The homepage uses existing page content and scripts; this is an implementation pass, not a pixel-perfect screenshot-to-code reproduction.
- Verify login, student lessons, video playback, and mentor/admin access after deployment.
- Do not expose Supabase service-role keys in client files.

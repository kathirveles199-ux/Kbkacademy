KBK ACADEMY — PHASE 1 PRESENTATION / LAUNCH PACKAGE

Included files
- index.html: public homepage; exam cards lead to diagnosis.html. Mentor/admin/student portal links are not included.
- diagnosis.html: profile and exam diagnosis flow. It restores the homepage exam selection when possible.
- study-plan.html: displays baseline score, focus areas and seven-day plan.

Phase 1 scope
Public homepage -> student diagnosis -> study plan. No student registration, no online payment, no course purchase, no automatic course assignment, no student/mentor/admin dashboards.

Payment and course access
Until a secure payment gateway and server-side payment verification are implemented and tested, do not accept payment details on this static website. KBK staff may register a student manually after independently confirming payment. Course assignment remains a manual/admin process outside this Phase 1 site.

Data and privacy limitations
Diagnostic results use browser localStorage only. They are not uploaded to Supabase and do not follow a student across devices. Do not treat the diagnostic as a formal eligibility assessment. Review privacy notice/contact details before public launch.

Deployment
Upload these three HTML files to a separate Git branch or a separate GitHub Pages staging repository for mentor review. Do not overwrite the current live files. If deploying under a subfolder, keep all three files together.

Testing checklist
1. Homepage exam card opens diagnosis.html.
2. Selected exam is reflected where a matching target exists.
3. Complete all diagnostic steps; results and plan display on study-plan.html.
4. Refresh study-plan.html in the same browser; locally saved results remain.
5. Open study-plan.html in a fresh browser; it should show the no-results message.
6. Confirm there are no links to login.html, dashboard.html, student-dashboard.html, or mentor-dashboard.html in the public journey.

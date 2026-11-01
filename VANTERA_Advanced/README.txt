VANTERA REDESIGN — FRONTEND PROTOTYPE
====================================

START HERE
Open index.html in a browser. The project uses plain HTML, CSS and JavaScript. No build step is required.

WHAT CHANGED
- Redesigned the public landing page around students, educators, schools, guardians, businesses and personal users.
- Rebuilt role-specific student, educator, school, business and personal workspaces.
- Added Finance with browser-local demo income/expense transactions, categories, filters, totals and a comparison chart.
- Added pages for parents/guardians, messages, notifications, memberships, assignments, subjects, progress, classes, attendance, grades, school staff, reports, permissions, academic setup, live sessions, inventory and customers.
- Reworked registration/login fields and browser-side validation, including username/email/phone login identifier, international calling code selector, optional second phone, 8–64 character password and confirmation.
- Added mobile navigation, workspace switching demo, visible prototype notices, responsive styling and complete-logo image treatment.

IMPORTANT LIMITATIONS
This is a frontend prototype. There is no backend, database, real authentication, email/SMS verification, password reset delivery, permission enforcement, live messaging, payment system or server-side file storage. The Finance demo stores sample transactions in this browser only and is not an accounting ledger. Do not enter real sensitive data or use this as a live service.

SECURITY AND PRODUCT REQUIREMENTS FOR THE NEXT PHASE
- Implement server-side authentication and authorization for every protected request.
- Use secure password hashing, session management, rate limits, recovery controls and email/phone verification.
- Model accounts separately from school/class/business memberships; membership removal must not delete the global account.
- Scope all records to the appropriate school, class, business and role; log sensitive administrative actions.
- Design child/guardian privacy, consent, retention and safety before implementing location or messaging features.
- Add a real database, validation, backups, tests, monitoring and deployment configuration.

TECHNOLOGY
HTML + CSS + vanilla JavaScript.

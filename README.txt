GGCHST ADMIN — 10 FUNCTION SUITE

Files:
- admin.html — hub for all 10 functions
- admin-users.html — User & Role Management
- admin-dashboard.html — Admin Dashboard
- admin-notes.html — Lecture Notes
- admin-assignments.html — Assignments
- admin-finance.html — Finance & Fees
- admin-notices.html — Notices & Announcements
- admin-calendar.html — Academic Calendar
- admin-settings.html — System Settings
- admin-audit.html — Audit & Activity Logs
- admin-reports.html — Reports & CSV Export

Firebase:
Project: ggchst-sms-new
The Firebase web configuration is included in the files based on the project configuration supplied for this SMS.

IMPORTANT:
1. These pages use Firestore. Create/allow the referenced collections in Firestore as needed.
2. Client-side HTML cannot provide real security. Production security must be enforced with Firebase/Firestore Security Rules and, where required, trusted server/Admin SDK code.
3. User creation here manages the Firestore user profile. It does not securely create Firebase Authentication accounts.
4. Financial records and approved results should have server-side authorization and immutable/audited workflows.
5. The blueprint specifies a relational database for core institutional records; this package keeps compatibility with the user's current Firebase project and should be treated as an implementation layer, not a replacement for the blueprint's long-term architecture.
6. Existing modules such as student.html, results.html, attendance.html, academic-session.html, examination.html, course-registration.html and user-management.html are not replaced by this package.

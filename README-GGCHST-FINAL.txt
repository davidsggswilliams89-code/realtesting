GGCHST SCHOOL MANAGEMENT SYSTEM - CLEAN PROJECT BUILD

Firebase project:
ggchst-sms-new

Verified Firebase API key used across this build:
AIzaSyAoT3LGcdwA3FzHDrPEuhTNCnfiTklGXY

ADMIN ENTRY:
1. Open admin-login.html
2. Sign in with an active Firebase Admin account.
3. Admin authentication is checked against the users collection.
4. Successful login opens admin.html.
5. Direct access to admin.html without an authorized Admin session redirects to admin-login.html.

CREATE ACCESS:
create-access.html creates NEW Student, Lecturer and Staff accounts.
Passwords are used only for Firebase Authentication account creation and are not written to Firestore.
Firebase UID is the permanent link between Authentication and the school record.
Created accounts can be activated/deactivated from the access list.

ACADEMIC STRUCTURE:
Academic Session -> Semester -> Programme -> 100/200/300 Level -> Course
No Faculty or Department is part of the active academic structure.

COURSE FLOW:
Programme Course Setup -> Curriculum Mapping -> Lecturer Course Assignment -> Student automatic course visibility.
Students do not manually register courses.

KEY ACTIVE MODULES:
admin-login.html
admin.html
create-access.html
academic-session.html
levels.html
programme.html
course-registration.html
curriculum-mapping.html
assignment-management.html
lecturer-course-assignment.html
timetable.html
results.html
student.html
lecturer-login.html
lecturer-profile.html
admin-attendance.html
admin-finance.html
admin-notes.html
admin-assignments.html

DEPLOYMENT:
Keep logo.png in the same folder as the HTML files.
Use admin-login.html as the Admin entry point.
Do not expose or distribute Admin passwords.

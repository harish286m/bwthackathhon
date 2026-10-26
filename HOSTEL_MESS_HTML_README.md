# Hostel Mess Management System (HTML + CSS + JavaScript)

One file: `hostel_mess.html` (HTML structure, CSS styling and JavaScript logic together).

## How to run
1. Save `hostel_mess.html` anywhere on your PC.
2. Double-click it, or in VS Code right-click > "Open with Live Server" (optional).
3. Sign in with a demo account.

No installation, no server, no internet needed.

## Demo logins
| Role | Username | Password |
|---|---|---|
| Admin / Warden | admin | admin123 |
| Mess Staff | staff | staff123 |
| Student | student | student123 |

## Features
- Admin: dashboard, add/search/remove students, edit weekly menu, mark attendance, create fees and record simulated payments, respond to complaints, food-waste records, CSV exports.
- Staff: dashboard, menu, mark attendance, food-waste records with demand estimate.
- Student: dashboard, menu, own fees and payments, complaints with status/response, planned meal absences.
- Wastage % = leftover / prepared x 100. Suggested preparation = attendance rate x students not absent + 5% (labelled as an estimate).

## Important limits
- Data is stored in your browser (localStorage). It stays on this browser only. "Reset demo" restores the sample data.
- There is no real server, so logins and roles are a demo. Anyone can open the file and read the passwords in the code. Do not use it for real student data. The Django version is the one with real server-side security.
- Payments are simulated; never enter card or bank details.

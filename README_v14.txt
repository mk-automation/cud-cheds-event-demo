V14 update: IRP login gate

IRP Department now requires login before the IRP dashboard opens.

Demo credentials:
Username: irp@cud.ac.ae
Password: IRP123!

- Successful login is stored only for the current browser tab/session using sessionStorage.
- Logout clears the demo session.
- Event Organizer remains accessible from the shared public link.
- Attendance QR same-page routing from v13 is retained.

IMPORTANT: This is only a front-end demo login. Credentials in static JavaScript are not secure.
The final XAMPP/MySQL version must use server-side password hashing, sessions, role authorization and database-backed IRP accounts.

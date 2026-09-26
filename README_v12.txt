v12 QR FIX
The regression in v10/v11 is fixed.

QR destination is now a real page:
attendance.html?event=<id>&code=<event-code>&name=<event-name>

This means:
- QR scan opens attendance.html directly.
- Event name and Event ID travel in the QR URL, so the attendance page can identify the event even on another phone.
- PDF QR uses exactly the same QR generated on screen.
- Open Attendance Sheet button uses the same URL.

Important static-demo limitation:
GitHub Pages/localStorage cannot share attendance data between the organizer PC and a participant phone.
The final XAMPP/MySQL version will store attendance centrally and update the IRP/organizer dashboard across devices.

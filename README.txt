CUD CHEDS Functional GitHub Demo v8 — based on Demo 4 design.

This is a true interactive static demo:
- Two portals: Event Organizer and IRP Department.
- Organizer creates events using the detailed CHEDS form.
- Submission generates Event Code and QR.
- QR encodes #attendance-EVENTID and opens the attendance sheet for that event.
- Attendance submission increments QR Attendance and blocks duplicates in browser storage.
- Organizer can add Manual Attendance and evidence file names in Post Event.
- Total = QR + Manual.
- IRP dashboard filters/categorizes by School, Program, Department and Category.
- IRP can export the filtered event register as CSV.
- Data persists in the browser via localStorage.

GitHub Pages:
Upload index.html, style.css and README.txt to the repository root and enable Pages.

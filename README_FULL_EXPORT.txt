Full Pre/Post IRP export enhancement.

The IRP Excel download now produces ONE workbook with TWO sheets:

1) CHEDS Events
   - 30-column CHEDS submission format based on the supplied Institute Events workbook.
   - Event_Attendees = QR Attendance + Manual Attendance.

2) Full Pre-Post Data
   - Event ID and Status
   - Creator CUD Email
   - all Pre-Event fields captured by the application
   - QR Attendance
   - Manual Attendance
   - Total Attendance
   - Evidence file names
   - Post-Event Remarks
   - Post submission timestamp

IRP dashboard filters continue to control which event rows are exported.

Note for static demo:
Browser file inputs cannot permanently retain/upload the actual evidence file bytes. The demo records evidence file names.
The final XAMPP/MySQL version should store uploaded evidence on the server and export evidence links/paths.

IRP Excel export updated to match the uploaded CHEDS Institute Events workbook structure.

The IRP button is now:
Download CHEDS Excel

Output:
Institute-Events-CHEDS.xlsx
Sheet: Events

Column order exactly follows the supplied template:
Events_InstCode through Remarks (30 columns).

Fixed institutional values:
Events_InstCode = 19
Events_InstName = Canadian University Dubai

Event_Attendees = QR Attendance + Manual Attendance.

IRP dashboard filters are respected: if IRP filters by School/Department/Program/Status,
the Excel download contains the filtered event rows.

Note: Static demo uses SheetJS in the browser and requires internet to load the export library.
The final XAMPP version can generate the XLSX server-side.

V13 definitive QR routing fix

The QR NO LONGER depends on attendance.html.

It points back to the SAME published index.html using:
?attendance=<id>&code=<event-code>&name=<event-name>

Example:
https://YOUR-GITHUB-PAGES-SITE/index.html?attendance=123&code=CUD-EVT-2026-0003&name=COURSE%20FILE%20WORKSHOP

Because the QR opens the same index.html that is already working, scanning it cannot fail due to a missing attendance.html deployment.

IMPORTANT:
After uploading v13 to GitHub, create a NEW event / regenerate the QR. Old QR images/PDFs still contain their old destination and cannot change automatically.

The QR screen now prints the exact QR destination below the QR so it can be checked before scanning.

Static GitHub limitation remains: another phone can open and submit the attendance form, but its browser localStorage cannot update the organizer PC's localStorage. The final XAMPP/MySQL version will provide shared central counting.

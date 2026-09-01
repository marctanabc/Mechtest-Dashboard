MECHTEST DIGITAL SIGNAGE PLAYER

1) Put your two MP4 files in the media folder.
   - first video:  ad1.mp4
   - second video: ad2.mp4

2) Double-click index.html to test in Google Chrome.

3) The sequence is:
   Ad 1 -> Ad 2 -> Dashboard for 60 seconds -> repeat.

4) Dashboard data source:
   https://docs.google.com/spreadsheets/d/e/2PACX-1vSgYkO7VW6kAjGgYS8BfIprjsD8l82rbrkaBNUxzmHiNftLWBScM513EsZTy6lV7L9fpFA_nj9Zpfsl/pub?gid=738983995&single=true&output=csv

5) The dashboard checks Google Sheets every 30 seconds while running.

6) For TV kiosk mode, create a Chrome shortcut with a target similar to:
   "C:\Program Files\Google\Chrome\Application\chrome.exe" --kiosk "C:\MechTest-Signage\index.html"

IMPORTANT:
- Internet is required for the live Google Sheets percentages.
- Videos are local, so they still play if the internet drops.
- The dashboard falls back to the last/default values if the sheet cannot be reached.

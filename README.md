File editing is open to everyone who wants to add a new hospital helipad.

Make sure to know what you are doing. Wrong edits will corrupt the file.

Tip for the editors: Add your custom helipads at the beginning of the file, the line after after the very first (and most left) bracket "["
Add lines in this format:
  [
    48.2188903,
    16.4634503,
    "Donauspital / SMZ-Ost",
    "Klinik Donaustadt"
  ],


  Latitude and longitude must be numerical (google maps format) and latitude on first line, longitude on second line.

  Make sure to respect brackets and commas.

To update the DB, make sure to: 
1) download the H_hospital.json
2) Copy it in \Community\hpg-airbus-h145\html_ui\HPGH145-System\db
3) Update mission index
4) Use MSFS Layout Generator to update the h145 layout.json (this may be optional, but if you don't see the DB anymore, this step will be necessary). The update of layout.json may be optional on msfs20.

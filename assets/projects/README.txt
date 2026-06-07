ALTER — PROJECTS FOLDER (how it works)
=====================================
Each subfolder here = one project. Inside a project folder put images named:
  01.jpg  -> the MAIN image (shown in the work grid)
  02.jpg, 03.jpg, ... -> the gallery (shown when the project is opened)
(.jpg / .jpeg / .png all fine. They are auto-resized on build.)

A folder already has a _fallback.txt listing the current Wix images — these
stay live until you drop your own images into the folder.

TO EDIT A MAIN IMAGE: replace 01.jpg in that project folder.
TO ADD A PROJECT: create a new folder (e.g. "13_NewClient"), drop images in it,
   then add a row in Projects.xlsx (Order, Folder, Key, Title, Size, Location, In Grid, Description).
TO REORDER / show-hide in grid: edit Projects.xlsx.

When done, tell Claude "rebuild projects" and it runs the build.

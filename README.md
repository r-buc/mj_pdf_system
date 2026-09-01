# MJ PDF (system)
This is a fork of [MJ PDF Reader](https://gitlab.com/mudlej_android/mj_pdf_reader) from Gitlab to fix compilation issues and to allow integrating it as a system app in custom ROMs.
Changes made:<br>
1. Removed launcher icon and internet permission
2. Removed intro
3. "High quality rendering" is turned on by default
4. Removed temporary file copying (it unnecessarily copied PDFs into `/storage/emulated/0/Documents/MJ PDF`)

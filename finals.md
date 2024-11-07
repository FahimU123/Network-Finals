# Network Finals

# Setting Permissions For Others Remotely

1. Create a folder in desktop
2. Right click and select properties
3. Select sharing
4. Select advanced sharing
5. Select permissions
6. Give full control
7. Click ok
8. Go back to properties
9. Select security
10. Select Everyone
11. Select edit
12. Give control
12. Ok


# Enabling Auditing

1. Open Windows Adminstrative Tools
2. Select Local security policy
3. Local policies
4. Audit Policy
5. Audit object access
6. Click on properties to check success and failure
7. Now open event viewer
8. Clear security before you start
9. After you have moved the files look for it in security
10. The giveaway is the lock sign for failed attamets


# Seeing file transfers in wireshark

1. Start scanning buy clicking blue fin
3. Stop scan
3. Filter with smb2

# Creating a Backup

1. Create a new text document in C
2. Open Powershell
3. Go to root(cd\)
4. Type ls to list all files
5. Look for the file you just created
6. Type Get-FileHash FILENAME (When you make changes to the file and save it, the hash WILL chnage)
7. Open control panel
8. Select Backup and Restore
9. Select Set up backcup
10. Select your thumb drive
11. Select let me choose
12. Deselect all items in data files
13. Expand Localdisk
14. Select folder you would like to backup
15. Delet orginal folder on C
16. Commence a restore 

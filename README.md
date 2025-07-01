# Anydesk
License renew or session out issue

To reset your AnyDesk ID, you'll need to close AnyDesk, navigate to the AnyDesk configuration folder, and then rename or delete the service.conf file. This forces AnyDesk to generate a new ID the next time it's opened. 

Here's a step-by-step guide:

1. Close AnyDesk:
Ensure AnyDesk is completely closed, including any background processes. You can do this by right-clicking the AnyDesk icon in the system tray and selecting "Exit" or by ending the AnyDesk process in Task Manager. 

2. Locate the AnyDesk Configuration Folder:
Open File Explorer and navigate to C:\ProgramData\AnyDesk. 

3. Rename or Delete service.conf:
Rename the service.conf file to something like service_backup.conf or delete it entirely. 

4. Restart AnyDesk:
Open AnyDesk again. It will detect the missing configuration file and create a new one, generating a new AnyDesk ID. 

Important Notes:
Backup:
Before deleting or renaming service.conf, consider making a backup copy in case you need to revert to your previous settings. 

Cloned ID:
If you're dealing with a cloned AnyDesk ID, resetting it this way will generate a new one. 

License:
Resetting the ID does not affect your AnyDesk license. If you need to reset your license key, you can do so in the my.anydesk management portal. 

This video demonstrates how to change the AnyDesk ID easily:
https://youtu.be/dZBbNeFFt0g

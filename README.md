# A simple backup script in Shell Script

This script backs up your machine after you run the command:
```bash
 ./backuphw.sh -l or --login 
 ```
on your terminal emulator, if you need help, run the command:
 ```bash
 ./backuphw.sh -h or --help 
 ```
to open the help menu.

The script will back up the **NEW** directory, if you do not have the **NEW** directory in your **HOME** directory the script will not back up.

The backup will be saved in the **BACKUP** directory, if you don't have this directory in your **HOME** directory don't worry, the script will create this directory and perform the backup.

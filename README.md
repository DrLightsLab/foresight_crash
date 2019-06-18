# Foresight Crash
An application that backs up the Monster Hunter world steam save file.

# Parry This You Filthy Casual!
1.  Download the zip file and extract the contents to a new directory. (E.G.: C:\Program Files (x86)\Foresight Crash)

2.  Get the path to your Steam user account. (E.G.: C:\Program File(x86)\Steam\userdata\1111111)
    - NOTE: 111111 is just an example user account.

    2a.  Make sure that the 582010 directory is in that user account directory. (E.G.: C:\Program File(x86)\Steam\userdata\1111111\582010)
        - NOTE:  582010 is the default monster hunter world steam save file directory (per Capcom Support: https://steamcommunity.com/app/582010/discussions/0/1745594817430281693/). 
          If you do not have this, you are in the wrong directory.

3.  Parry That Shit! (Run the application)

    3a.  Nice parry!  You just created a config.json file and backup_log.txt file in the directory you ran this in!
        - config.json stores Foresight Crash data like the path you give it, the back up directory, etc.
        - backup_log.txt is a simple log file of all the successful backups of the save file
        
4. You will be prompted for the path to the Steam user account.  Paste the path to the Steam user account we got in Step 2.
    - NOTE: Full path! (E.G.: C:\Program File(x86)\Steam\userdata\1111111)

5. You will be prompted if you want to use the default backup directory. Enter y or n
    - NOTE: The default is: C:\backup\foresight_crash_backup\mhw

6.  Did it work?  Verify by checking the backup directory or the backup_log.txt inside of the Foresight Crash directory.

7.  If there is no SAVEDATA1000 in your backup directory then browse to the Foresight Crash directory (where the executable is).

8.  Check for an error.log file in the directory and contact me by raising an issue and posting the error you received.

9.  If it worked, you're all done.  The next time you run Foresight Crash, you will not be prompted at all!  If you are unsure,
    check the Last Modified Date of the SAVADATA1000 file in the backup directory, or check the backup_log.txt file in the 
    Foresight Crash directory.

Thanks

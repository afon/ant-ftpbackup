ant-ftpbackup
=============

Ant based routine to backup your site via ftp.
It's free as a free beer, but will take you several minutes to install. 

Abilities: 
- backup your site via ftp;
- create archive each time when backup;
- download only newer or changed files - this will save you some trafiic and time;
- create new archive only if there were newer or changes files - this will save you several megabytes on your HDD.

Installation (short): 
- download and install Java (meaning JRE) and add JAVA_HOME environment variable;
- download and unzip Ant;
- download this ftpbackup.xml, change properties like user, password, host etc;
- run from command line "ant -f ftpbackup.xml" and enjoy your backup process. 

Scheduling: 
- use scheduler embedded in your OS. This will "crontab" on linux and "Task Scheduler" on Windows. 

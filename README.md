ant-ftpbackup
=============

Ant based routine to backup your site via ftp (meaning from ftp to local hdd).
It's free as a free beer, but will take you several minutes to install. 

Abilities: 
- backup your site via ftp;
- create archive each time when backup;
- download only newer or changed files - this will save you some network traffic and time;
- create new archive only if there were newer or changed files - this will save you several megabytes on your HDD;
- take care for log file from last backup process.

Installation (short): 
- download and install Java (meaning JRE) and add JAVA_HOME environment variable;
- download and unzip Ant and add ANT_HOME environment variable; 
- run 'ant -f fetch.xml' from ANT_HOME directory for fetching several additional ant libraries;
- download this ftpbackup.xml, change properties like user, password, host etc;
- run from command line "ant -f ftpbackup.xml" and enjoy your backup process. 

Scheduling: 
- use scheduler embedded in your OS. This will "crontab" on linux and "Task Scheduler" on Windows. 

#Scripts for administrating Nagios - in CLI and GUI 
Some scripts to administrate my Nagios
##Bash scripts
These scripts administrate the creation of new hosts, by parsing and asking service templates and hostgroups template.

I used whiptail to generate some windows to administrate more easily my Nagios.
![Whiptail GUI](http://i.imgur.com/uCNwLwX.png)
## /!\WARNING/!\
These scripts are just some tests. Don't use it in production (or customize it before)
##My directory Tree
For an example, this is my directory tree of my Nagios install

├── bin
├── etc
│   ├── objects
│   │   ├── commands
│   │   ├── hostgroups
│   │   ├── hosts
│   │   │   ├── esx_hosts
│   │   │   ├── linux_hosts
│   │   │   ├── web_hosts
│   │   │   └── windows_hosts
│   │   └── servicegroups
│   └── templates
├── include
├── libexec
│   └── eventhandlers
│       ├── distributed-monitoring
│       └── redundancy-scenario1
├── sbin
├── share
│   ├── contexthelp
│   ├── docs
│   │   └── images
│   ├── images
│   │   └── logos
│   ├── includes
│   │   └── rss
│   │       └── extlib
│   ├── js
│   ├── locale
│   │   ├── de
│   │   │   └── LC_MESSAGES
│   │   └── fr
│   │       └── LC_MESSAGES
│   ├── media
│   ├── ssi
│   └── stylesheets
└── var
    ├── archives
    ├── rw
    └── spool
        └── checkresults

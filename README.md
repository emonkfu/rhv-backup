# rhv-backup
Script to run daily to backup RHV Manager

This creates local file backup, and option to scp it to remote host for off-RHVM backup location.
Also includes ability to age out files both locally and also (optionally) remote.

All configuration settings are varibles in start of script for easy customization.

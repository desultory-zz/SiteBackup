# SiteBackup
script that is degined to back up a given site and can be run as a cron job and will only download when changes are made

usage: 
chmod +x sitearchive
./sitearchive

this script will download the current version of the site specified in the script.  Additionally, it will not download any filetypes other than the types specified.  I did this because after a day of running this, the script ended up downloading hundreds of gigabytes of videos which is undesireable

usage: 
chmod +x sitearchiveALL
./sitearchiveALL

the only difference in this script is that it will get all files.  If the site hosts videos this WILL use a lot of data

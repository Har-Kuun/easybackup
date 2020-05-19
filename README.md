# easybackup
A Short and Easy Website Files/DB FTP Backup Script
Works for websites with single DB.

## First time:

### For Ubuntu/Debian:
```
apt-get install ftp -y
wget https://raw.githubusercontent.com/Har-Kuun/easybackup/master/backup.sh && chmod +x backup.sh && mkdir ~/backup
```
### For CentOS/Fedora:
```
yum install ftp -y
wget https://raw.githubusercontent.com/Har-Kuun/easybackup/master/backup.sh && chmod +x backup.sh && mkdir ~/backup
```

## Then:
Edit the 2-12 lines of backup.sh with your own DB credentials, FTP credentials, and your file paths.

## Backup:
```./backup.sh```

### If you are looking for a stable FTP backup storage service, take a look at [1fichier](https://1fichier.com/?af=2896848).

Thanks for using this script.

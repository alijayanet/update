# update
# INSTALL UPDATER GENIEACS OTOMATIS
This is autoinstall GenieACS 

# Usage
```
apt install git curl -y
```
```
git clone https://github.com/alijayanet/update
```
BACKUP SETINGAN GENIEACS YANG SUDAH ADA
```
sudo mongodump --db=genieacs --out genieacs-backup >/dev/null 2>&1
```
RESTORE/UPLOAD PRESET PROVISION VIRTUAL PARAMETER UPDATE
```
sudo mongorestore --db=genieacs --drop update >/dev/null 2>&1
```


#!/bin/sh
cd /home/jk/Desktop/backup
mysqldump -u root -proot jk --ignore-table=jk.ignoretable > backupdatas.sql
git add -A
git commit -m "mydbbackup`date`"
git push live master
git push origin master



# ubuntu-1604-mysql-backup

This repository contains a few scripts for automating backups with Percona Xtrabackup and Innobackupex

Fork of [this repository](https://github.com/do-community/ubuntu-1604-mysql-backup) with backup encryption removed. 
For our system ability of restore backup is much more important than encryption. 
Encryption key might be lost when time comes to restore backup.

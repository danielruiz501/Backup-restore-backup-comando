# 03-backup-restore-backup-comando.txt

mysqldump -u root -p ecommerce > ecommerce_backup.sql

mysql -u root -p ecommerce < ecommerce_backup.sql


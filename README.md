# MySqL-logger
Useful one liner commands to troubleshoot mysql

logging Processlist while a mysqlp dump is being restored to identify the query at which the dump fails. 

mysqladmin -u root -p -i 1 processlist| grep magento | tee /opt/sql_restore_log.txt

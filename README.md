# skprojects
skprojects
#!/bin/bash
sudo yum update -y
yum install httpd -y
echo "this is skprojects" > var/www/html/index.html
service httpd start 
chkconfig httpd on

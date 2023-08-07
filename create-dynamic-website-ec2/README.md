sudo yum install -y httpd
sudo systemctl start httpd
sudo systemctl enable httpd
sudo dnf install -y httpd 


The script starts by elevating the user's privileges to superuser (root) using sudo su.
It then updates the system's package repository using sudo yum update -y.
Next, it installs the Apache HTTP Server (httpd) using sudo yum install -y httpd.
The script starts the httpd service using sudo systemctl start httpd.
To ensure that httpd starts automatically on system boot, the script enables the service using sudo systemctl enable httpd.


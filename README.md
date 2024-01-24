# The three types of cryptography are:

# 1. Secret key cryptography
# 2. Public key cryptography
# 3. Hash function cryptography 

# Linux-Focal-Fossa-Ubuntu-20.04-Apache2-Open-SSL-installation

# open terminal type
# sudo su
#  apt install open ssl
#  open ssl version

# installation of Apache2 server.
#  apt install apache2 
#  systemctl is-enabled apache2.service
# apache2 version

# Now install firewall.
# apt install ufw
# ufw allow 80/tcp comment 'accept Apache'
# ufw allow 443/tcp comment 'accept HTTPS connections'
# ufw status

# change your password in the start button ->Settings and logout.

---------------------------------------------------------------
# Extra Apache2 server commands.

#Start the apache2 server
# sudo systemctl start apache2.service

#Stop the apache2 server
# sudo systemctl stop apache2.service

#Restart the apache2 server
# sudo systemctl restart apache2.service

#Reload the apache2 server gracefully
# sudo systemctl reload apache2.service

#Find the status of apache2 server
# sudo systemctl status apache2.service

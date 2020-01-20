# soma elearning platform 
This is a bundled elearning platform package developed by Tunapandanet for community networks.
A site demo can be found [here](http://197.136.151.9/soma)
Installation 
Dependancies 
# Prerequisites 
[Install LAMP Stack on Ubuntu 18.04](https://phoenixnap.com/kb/how-to-install-lamp-stack-on-ubuntu)
[Installing apache](https://www.liquidweb.com/kb/install-apache-2-ubuntu-18-04/)
[Installing phpmyadmin](https://www.liquidweb.com/kb/install-phpmyadmin-ubuntu-18-04/)

#Installation

1. Go to your root directory
>cd /var/www/html

2. Create a folder <your elearning learn site name>
>mkdir learn

3. Change folder permissions
> sudo chmod -R 755 learn

4. Change folder ownership permissions
 > sudo chown -R www-data:www-data learn
5. Upload the two files to your main root folder (installer.php and the zip folder) using Filezilla or your recommended ftp software
> you can also copy your files directly using scp 
  scp 

6. Open your browser and go to localhost/installer.php or your_ip_address/installer.php to confirm your have the right setup 
> e.g 192.168.136.10/installer.php or localhost/installer.php

7. Create a database for your new elearning website using phpmyadmin  
  - Open Phpmyadmin through your server_ip/phpmyadmin or localhost/phpmyadmin 
  > e.g 192.168.0.10/phpmyadmin or localhost/phpmyadmin
  - enter user & password then login to create your server's database
  
  Create a database
  utf_unicode_ci
  > Enter these details in the running installer
8. Follow the instaractions to finnish your installation

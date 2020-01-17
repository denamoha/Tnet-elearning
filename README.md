# Tunapandanet's elearning platform 
This is an bundled elearning platform package developed by Tunapandanet for community networks.
platform demo can be found <here>
Installation 
Dependancies 
# Prerequisites 

Install LAMP Stack on Ubuntu 18.04

#Installation
Setup Lamp server
Phpmyadmin to manage the database 
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

# Soma elearning platform 
This is a bundled elearning platform package developed by Tunapandanet for community networks.
A site demo can be found [here](http://197.136.151.9/soma)
Installation 
Dependancies 
# Prerequisites 

Required Files
* installer.php from this repo
* Zipped File downloadable from this [link](https://drive.google.com/file/d/1x_Aup_dAJkHoKZ-gJxOZ5Tcg2Z6O2gqM/view?usp=sharing)

[Install LAMP Stack on Ubuntu 18.04](https://phoenixnap.com/kb/how-to-install-lamp-stack-on-ubuntu)

[Installing apache on ubuntu](https://www.liquidweb.com/kb/install-apache-2-ubuntu-18-04/)

[Installing phpmyadmin on ubuntu ](https://www.liquidweb.com/kb/install-phpmyadmin-ubuntu-18-04/)

# Installing Soma



1. Go to your root directory(terminal)
>cd /var/www/html

2. Create a folder <your elearning site's name>
>mkdir Soma

3. Change folder permissions
> sudo chmod -R 755 Soma

4. Change folder ownership permissions
 > sudo chown -R www-data:www-data Soma
5. Upload the two files to the folder you created (installer.php and the zip folder) using Filezilla or your Preffered ftp software
> you can also copy your files directly to your server using the scp command on terminal 
  scp 
 
 > scp file.txt username@to_host:/remote/directory/

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

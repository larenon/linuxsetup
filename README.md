## AWS_UBUNTU ##

Install Apache, MySQL, PHP and phpMyAdmin
```
curl https://raw.githubusercontent.com/larenon/linuxsetup/master/install/amp_debian.sh | bash
```

## Letsencrypt SSL 
```
sudo certbot --apache -d Domain.com
```
## Secure PHPMYADMIN
```
sudo nano /etc/apache2/conf-available/phpmyadmin.conf

and change alias from /phpmyadmin to /customname
```

## AWS_UBUNTU

Install Apache, MySQL, PHP and phpMyAdmin

- requires no user input
- sets a MySQL password and shows in console
- does not overwrite the MySQL password if it is already set

```bash
curl https://raw.githubusercontent.com/larenon/linuxsetup/master/install/amp_debian.sh | bash

sudo certbot --apache -d Domain.com

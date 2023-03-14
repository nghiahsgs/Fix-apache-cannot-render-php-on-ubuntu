# Fix-apache-cannot-render-php-on-ubuntu
Fix apache cannot render php on ubuntu


## Install the PHP module for Apache: 
You also need to install the PHP module for Apache. You can do this by running the following command:

```
sudo apt-get install libapache2-mod-php
```
OR
```
sudo apt install libapache2-mod-php8.0
```
OR
```
sudo apt-get install libapache2-mod-php
```

## Activate php module on apache
Check the available PHP modules: Run the following command to list the available PHP modules on your system:
```
ls /usr/lib/apache2/modules/libphp*.so
```

Enable the PHP module: Once you have identified the appropriate PHP module, you can enable it by running the following command:

```
sudo a2enmod <module-name>
```


Restart Apache: Finally, restart the Apache web server to apply the changes
```
sudo systemctl restart apache2

```

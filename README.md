Setup za virtualni host

<VirtualHost *:80>
        DocumentRoot "/var/www/uvoduphp"
        ServerName uvoduphp.loc
        DirectoryIndex index.php

        <Directory "/var/www/uvoduphp">
                Options All
                AllowOverride All
                Require all granted
        </Directory>
</VirtualHost>

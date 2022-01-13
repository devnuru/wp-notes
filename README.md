## 1. php.ini codes
===============
<br />
upload_max_filesize = 256M
post_max_size = 256M
memory_limit = 256M
file_uploads = On
upload_max_filesize = 128M
max_execution_time = 300
max_allowed_packet_size = 524288000

###2. .htaccess codes
===================
php_value max_input_vars 5000
php_value max_execution_time 300
php_value post_max_size 128M
php_value upload_max_filesize 128M
php_value memory_limit 256M

###3. wp-config.php code
=====================
define( 'WP_MEMORY_LIMIT', '128M' );



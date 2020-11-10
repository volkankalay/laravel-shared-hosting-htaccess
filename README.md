# laravel-shared-htaccess
Laravel shared hostig htaccess file (exclude openlitespeed)

If you use SSL, please remove '#' on this lines.

#RewriteCond %{HTTPS} !=on

#RewriteRule ^ https://%{HTTP_HOST}%{REQUEST_URI} [L,R=301]

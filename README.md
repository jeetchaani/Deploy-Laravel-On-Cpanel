<h3>Deploy Laravel Project On Cpanel</h3>
1) Add following code to **.htaccess** in root directory-->
   
             <IfModule mod_rewrite.c>
              RewriteEngine On
              RewriteRule ^(.*)$ public/$1 [L]
             </IfModule>
   
3) change database credentials in .env file


RewriteEngine on
RewriteCond %{SERVER_PORT} 80
RewriteRule ^(.*)$ https:/suansuanmango.github.io/today/index.html$1 [R,L]

# to_code_4
.htaccess
RewriteEngine On # Activer le module Rewrite
RewriteRule ^produits/?$ produits.php [NC,L]
RewriteRule ^[^/]+/(\d+)$ produits.php?id=$1

# Magento2_outside_cart_redirect
 This Magento2 module is cart and redirect cart page for outside.

Copy Directory app/code
php bin/magento setup:upgrade
php bin/magento deploy:mode:set developer
php bin/magento c:f

url type:
https://url/outsidecart/index/carting?product=5_2,6_3....
5_2 => 5: Product id, 2: Qty

# Show-Free-Shipping-under-each-product-at-WooCommerce-Shop-list-page


Add the below code on function.php
```php

add_action( 'woocommerce_after_shop_loop_item', 'bbloomer_show_free_shipping_loop', 5 );
 
function bbloomer_show_free_shipping_loop() {
   echo '<p class="shop-badge">Free Shipping</p>';
}

< ?php
/*
Plugin Name: unlock-PayPal-China-Woocommerce
Description: 解锁人民币市PayPal不可用
Author: kidswong999
*/
add_filter( 'woocommerce_paypal_supported_currencies', 'enable_custom_currency' );
function enable_custom_currency($currency_array) {
  $currency_array[] = 'CNY';
  return $currency_array;
}
?>

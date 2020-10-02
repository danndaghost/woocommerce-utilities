# woocommerce-utilities

add_filter( 'woocommerce_email_recipient_customer_completed_order', 'your_email_recipient_filter_function', 10, 2);

function your_email_recipient_filter_function($recipient, $object) {
    $recipient = $recipient . ', xxxxxxxxx.xxxxxx@gmail.com';
    return $recipient;
}

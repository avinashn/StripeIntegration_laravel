## Prerequisites
<ul>
<li>After cloning this repository, go to the root folder, run the following command/s,
<pre>
    composer install
    composer update</pre>
</li>
<li>Rename .env.example to .env</li>
<li>Run <pre>php artisan key:generate</pre> </li>
<li>Replace dummy stripe secret key with you original stripe test Secret key here <code>\Stripe\Stripe::setApiKey ( 'sk_test_yourSecretkey' );</code>in <span title="/routes/web.php">web.php</span> file</li>
<li>Replace dummy stripe publishable key with you original stripe test publishable key at form's data attribute <code>data-stripe-publishable-key="pk_test_yourPublishableKey"</code>in  <span title="/resources/views/welcome.blade.php">welcome.blade.php</span> file</li>
</ul>

## Working Demo
You can see the demo of the project <a href="http://justlaravel.com/demos/integrate-stripe-payment-gateway-laravel/">here</a>

## Reference Post
<a href="http://justlaravel.com/integrate-stripe-payment-gateway-laravel/">http://justlaravel.com/integrate-stripe-payment-gateway-laravel/
</a>

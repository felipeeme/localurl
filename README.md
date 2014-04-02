/*

^(https?:\/\/)?[\w]+(\.[\w]+)*(\:[\d]+)*(\.[a-zA-Z\d]{2,})*(\/[\w\d\/\.\?\&\=\-]*)?$

*/
http://regexr.com/38ldi


Local URL RegEx validator. Includes local URLs and ports.
@author: github.com/felipeeme

# allowed
localhost
127.0.0.1:8080
http://localhost
https://myfalafel.org
https://www.myfalafel.org
https://myfalafel.org/cart
https://myfalafel.org/cart/checkout.php
https://myfalafel.org/cart/checkout.php
https://myfalafel.org/cart/checkout/view.php&param=01&param=03

# not allowed
ftp:// or unusual prefixes;
different characters that are not alphanumeric, underscore or /.?&=- after the dash;


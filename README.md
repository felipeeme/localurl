/*

^(https?:\/\/)?[\w]+(\.[\w]+)*(\:[\d]+)*(\.[a-zA-Z\d]{2,})*(\/[\w\d\/\.\?\&\=\-]*)?$

/*
<br />
<a href="http://regexr.com/38ldi" target="_blank">http://regexr.com/38ldi</a>


Local URL RegEx validator. Includes local URLs and ports.<br />
@author: github.com/felipeeme

# allowed
localhost<br />
127.0.0.1:8080<br />
http://localhost<br />
https://myfalafel.org<br />
https://www.myfalafel.org<br />
https://myfalafel.org/cart<br />
https://myfalafel.org/cart/checkout.php<br />
https://myfalafel.org/cart/checkout.php<br />
https://myfalafel.org/cart/checkout/view.php&param=01&param=03

# not allowed
ftp:// or unusual prefixes;<br />
different characters that are not alphanumeric, underscore or /.?&=- after the dash;


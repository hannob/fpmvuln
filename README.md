# fpmvuln
bash poc scripts to exploit open fpm ports

fpmexfil
--------

Will try to exfiltrate /etc/passwd from target host. Works with many hosts using
HHVM exposed on a public interface

fpmrce
------

Will try to execute PHP code on remote host. Works with most PHP installations exposing fpm
on the public port.

background
----------

* https://www.openwall.com/lists/oss-security/2019/07/09/2
* https://www.golem.de/news/fpm-sicherheitsluecke-daten-exfiltrieren-mit-facebooks-hhvm-1907-142418.html
* https://hhvm.com/blog/2019/06/10/hhvm-4.9.0.html
* https://www.openwall.com/lists/oss-security/2019/07/27/1

misc
----

There were previous, similar exploits for these issues:

* https://github.com/wofeiwo/webcgi-exploits/blob/master/php/Fastcgi/fcgi_exp.go
* https://gist.github.com/phith0n/9615e2420f31048f7e30f3937356cf75

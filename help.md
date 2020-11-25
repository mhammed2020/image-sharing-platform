# Heading1 Mastering python 3.x



## page 129  instagram project


* item 1
* Item 2
- Item 3
- Item 4
+ item 5
+ item 5


# Running the development server through HTTPS
Some of the social authentication methods you are going to use require an HTTPS
connection. The Transport Layer Security (TLS) protocol is the standard for serving
websites through a secure connection. The TLS predecessor is the Secure Sockets
Layer (SSL).
Chapter 4
[ 133 ]
Although SSL is now deprecated, in multiple libraries and online documentation
you will find references to both the terms TLS and SSL. The Django development
server is not able to serve your site through HTTPS, since that is not its intended
use. In order to test the social authentication functionality serving your site through
HTTPS, you are going to use the RunServerPlus extension of the package Django
Extensions. Django Extensions is a third-party collection of custom extensions for
Django. Please note that this is never the method you should use to serve your site
in a real environment; this is a development server.
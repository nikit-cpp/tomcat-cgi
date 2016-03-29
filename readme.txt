I run it in IntelliJ IDEA

0) Open $CATALINA_HOME/conf/web.xml
Uncomment servlet containing "org.apache.catalina.servlets.CGIServlet"

1) Chech that you Linux can execute
web/WEB-INF/cgi/hi-perl.cgi
if no, type
chmod +x web/WEB-INF/cgi/hi-perl.cgi

2) Open in browser
http://localhost:8080/cgi-bin/hi-perl.cgi

Resources
http://tomcat.apache.org/tomcat-8.0-doc/cgi-howto.html
http://www.wellho.net/forum/Perl-Programming/Running-Perl-CGI-scripts-under-Apache-Tomcat.html

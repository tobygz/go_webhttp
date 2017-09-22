# go_webhttp
a simple http server written in golang with request channel that can be easily used in your project.

[root@localhost go_web]# go run web.go <br>
Listening on ::8080<br>
Received message 10.6.1.16:50844 -> 10.2.61.130:8080 <br>
append len: 0 , str: /test<br>
Received message 10.6.1.16:50845 -> 10.2.61.130:8080 <br>
append len: 0 , str: /favicon.ico<br>


request in IE:http://10.2.61.130:8080/test<br>
the content in IE:<br>
hello web golang reqName: /test, map length: 1<br>

the request format below is well supported<br>
http://10.2.61.130:8080/test?a=123<br>
http://10.2.61.130:8080/test?a=123&b=4<br>

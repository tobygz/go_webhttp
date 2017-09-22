# go_webhttp
a simple http server written in golang with request channel that can be easily used in your project.

[root@localhost go_web]# go run web.go 
Listening on ::8080
Received message 10.6.1.16:50844 -> 10.2.61.130:8080 
append len: 0 , str: /test
Received message 10.6.1.16:50845 -> 10.2.61.130:8080 
append len: 0 , str: /favicon.ico


request in IE:http://10.2.61.130:8080/test
the content in IE:
hello web golang reqName: /test, map length: 1


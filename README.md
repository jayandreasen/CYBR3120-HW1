# CYBR3120-HW1


## 200 OK
nc -C portquiz.net 80  
HEAD / HTTP/1.1  
Host: portquiz.net  

HTTP/1.1 200 OK  
Date: Thu, 09 Sep 2021 12:13:03 GMT  
Server: Apache/2.4.29 (Ubuntu)  
Connection: close  
Content-Type: text/html; charset=UTF-8  


## 301 Moved Permanently  
nc -C dunwoody.edu 80  
HEAD / HTTP/1.1  
Host: dunwoody.edu  

HTTP/1.1 301 Moved Permanently  
Server: nginx  
Date: Thu, 09 Sep 2021 12:17:17 GMT  
Content-Type: text/html; charset=UTF-8  
Connection: keep-alive  
X-Powered-By: PHP/7.2.34  
Expires: Thu, 09 Sep 2021 13:17:17 GMT  
Cache-Control: max-age=3600  
X-Redirect-By: redirection  
Location: https://dunwoody.edu/  
MS-Author-Via: DAV  
X-Powered-By: PleskLin  


## 400 Bad Request  
nc -C twin-cities.umn.edu 443  
HEAD / HTTP/1.1  
Host: twin-cities.umn.edu  

HTTP/1.1 400 Bad Request  
Server: nginx  
Date: Thu, 09 Sep 2021 12:20:58 GMT  
Content-Type: text/html  
Content-Length: 248  
Connection: close  


## 404 Not Found  
nc -C api.scheduleengine.net 80  
GET / HTTP/1.1  
Host: api.scheduleengine.net  

HTTP/1.1 404 Not Found  
Date: Thu, 09 Sep 2021 12:24:36 GMT  
Content-Type: application/json; charset=utf-8  
Transfer-Encoding: chunked  
Connection: keep-alive  
Server: kong/0.13.0  

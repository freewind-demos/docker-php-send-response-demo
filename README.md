Docker Php Send Response Demo
=============================

php发送response header/code和content

```
npm run up
```

```
$ http http://localhost:10080
```

```
HTTP/1.1 201 Created
Connection: Keep-Alive
Content-Length: 26
Content-Type: text/html; charset=UTF-8
Date: Wed, 29 Jan 2020 11:44:30 GMT
Keep-Alive: timeout=5, max=100
My-Custom-Header: 111
Server: Apache/2.4.38 (Debian)
X-Powered-By: PHP/7.4.2

<h1>Response content</h1>
```
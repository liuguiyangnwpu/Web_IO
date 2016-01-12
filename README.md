# 网站压力测试
## 使用说明
```
fighter@ubuntu:~/Documents/Web_IO$ ./pressure -?
usage: ./pressure --mode=string [options] ... 
options:
  -h, --host        host name (string [=www.baidu.com])
  -p, --port        port number (int [=80])
  -d, --delay       each connect delay time ms (int [=50])
  -n, --n_users     user number (int [=50])
  -v, --n_visit     each user visit number (int [=100])
  -u, --url         url address (string [=http://www.baidu.com])
  -s, --savefile    download file save path (string [=temp.html])
  -t, --type        data send type (string [=GET])
  -m, --mode        pressure tesing mode (string)
  -?, --help        print this message
```

## 链接测试
```
fighter@ubuntu:~/Documents/Web_IO$ ./pressure -m connect -h www.baidu.com
official hostname: www.a.shifen.com
alias: www.baidu.com
 address: 61.135.169.125
 address: 61.135.169.121
Thread 1
	Max visit time: 4309 ms
	Min visit time: 118 ms
	Avg visit time: 1447.45 ms
Thread 2
	Max visit time: 4272 ms
	Min visit time: 294 ms
	Avg visit time: 1587.49 ms
Thread 3
	Max visit time: 4898 ms
	Min visit time: 76 ms
	Avg visit time: 1495.71 ms
Thread 4
	Max visit time: 137851 ms
	Min visit time: 130 ms
	Avg visit time: 2728.23 ms
Thread 5
	Max visit time: 2866 ms
	Min visit time: 233 ms
	Avg visit time: 1338.67 ms
Thread 6
	Max visit time: 4130 ms
	Min visit time: 267 ms
	Avg visit time: 1673.04 ms
Thread 7
	Max visit time: 3782 ms
	Min visit time: 85 ms
	Avg visit time: 1459.43 ms
Thread 8
	Max visit time: 140450 ms
	Min visit time: 95 ms
	Avg visit time: 2925.19 ms
Thread 9
	Max visit time: 3997 ms
	Min visit time: 119 ms
	Avg visit time: 1463.26 ms
Thread 10
	Max visit time: 3576 ms
	Min visit time: 377 ms
	Avg visit time: 1567.47 ms
Thread 11
	Max visit time: 3619 ms
	Min visit time: 63 ms
	Avg visit time: 1379.96 ms
Thread 12
	Max visit time: 139078 ms
	Min visit time: 67 ms
	Avg visit time: 2582.24 ms
Thread 13
	Max visit time: 3437 ms
	Min visit time: 234 ms
	Avg visit time: 1433.83 ms
Thread 14
	Max visit time: 3827 ms
	Min visit time: 457 ms
	Avg visit time: 1610.68 ms
Thread 15
	Max visit time: 122969 ms
	Min visit time: 260 ms
	Avg visit time: 2333.89 ms
Thread 16
	Max visit time: 3082 ms
	Min visit time: 368 ms
	Avg visit time: 1600.9 ms
Thread 17
	Max visit time: 3769 ms
	Min visit time: 126 ms
	Avg visit time: 1476.29 ms
Thread 18
	Max visit time: 3847 ms
	Min visit time: 187 ms
	Avg visit time: 1537.9 ms
Thread 19
	Max visit time: 36192 ms
	Min visit time: 92 ms
	Avg visit time: 1771.16 ms
Thread 20
	Max visit time: 135393 ms
	Min visit time: 223 ms
	Avg visit time: 2610.95 ms
Thread 21
	Max visit time: 4076 ms
	Min visit time: 495 ms
	Avg visit time: 1698.1 ms
Thread 22
	Max visit time: 4166 ms
	Min visit time: 58 ms
	Avg visit time: 1457.08 ms
Thread 23
	Max visit time: 4271 ms
	Min visit time: 149 ms
	Avg visit time: 1532.88 ms
Thread 24
	Max visit time: 3364 ms
	Min visit time: 203 ms
	Avg visit time: 1461.83 ms
Thread 25
	Max visit time: 3816 ms
	Min visit time: 193 ms
	Avg visit time: 1317.99 ms
Thread 26
	Max visit time: 4482 ms
	Min visit time: 52 ms
	Avg visit time: 1628.23 ms
Thread 27
	Max visit time: 3117 ms
	Min visit time: 254 ms
	Avg visit time: 1469.88 ms
Thread 28
	Max visit time: 4085 ms
	Min visit time: 80 ms
	Avg visit time: 1501.59 ms
Thread 29
	Max visit time: 4019 ms
	Min visit time: 131 ms
	Avg visit time: 1639.73 ms
Thread 30
	Max visit time: 3982 ms
	Min visit time: 140 ms
	Avg visit time: 1751.65 ms
Thread 31
	Max visit time: 3025 ms
	Min visit time: 108 ms
	Avg visit time: 1340.01 ms
Thread 32
	Max visit time: 3961 ms
	Min visit time: 257 ms
	Avg visit time: 1749.5 ms
Thread 33
	Max visit time: 3760 ms
	Min visit time: 257 ms
	Avg visit time: 1670.22 ms
Thread 34
	Max visit time: 3871 ms
	Min visit time: 108 ms
	Avg visit time: 1550.47 ms
Thread 35
	Max visit time: 4058 ms
	Min visit time: 335 ms
	Avg visit time: 1649.18 ms
Thread 36
	Max visit time: 4014 ms
	Min visit time: 399 ms
	Avg visit time: 1752.67 ms
Thread 37
	Max visit time: 3633 ms
	Min visit time: 94 ms
	Avg visit time: 1556.86 ms
Thread 38
	Max visit time: 4018 ms
	Min visit time: 206 ms
	Avg visit time: 1454.38 ms
Thread 39
	Max visit time: 61296 ms
	Min visit time: 62 ms
	Avg visit time: 2030.42 ms
Thread 40
	Max visit time: 4292 ms
	Min visit time: 256 ms
	Avg visit time: 1574.53 ms
Thread 41
	Max visit time: 4811 ms
	Min visit time: 320 ms
	Avg visit time: 1758.21 ms
Thread 42
	Max visit time: 3126 ms
	Min visit time: 86 ms
	Avg visit time: 1441.26 ms
Thread 43
	Max visit time: 2729 ms
	Min visit time: 99 ms
	Avg visit time: 1411.3 ms
Thread 44
	Max visit time: 3715 ms
	Min visit time: 305 ms
	Avg visit time: 1753.94 ms
Thread 45
	Max visit time: 4086 ms
	Min visit time: 376 ms
	Avg visit time: 1719.4 ms
Thread 46
	Max visit time: 4253 ms
	Min visit time: 95 ms
	Avg visit time: 1540.83 ms
Thread 47
	Max visit time: 4345 ms
	Min visit time: 84 ms
	Avg visit time: 1447.84 ms
Thread 48
	Max visit time: 5393 ms
	Min visit time: 32 ms
	Avg visit time: 1565.05 ms
Thread 49
	Max visit time: 3800 ms
	Min visit time: 584 ms
	Avg visit time: 1758.85 ms
Thread 50
	Max visit time: 4061 ms
	Min visit time: 246 ms
	Avg visit time: 1667.66 ms
```

## 网页下载
```
fighter@ubuntu:~/Documents/Web_IO$ ./pressure -m download -h www.baidu.com -u http://www.baidu.com
official hostname: www.a.shifen.com
alias: www.baidu.com
 address: 61.135.169.125
 address: 61.135.169.121
GET http://www.baidu.com HTTP/1.1
Host: 61.135.169.125:80
Connection: Close
User-Agent: Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Ubuntu Chromium/47.0.2526.73 Chrome/47.0.2526.73 Safari/537.36


	***********************Request Header************************
HTTP/1.1 200 OK
Date: Tue, 12 Jan 2016 14:00:04 GMT
Server: Apache
P3P: CP=" OTI DSP COR IVA OUR IND COM "
P3P: CP=" OTI DSP COR IVA OUR IND COM "
Set-Cookie: BAIDUID=B154ECBEAF75864C29C4A5E1739BE237:FG=1; expires=Wed, 11-Jan-17 14:00:04 GMT; max-age=31536000; path=/; domain=.baidu.com; version=1
Set-Cookie: BAIDUID=B154ECBEAF75864CAACC52FBB9DDEB0A:FG=1; expires=Wed, 11-Jan-17 14:00:04 GMT; max-age=31536000; path=/; domain=.baidu.com; version=1
Last-Modified: Thu, 12 Mar 2015 07:58:57 GMT
ETag: "2a3b-51112c17f9240"
Accept-Ranges: bytes
Content-Length: 10811
Cache-Control: max-age=1
Expires: Tue, 12 Jan 2016 14:00:05 GMT
Vary: Accept-Encoding,User-Agent
Connection: Close
Content-Type: text/html
```

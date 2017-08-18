# PHP 基本用法  
## 内置Web Server
**PHP 5.4.0** 起，LCI SAPI 提供了一个内置Web服务器。  
- 启动Web服务器  
`php -S localhost:8000`  
指定Web根目录(默认为当前目录)  
`php -S localhost:8000 -t workspace\php`  
指定路由脚本(默认为index)  
`php -S localhost:8000 -t dir route.php`

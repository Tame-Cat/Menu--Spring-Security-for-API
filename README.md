# Menu : Spring Security for API
### Phubordee romin 6210451390 sec200

* เชื่อมต่อกับMySQL database
    * username = root
    * password = abc123
    * MySQL port = 3307
> รัน MySQL ผ่าน Docker
```
$ docker run --name=mysql_menu -e MYSQL_ROOT_PASSWORD=abc123 -e MYSQL_DATABASE=menu -p 3307:3306 -d mysql
```
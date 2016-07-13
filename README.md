# MySQL Docker Image
build from [official image](https://github.com/docker-library/mysql)

## Environment Variables
### MYSQL_CHARSET
default: utf8

### MYSQL_COLLATION
default: utf8_general_ci

### MYSQL_INNODB_LARGE_PREFIX
default: nil

## Usage
```
docker run -e MYSQL_ROOT_PASSWORD=password -e MYSQL_CHARSET=utf8mb4 -e MYSQL_COLLATION=utf8mb4_general_ci -r MYSQL_INNODB_LARGE_PREFIX=1 -d heathrow/mysql:latest
```

[https://github.com/docker-library/mysql](https://github.com/docker-library/mysql)

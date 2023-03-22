# xman-dkcompose
docker-compose(php_nginx_mysql_redis_go)
修改挂载、端口映射之后可以直接跑起来。
注意事项：
conf.d/下的的vhost配置文件中的 {$host}:9000  host需为docker-compose中的php服务名字

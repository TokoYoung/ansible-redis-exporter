##### REDIS EXPORTER INSTALL ### 

If you dont have password on redis cluster delete the argument 
in redis_exporter.service "   -redis.password {{ redispasswd }} " 
and you should be good to go 

Redis exporter wont work if Redis nodes in the same cluster will have different password 

Redis exporter source :

https://github.com/oliver006/redis_exporter

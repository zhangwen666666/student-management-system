1. 启动nacos  startup.cmd -m standalone
2. 启动sentinel java -Dserver.port=9060 sentinel-dashboard-1.8.5.jar
3. 启动redis镜像 docker run --name myredis -v E:\docker\redis\redis.conf:/etc/redis/redis.conf -v E:\docker\redis\data:/data -dp 6379:6379 redis:7.0 redis-server /etc/redis/redis.conf
4. 启动前端项目 npm run dev
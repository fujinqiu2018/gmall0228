<<<<<<< HEAD
gmall-user      8080
gmall-user-web  8180

gmall-manager-service 8081
gmall-manager-web     8181

gmall-item-web  8182

gmall-list-service  8083    
gmall-list-web    8183

gmall-cart-service 8084
gmall-cart-web  8184

gmall-passport-web 8185

gmall-order-service 8086
gmall-order-web 8186

gmall-payment 8087

关闭防火墙：       
    systemctl stop firewalld.service
Nginx启动(保存上传图片)：        
    /usr/local/nginx/sbin/nginx
Tomacat启动：      sh /opt/apache-tomcat-7.0.75/bin/startup.sh
Dubbo 随着 Tomcat 的启动而启动 
Zookeeper启动：    /opt/zookeeper-3.4.9/bin/zkServer.sh start
Zookeeper状态：    /opt/zookeeper-3.4.9/bin/zkServer.sh status
                   /opt/zookeeper-3.4.9/bin/zkServer.sh stop        
Redis服务启动(缓存)：    
    /usr/local/bin/redis-server /usr/local/bin/redis.conf
Redis客户端启动：  /usr/local/bin/redis-cli
        或 /usr/local/bin/redis-cli -h 192.168.38.200 -p 6379
Redis退出客户端：  127.0.0.1:6379> quit
Redis服务退出：    /usr/local/bin/redis-cli shutdown
ElasticSearch启动(缓存，倒排索引搜索)：
    systemctl start elasticsearch.service
ElasticSearch开机启动：systemctl enable elasticsearch.se/usr/local/bin/redis-server /usr/local/bin/redis.confrvice
ElasticSearch图形界面kibana启动：
    /opt/kibana-5.6.4-linux-x86_64/bin/kibana
    使用浏览器访问 http://192.168.38.200:5601

=======
# gmall0228

# 2018.07.07 welcome to use
# jhsjajshkjahkadada
>>>>>>> 108b793c151bbfc1a95f41f1e3094e75fafb8781


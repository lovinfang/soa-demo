1、soa-demo 为自己定义的soa框架工程
2、lovin-soa-consumer-test  soa-demo工程的部分功能的测试工程
3、workspace-soa-1 为引入soa-demo jar包的服务端工程
4、workspace-soa-2 为引入soa-demo jar包的服务端工程
5、SSMDemo 为web版本的客户端测试工程 http://localhost:8081/SSMDemo/framework/index
6、采用redis作为注册中心
7、dn-jack-soa.zip 为动脑源码包
8、dubbo-provider-web.zip dubbo服务端代码实例
   dubbo-consumer-web1.zip dubbo客户端代码实例


redis启动和其他命令

cd F:\d\workSoftware\redis-2.4.5
F:\d\workSoftware\redis-2.4.5>redis-server.exe
F:\d\workSoftware\redis-2.4.5>redis-cli.exe

查看keys
redis 127.0.0.1:6379> keys *
删除key
redis 127.0.0.1:6379> del testService
查看key内容
redis 127.0.0.1:6379> lrange testService 0 -1

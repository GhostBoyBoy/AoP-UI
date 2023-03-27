# AoP-UI
## Build
1.To set host on your host, modify /js/main.js lines 1188 and 1251.  
2.npm install anywhere -g  
3.anywhere -p 7000  
4.pulsar broker config such as:  
### --- aop settings --- ###  
messagingProtocols=amqp  
protocolHandlerDirectory=./protocols  
amqpTenant=amqp  
amqpListeners=amqp://xxx:5671  
amqpProxyEnable=true  
amqpProxyPort=5672  
amqpAdminPort=15672  
amqpMsgIndexEnable=true  
amqpMultiBundleEnable=true  

You need to build with this PR：  
https://github.com/streamnative/aop/pull/851  

This pr implements the Rabbitmq management background API.  

![image](https://user-images.githubusercontent.com/38995810/226938238-10917b4b-bb94-4ef5-af57-0305ef2816b4.png)

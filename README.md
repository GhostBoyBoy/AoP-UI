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

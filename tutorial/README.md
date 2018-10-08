hawkBit 101 - Stack
===

This Docker stack contains a full-blown hawkBit setup: 

* hawkBit Update Server (Port: 8080)
* hawkBit Device Simulator (Port: 8083)
* MySQL Database 
* RabbitMQ 


## Device Simulator

**Start**

```
$ curl localhost:8083/start
```

**Reset**

```
$ curl localhost:8083/reset
```

for more, see [link](https://github.com/eclipse/hawkbit-examples/tree/master/hawkbit-device-simulator).
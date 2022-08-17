sentinel-dashboard-nacos
```
nacos.serverAddr=${NACOS_SERVER:192.168.0.100:8848}
nacos.namespace=${NACOS_NAMESPACE:dev}
nacos.group=${NACOS_GROUP:DEFAULT_GROUP}
nacos.username=${NACOS_USERNAME:nacos}
nacos.password=${NACOS_PASSWORD:nacos}
```
将当前项目添加到 https://github.com/alibaba/Sentinel 模块里，进行编译即可
使用时可通过 java -DNACOS_SERVER=x.x.x.x:8848 -DNACOS_NAMESPACE=dev -DNACOS_USERNAME=nacos -DNACOS_PASSWORD=nacos -jar sentinel-dashboard-nacos-1.8.5.jar
根据需要对-D等号后面的进行替换

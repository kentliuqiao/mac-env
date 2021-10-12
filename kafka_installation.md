安装java

```
brew install --cask homebrew/cask-versions/adoptopenjdk8
```

验证
```
java -version
```

安装kafka

```
brew install kafka
```

验证

```
To start kafka:
  brew services start kafka
Or, if you don't want/need a background service you can just run:
  /usr/local/opt/kafka/bin/kafka-server-start /usr/local/etc/kafka/server.properties
```

启动

以服务的方式启动
```
brew services start zookeeper
brew services start kafka
```

或者临时启动
```
/usr/local/bin/zkServer start
/usr/local/opt/kafka/bin/kafka-server-start /usr/local/etc/kafka/server.properties
```

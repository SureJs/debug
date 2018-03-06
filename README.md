# debug
## hive : ${HIVE_HOME}/bin/hive --debug <必要启动参数>
* export HIVE_CONF_DIR=${调整hive配置读取路径}
* export HIVE_CLASSPATH=${添加三方Jar到环境变量}
## spark-thrift : ${SPARK_HOME}/sbin/start-thriftserver.sh --driver-java-options "-agentlib:jdwp=transport=dt_socket,server=y,suspend=y,address=<远程DEBUG监听端口>" <必要启动参数>

# debug
* hive : ${HIVE_HOME}/bin/hive --debug <必要启动参数>
* spark-thrift : ${SPARK_HOME}/sbin/start-thriftserver.sh --driver-java-options "-agentlib:jdwp=transport=dt_socket,server=y,suspend=y,address=<远程DEBUG监听端口>" <必要启动参数>

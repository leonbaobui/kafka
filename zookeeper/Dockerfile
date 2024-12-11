# zookeeper/Dockerfile
FROM confluentinc/cp-zookeeper:7.3.2
ENV ZOOKEEPER_CLIENT_PORT=2181
ENV ZOOKEEPER_TICK_TIME=2000
ENV KAFKA_OPTS='-Dzookeeper.admin.enableServer=false'
EXPOSE 2181

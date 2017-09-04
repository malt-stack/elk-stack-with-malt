Example ELK stack using MALT stack
==================================

This is an example of setting up the ELK stack using the principles of the MALT stack, primarily Kafka.

For more information, see our blog post: http://www.maltstack.com/2017/09/setting-up-elk-stack-on-malt.html

To get started, download Docker and run:

docker-compose up
This will create an entire stack with 3 Zookeeper nodes, 3 Kafka nodes, Kibana, Elasticsearch, and a logstash publisher and consumer.

Once started, open Kibana at http://localhost:5601

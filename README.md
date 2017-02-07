# my-jelk-stack
This is attempt to visualize results of JMeter load tests via ELK stack.

Idea is to use Logstash to collect metrics from JMeter. Later this data is later passed to
Elasticsearch, and visualized using Kibana.

Current status:

07-02-2017:
- Docker containers for Elasticsearch(only 1 node. 2 nodes are crushing when adding kibana container) and Kibana
- Logstash config to fetch JMeter CSV output.

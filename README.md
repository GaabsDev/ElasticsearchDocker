# ELK (Elasticsearch + Logstash + Kibana) 7.6.2 Com Docker

<img src="https://images.contentstack.io/v3/assets/bltefdd0b53724fa2ce/blt79a924435d0d3db1/5e21df16e87f9111587363b2/illustration-solution-enterprise-search-rock-solid-555.png" alt="ELK" width="400" align="center" />

```
docker-compose up -d
```

* User `elastic` and password `123change...`
* Elasticsearch: http://localhost:9200
* Kibana: http://localhost:5601
* For logstash demo, see confs in `logstash/conf` dir
* CSV used to load data is in `logstash/csv` dir
* For elasticsearch configuration, see `elasticsearch.yml` in `elasticsearch/config` dir
* Search for test `http://localhost:9200/_search`

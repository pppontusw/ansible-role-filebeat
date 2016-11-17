Sets up filebeat to scan and push logs to logstash.

Ex.

```
filebeat_paths: ["{{path_to_log}}/*.log"]
logstash_hosts: ["{{logstash_host}}"]
```
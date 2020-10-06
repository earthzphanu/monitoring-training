# Monitoring Training
A demonstration of Monitoring services or applications using Prometheus, Alertmanager and Grafana stack

## Usage 
```
docker-compose up
```

## Access to services
- Grafana running at port 3000
- Prometheus running at port 9090

<!-- 
Graylog
```
echo -n '{"version": "1.1", "host": "example.org", "short_message": "A short message", "level": 5, "some_info": "userXX"}' | nc -w1 -u GRAYLOG_IP 122XX
``` -->
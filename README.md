# k6-demo

```sh

docker-compose up -d influxdb grafana

git clone https://github.com/grafana/k6 
cd k6/examples
k6 run --out influxdb=http://localhost:8086 stages.js

https://grafana.com/grafana/dashboards/2587-k6-load-testing-results/
```
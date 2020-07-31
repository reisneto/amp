# APM

## Configuration 

### Prometheus
- go to [prometheus.yml](https://github.com/reisneto/amp/blob/master/prometheus/config/prometheus.yml#L14)
- change this application name 
- change *targets* to your application ip
- `mkdir prometheus/data`

### Grafana
- `mkdir grafana/data`

## Starting containers

`docker-compose up -d`

## Opening Services on the browser
- Prometheus  
    `localhost:9090`

- Grafana  
    `localhost:3001`  
    login/password: admin

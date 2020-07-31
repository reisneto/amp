# amp

## Configuring Prometheus

- go to [prometheus.yml](https://github.com/reisneto/amp/blob/master/prometheus/config/prometheus.yml#L14)
- change this application name 
- change *targerts* to your application ip

## Starting containers

`docker-compose up -d`

## Opening Services on the browser
- Prometheus  
    `localhost:9090`

- Grafana  
    `localhost:3001`  
    login/password: admin

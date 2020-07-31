# amp

## Configure Prometheus

- go to [prometheus.yml](https://github.com/reisneto/amp/blob/master/prometheus/config/prometheus.yml#L14)
- alter this application name 
- alter *targerts* to your application ip

## Starting containers

`docker-compose up -d`

## Opening Services on the browser
- Prometheus  
    `localhost:9090`

- Grafana  
    `localhost:3001`  
    login/password: admin

# Prometheus-Grafana
Put both services online locally to connect an application to it.

## Configuration 

### Prometheus
- go to [prometheus.yml](https://github.com/reisneto/amp/blob/master/prometheus/config/prometheus.yml#L14)
- change this application name 
- change *targets* to your application ip
- `mkdir prometheus/data`
- sudo chown 777 prometheus/ (so docker user can access it)

### Grafana
- `mkdir grafana/data`
- sudo chown 777 grafana/ (so docker user can access it)

## Starting containers

`docker-compose up -d`

## Opening Services on the browser
- Prometheus  
    `localhost:9090`

- Grafana  
    `localhost:3001`  
    login/password: admin

## UID
on terminal type `id -u` and add it on docker-compose.yml
example `user: '1000'` [below prometheus line](https://github.com/reisneto/apm/blob/master/docker-compose.yml#L6) and [grafana's](https://github.com/reisneto/apm/blob/master/docker-compose.yml#L15)

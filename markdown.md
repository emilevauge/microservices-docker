name: inverse
layout: true
class: center, middle, inverse
---
# Microservices
with

![Docker](images/small_v-dark-trans.png)

Emile Vauge
---
layout: false
class: center, middle
# DevOps
![Zenika](images/logo-zenika.png)

.bottom[
<i class="fa fa-twitter fa-2x"></i> [@emilevauge](http://twitter.com/emilevauge)

<i class="fa fa-github fa-2x"></i> [emilevauge/traefik](https://github.com/emilevauge/traefik)
]

---
class: center, middle
## Microservices
![Microservices](images/microservices.jpg)

---
class: center, middle
.left-column[
### Microservices stack
]
.right-column[
![Spring cloud](images/spring-cloud.png)

![Netflix OSS](images/Netflix-OSS-Logo.png)
]

---
class: center, middle
.left-column[
### Microservices stack
### Containers
]
.right-column[
![Docker](images/small_v-dark-trans.png)
]

---
class: center, middle
.left-column[
### Microservices stack
### Containers
### Orchestration
]
.right-column[
![Mesos](images/mesos-logo.jpeg)
![Twitter](images/twitter.png)
![Apple](images/apple.png)
]

---
class: center, middle
.left-column[
### Microservices stack
### Containers
### Orchestration
### Logs
]
.right-column[
![Graylog](images/graylog.png)
]

---
class: center, middle
.left-column[
### Microservices stack
### Containers
### Orchestration
### Logs
### Reverse proxy
]
.right-column[
![traefik](images/traefik.logo.white.svg)

![traefik](images/traefik.architecture.svg)
]

---
class: center, middle,  inverse
# Immutable infrastructure

---
class: center, middle
## Reverse proxy
![Consul](images/reverse-proxy.png)

---
class: center, middle
## Traefik
![Consul](images/reverse-proxy2.png)


---
.left-column[
  ## Features
]
.right-column[
<i class="fa fa-check-square"></i> Single binary

<i class="fa fa-check-square"></i> Rest API, metrics

<i class="fa fa-check-square"></i> Multiple backends supported: Docker, Mesos/Marathon, Consul, Etcd, and more to come

<i class="fa fa-check-square"></i> Watchers for backends

<i class="fa fa-check-square"></i> Hot-reloading of configuration. No need to restart the process

<i class="fa fa-check-square"></i> Graceful shutdown http connections during hot-reloads

<i class="fa fa-check-square"></i> Circuit breakers on backends

<i class="fa fa-check-square"></i> Weighted Round Robin, Dynamic Round Robin load-balancers

<i class="fa fa-check-square"></i> Tiny docker image included

<i class="fa fa-check-square"></i> WebUI
]
---

.left-column[
  ## Plumbing
]
.right-column[
<i class="fa fa-check-square"></i> Oxy: an awsome proxy library made by Mailgun guys

<i class="fa fa-check-square"></i> Gorilla mux: famous request router

<i class="fa fa-check-square"></i> Negroni: web middlewares made simple

<i class="fa fa-check-square"></i> Manners: graceful shutdown of http.Handler servers
]

---
class: center, middle
<iframe src="https://ghbtns.com/github-btn.html?user=emilevauge&repo=traefik&type=star&count=true&size=large" frameborder="0" scrolling="0" width="160px" height="30px"></iframe>

---
class: center, middle, inverse
# Demo

---
class: center, middle, inverse

![traefik](images/traefik.site.svg)

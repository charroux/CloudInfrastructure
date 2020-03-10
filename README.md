# CloudInfrastructure

## Monolithic architecture

The Monolithic architecture contains a single-tiered software application in which different components combined into a single program from a single platform.

https://github.com/charroux/WebServiceExample

Drawbacks:
- A change made to a small part of the application => the entire monolith to be rebuilt and deployed. 
- Scaling requires scaling of the entire application rather than parts of it that require greater resource.

## Microservice architecture

Microservices are small, independent processes that communicate with each other to form complex applications which utilize language-agnostic APIs. 

https://github.com/charroux/microservices

https://www.qwiklabs.com/focuses/8498?catalog_rank=%7B%22rank%22%3A4%2C%22num_filters%22%3A0%2C%22has_search%22%3Atrue%7D&parent=catalog&search_id=4807948

## Docker

Since a microservice application is language agnostic, many heterogeneous technology can be used together. But how to deploy heterogeneous applications? A first step is to embed each service inside a Docker container. Hence from an Ops point of view (the Ops part of the DevOps approach) there all only Docker containers.

https://github.com/charroux/docker

https://www.qwiklabs.com/focuses/1029?catalog_rank=%7B%22rank%22%3A3%2C%22num_filters%22%3A0%2C%22has_search%22%3Atrue%7D&parent=catalog&search_id=4807987

## Kubernetes

Given a set of Docker containers, how to manage those containers as a whole. Kubernetes allows to deploy a set of containers in a clusters of nodes (composed of virtual or real machines).

https://github.com/charroux/kubernetes
https://github.com/charroux/kubernetes-volume
https://github.com/charroux/CodingWithKubernetes

https://www.qwiklabs.com/quests/29?catalog_rank=%7B%22rank%22%3A1%2C%22num_filters%22%3A0%2C%22has_search%22%3Atrue%7D&search_id=4807987

https://www.qwiklabs.com/quests/45?catalog_rank=%7B%22rank%22%3A1%2C%22num_filters%22%3A0%2C%22has_search%22%3Atrue%7D&search_id=4807989

## Service Mesh VS Microservices communication patterns

Service Mesh like LinkerD analyse a Kubernetes cluster and generate proxies making communication between services easier. Since a service mesh uses proxies the services themselve remain unchanged. Nevertheless for fine tunning the programmatic approach given by the microservice architecture is sometimes more suitable.

https://github.com/charroux/kubernetes

https://www.qwiklabs.com/video/2779

## Prometheus

Monitoring a services is crucial as soon as many services are used.

https://github.com/charroux/prometheus

https://www.qwiklabs.com/focuses/8463?catalog_rank=%7B%22rank%22%3A1%2C%22num_filters%22%3A0%2C%22has_search%22%3Atrue%7D&parent=catalog&search_id=4807996

## Terraform

The last peace of the puzzle: portable and dynamic machine provisionning in a cloud infrastructure (Infrasctructure As Code) with Terraform.

https://github.com/charroux/terraform

https://www.qwiklabs.com/focuses/1208?catalog_rank=%7B%22rank%22%3A3%2C%22num_filters%22%3A0%2C%22has_search%22%3Atrue%7D&parent=catalog&search_id=4808000

https://www.qwiklabs.com/quests/44?catalog_rank=%7B%22rank%22%3A1%2C%22num_filters%22%3A0%2C%22has_search%22%3Atrue%7D&search_id=4808000

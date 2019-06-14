# Series: Learn to build a cloud-native microservices app in Java step-by-step.

## Overview

In this series, IBM developer advocates [Niklas Heidloff](http://heidloff.net/) and [Harald Uebele](https://haralduebele.blog/) simplify the sometimes intimidating process of building a full-featured microservices application running in Kubernetes. Many aspects of modern application development are explained in easy-to-understand tutorials with hands-on examples.

#### Project overview: [Description and Design Principles](http://heidloff.net/article/example-java-app-cloud-kubernetes)
#### Video: [World Congress Berlin Talk](https://youtu.be/ZIizxsmkWJo?t=6714)
#### [Hands-on workshop](https://github.com/nheidloff/cloud-native-starter/tree/master/workshop)



## Objectives

Learn how to put together a complete, secure back-end stack to run a web site that's fault-tolerant and scalable using modern cloud-native technologies like Open Liberty, a high performance open source Java application serve, MicroProfile, a set of Java standards aimed at microservice development, and Kubernetes a popular container orchestration platform. Some tutorials rely on services in IBM Cloud, but most can be completed with services available in the Free tier.

## Units


#####  Tutorial: [Setup of a Local Kubernetes and Istio Dev Environment](http://heidloff.net/article/setup-local-development-kubernetes-istio)
> Provision the necessary infrastructure and deploy the sample app to a local or public cloud.

#####  Tutorial: [Debugging Microservices running in Kubernetes](http://heidloff.net/article/debugging-microservices-kubernetes)

> Use the `Telepresense` tool to debug Java microservices locally.

#####  Tutorial: [Dockerizing Java MicroProfile Applications](http://heidloff.net/article/dockerizing-container-java-microprofile)

> Learn how to create a Docker image from your Open Liberty application so it's ready for deployment to Kubernetes.

#####  Tutorial: [Developing resilient Microservices with Istio and MicroProfile](http://heidloff.net/article/resiliency-microservice-microprofile-java-istio)

> Learn how to use MicroProfile Fallback annotations to allow your Java service to gracefully handle network errors.

#####  Tutorial: [Managing Microservices Traffic with Istio](https://haralduebele.blog/2019/03/11/managing-microservices-traffic-with-istio/)

> Use Istio's declarative traffic shaping and routing features to safely experiment with A/B deployment scenarios in production.

#####  Tutorial: [Web Application to demo Traffic Management with Istio](http://heidloff.net/article/sample-app-manage-microservices-traffic-istio)

> Continuation of the previous tutorial on Istio traffic management with Kiali visualizations.

#####  Tutorial: [Implementing and documenting REST APIs with JavaEE](http://heidloff.net/article/rest-apis-microprofile-javaee-jaxrs)

> Learn how to write REST APIs with JAX-RS and document them with the OpenAPI implementation built-in to Open Liberty.

#####  Tutorial: [Invoking REST APIs from Java Microservices](http://heidloff.net/invoke-rest-apis-java-microprofile-microservice)

> Learn how to use the MicroProfile REST client to invoke REST endpoints from Java.

#####  Tutorial: [Prometheus Metrics for MicroProfile Microservices in Istio](http://heidloff.net/article/prometheus-metrics-microprofile-microservices-istio/)

> Learn how to combine application specific metrics with Istio's built-in telemetry features to monitor traffic inside your cluster.

#####  Tutorial: [Moving from Minikube to IBM Cloud Kubernetes Service](https://haralduebele.blog/2019/04/04/moving-from-minikube-to-ibm-cloud-kubernetes-service/)

> Learn how to provision a free Kubernetes cluster on IBM Cloud and deploy your containerized microservices.

#####  Tutorial: [Distributed logging with LogDNA and Monitoring with Sysdig](https://haralduebele.blog/2019/04/08/whats-going-on-in-my-cluster/)

> Learn how to connect a LogDNA service with your Kubernetes cluster for simple centralized log management.

#####  Tutorial: [Implementing Health Checks with MicroProfile and Istio](http://heidloff.net/article/implementing-health-checks-microprofile-istio)

> Learn how to use MicroProfile health checking with Kubernetes automatic liveness and readiness probes.

#####  Tutorial: [Configuring Microservices with MicroProfile and Kubernetes](http://heidloff.net/article/configuring-java-microservices-microprofile-kubernetes/)

> Learn how to inject configuration parameters into Java microservices at run-time using MicroProfile and Kubernetes.

#####  Tutorial: [Authenticating Web Users with OpenID and JWT](http://heidloff.net/article/authenticating-web-users-openid-connect-jwt/)

> Learn how to integrate an OpenID client library with IBM App ID to provide a simple user authentication mechanism.

#####  Tutorial: [Authorization in Cloud-Native Applications via OpenID and Istio](http://heidloff.net/article/authentication-authorization-openid-connect-istio)


> Learn how to use Istio JWT based policies along with OpenID to provide secure access to authorized users.


#####  Tutorial: [Authorization in Microservices with MicroProfile](http://heidloff.net/article/authorization-microservices-java-microprofile/)

> As in the previous tutorial, we are using AppID and JWTs to only allow authorized users to access the Web app, but this tutorial shows how to use MicroProfile (not Istio) to secure access.

#####  Tutorial: [Persistence for Java Microservices in Kubernetes via JPA](http://heidloff.net/article/persistence-java-microservices-kubernetes-jpa/)

> Learn how to use Open Liberty and JPA, an ORM framework, to persist objects to a DB2 database in IBM Cloud.









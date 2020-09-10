# Awesome Envoy

List of resources related to [Envoy proxy](https://www.envoyproxy.io/)

## Success stories

* [How we migrated Dropbox from Nginx to Envoy](https://dropbox.tech/infrastructure/how-we-migrated-dropbox-from-nginx-to-envoy);

## Documentation

* [Official Docs](https://www.envoyproxy.io/docs/envoy/latest/);
* [GetEnvoy](https://www.getenvoy.io/);
* [envoyproxy/learnenvoy](https://github.com/envoyproxy/learnenvoy) - LearnEnvoy is a community content site that helps
organizations get the most out of the Envoy proxy (archive of site learnenvoy.io);

# xDS

aka [Universal Dataplane API](https://blog.envoyproxy.io/the-universal-data-plane-api-d15cec7a).

* [Golang xDS as a part of GRPC](https://github.com/grpc/grpc-go/tree/master/examples/features/xds);
* [miekg/xds](https://github.com/miekg/xds) - command line interface for Envoy xDS endpoint;
* [salrashid123/envoy_control](https://github.com/salrashid123/envoy_control) - Sample Envoy control plane 'hello world';
* [smallstep/step-sds](https://github.com/smallstep/step-sds) - Secret discovery service (SDS): simplifying certificate management for relying parties (such as Envoy);
* [envoyproxy/xds-relay](https://github.com/envoyproxy/xds-relay) - Caching, aggregation, and relaying for xDS compliant clients and origin servers;
* [envoyproxy/go-control-plane](https://github.com/envoyproxy/go-control-plane) - Go implementation of data-plane-api;
* [envoyproxy/ratelimit](https://github.com/envoyproxy/ratelimit) - Go/gRPC service designed to enable generic rate limit scenarios from different types of applications;
* [rosenhouse/envoy-secret-discovery-service-example](https://github.com/rosenhouse/envoy-secret-discovery-service-example) - example of static listener using the Secret Discovery Service (SDS);
* [mgfeller/xds-envoy](https://github.com/mgfeller/xds-envoy) - This repository illustrates the use of dynamic routing configuration (RDS) of the Envoy proxy;
* [kelseyhightower/kubernetes-envoy-sds](https://github.com/kelseyhightower/kubernetes-envoy-sds) - Kubernetes Envoy Service Discovery Service;

## Benchmarks

* [Benchmarking 5 Popular Load Balancers: Nginx, HAProxy, Envoy, Traefik, and ALB](https://www.loggly.com/blog/benchmarking-5-popular-load-balancers-nginx-haproxy-envoy-traefik-and-alb/);
* [Benchmarking Envoy Proxy, HAProxy, and NGINX Performance on Kubernetes](https://www.getambassador.io/resources/envoyproxy-performance-on-k8s/);

## Kubernetes Ingress

* [Ambassador](https://www.getambassador.io/);
* [Gloo](https://www.solo.io/products/gloo/);
* [Contour](https://projectcontour.io/);

## Kubernetes CNI

* [cilium](https://cilium.io/) - eBPF-based Networking, Security, and Observability;

## Service Mesh

* [Istio](https://istio.io/);
* [AWS App Mesh](https://docs.aws.amazon.com/app-mesh/latest/userguide/envoy.html);

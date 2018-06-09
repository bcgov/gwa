# GWA
Gateway Administration

[Current Status](https://github.com/BCDevOps/openshift-wiki/wiki/API-Management-Service-(Kong-Service-Mesh))


## Special files in this repository

Requirement: Kubernetes v1.9+ / OpenShift3.7+ supported client such as ```oc``` or ```kubectl```, minikue or minishift optional
Apart from the regular documentation files, this repository contains:

```

k8s/          - OpenShift/Kubernetes cluster production ready deployment files
├── Cassandra-StatefulSet.yaml            - Deployment of Cassandra as kubernetes statefulset ephemeral
├── Cassandra-persistent-StatefulSet.yaml - Deployment of Cassandra as kubernetes statefulset with persistent volume
├── redis-StatefulSet.yaml                - Deployment of redis as kubernetes statefulset with persistent volume
├── redis-persistent-StatefulSet.yaml     - Deployment of redis as kubernetes statefulset with persistent volume
├── kong-k8s-noplugins.yaml               - Deployment of standard kong as kubernetes replicaSet
└── kong-custom-ReplicaSet.yaml           - Deployment of custom plugin with kong as kubernetes replicaSet
```

## Main
This project contains following components
* [Kong - cloud-native, fast, scalable, and distributed Microservice Abstraction Layer (AKA an API Gateway, API Middleware or in some cases Service Mesh)](https://github.com/kong/kong) 
* [GWA-UI](https://github.com/bcgov/gwa-ui)
* [GWA-KONG-ENDPOINT](https://github.com/bcgov/gwa-kong-endpoint)

## Optional features
* [GWA-IP-Anonymity](https://github.com/bcgov/gwa-ip-anonymity)

## Roadmap
* [Development Status, Bugs Reports, New Feature Requests](https://github.com/bcgov/gwa#boards?repos=78794616,135350893,135510604,135498841) on Github ([ZenHub](https://chrome.google.com/webstore/detail/zenhub-for-github/ogcgkffhplmphkaahpmffcafajaocjbd) extension required for KANBAN) 

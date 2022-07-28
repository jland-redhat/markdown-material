# Learning Path Documentation

You can use this example if you want to get really fancy and take advantage of [material ui](https://squidfunk.github.io/mkdocs-material/) (the tool tip below plus extra stuff). And (meirmaid)[https://mermaid-js.github.io/mermaid/#/flowchart?id=graph] (the graph)

!!! tip
    Nodes are clickable links leading to more learning!!!

``` mermaid
graph TD;
  A[DO080 Containers, Kubernetes and Red Hat Openshift Technical Overview] --> C[DO101 Introduction to OpenShift Applications];
  B[DO092 Developing Cloud-Native Applications with Microservices Architectures] --> C;
  C --> D[DO328 Building Resilient Microservices with Istio and Red Hat OpenShift Service Mesh];
  C --> E[DO378 Red Hat Cloud-native Microservices Development with Quarkus];
  D --> F>Red Hat Certified Specialist in Building Resilient Microservices]
  E --> G>Red Hat Certified Cloud-native Developer]

  click A "https://www.redhat.com/en/services/training/do080-deploying-containerized-applications-technical-overview" "Overview for deploying containerized applications"
  click B "https://www.redhat.com/en/services/training/do092-developing-cloud-native-applications-microservices-architectures"
  click C "https://www.redhat.com/en/services/training/do101-introduction-openshift-applications" "In Introduction to openshift applications"
  click D "https://rol.redhat.com/rol/app/courses/do328vc-2.0"
  click E "https://rol.redhat.com/rol/app/courses/do378vc-1.11"
  click F "https://rol.redhat.com/rol/app/exam/ex328-2.0"
  click G "https://rol.redhat.com/rol/app/exam/ex378-1.7"

  style A fill:LightGray
  style B fill:LightGray
  style C fill:#C00000,color:white
  style D fill:#C00000,color:white
  style E fill:#C00000,color:white
  style F fill:#57a7b5
  style G fill:#57a7b5
```

!!! info
    Colors can be found [here](https://www.w3schools.com/colors/colors_shades.asp)


![Graph Key](assets/key.png)
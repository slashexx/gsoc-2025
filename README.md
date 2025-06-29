# Google Summer of Code 2025

**Project page:** [Completion of DaemonSet mode for the Prometheus Agent](https://summerofcode.withgoogle.com/programs/2025/projects/hZAZORpk)  
**Organisation:** [Prometheus Operator](https://prometheus-operator.dev/)  
**Mentor(s):** [Jayapriya Pai](https://github.com/slashpai), [M Viswanath Sai](https://github.com/mviswanathsai)  
**Proposal:** [Dhruv Puri - Prometheus Operator (GSoC 2025)](https://github.com/slashexx/gsoc-2025/blob/cf5080cffbe2e0ffa7046d4a6d2ab0edb0054129/PrometheusAgent-DaemonSet.pdf)

## About the Project

The project aims to bring the **Prometheus Agent's DaemonSet mode** in *Prometheus Operator* to full production readiness. This involves addressing missing functionalities, improving configuration validation, enhancing reliability, and providing comprehensive documentation. The ultimate goal is to offer a scalable, efficient, and fully supported way to run Prometheus Agent across Kubernetes nodes. This is achieved by integrating remaining features like *using CEL for CRD validation* to provide immediate feedback along with adding *runtime checks* as a fallback for older Kubernetes versions. Furthermore, Investigating and potentially implementing *EndpointSlice* for scalability and extending integration tests to multi-node Kind clusters. Finally, adding detailed documentation and example manifests.
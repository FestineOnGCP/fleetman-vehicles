# Fleetman-vehicles Project

This was a micro-service based Fleetman-vehicles project. They were four differnt microservice: frontend, queue, simulator, and generator. 

## Instructions on running the manifest

Create a kubernetes cluster and use the command "kubectl apply -f <manifest-name>" to create a deployment for each of the manifest.
Each manifest has both the deployment and service declaration for each microservice. You can also configure ELK for logging; Prometheus and Grafana
for monitoring and data monitored data visualization; and Istio service mesh for service visualization.

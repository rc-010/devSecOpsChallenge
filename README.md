# devSecOpsChallenge

Docker
  push the image to registery --> doc010/hello:latest

Kubernetes
  Created the cluster using minikube
    Then, created a new namespace called staging as namespace.yaml


Single Pod
  Create a new pod called hello in this staging namespace and used that hello image (doc010/hello:latest)

Multi-node

  for this task I have created the demonset which provides the option to running that p2.yaml pod of every node


Multi-container Pod

  deployment yaml file is --> p3.yaml

    Where I have used 2 Docker Images:
      --> doc010/hello:latest 
      --> nginx 

Monitoring 

 I have used helm charts:

      -> prometheus-community    https://prometheus-community.github.io/helm-charts port-forward to port:9090
     -> grafana                 https://grafana.github.io/helm-charts    port-forward to port:3000

     Partially done...

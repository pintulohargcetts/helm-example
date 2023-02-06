# helm-example
 helm example sample with custom image


 - How to use 
   
   - brew install helm 
   - helm template helm-example (from parent directory of helm-example)
   - helm install release-name project-name (helm template ucp-helm-example helm-example)
   - helm list -a 
   - you can do upgrade using helm upgrade and by updating the version: 0.1.0 to say 0.1.1 in Chart.yaml
   -  To access  
      -  kubectl port-forward svc/myrelease-ucp-example 3600:8080 -n default
      -  localhost:3600 in brower




# app-config-k8s

# Create configmap:
`kubectl create configmap fortune-service-k8s-kubernetes --from-file=fortune-service-k8s-kubernetes.yml`

# Get configmap:
`kubectl get configmap fortune-service-k8s-kubernetes -o yaml`
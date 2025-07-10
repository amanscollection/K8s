# K8s
A sample K8s project

# kubectl commands
kubectl apply -f https://k8s.io/examples/application/deployment.yaml

The output is similar to this:

deployment.apps/nginx-deployment created

# kubectl get
kubectl get pods -l environment=production,tier=frontend
kubectl get pods -l 'environment in (production),tier in (frontend)'

# kubectl label
kubectl label pods -l app=nginx tier=fe
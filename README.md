## AIO Helm Chart

Das ist a helm chart for alles-in-one applikation deployment on k8s using helm

Currently supported resources:
- `Deployment`
- `StatefulSet`
- `Service`
- `ConfigMap`
- `Secrets`
- `Ingress`
- `PersistentVolumeClaims`

While the chart is supposed to be relatively generik, it is probably more biased towards web applications and might need some edits to fit in to certain usecases, specifically those surrounding stateful applications


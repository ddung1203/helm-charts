# helm-charts
Deploying a web application on a Kubernetes cluster

## Usage

### repo add

```bash
helm repo add helm-charts https://ddung1203.github.io/helm-charts/
```

### helm chart install

```bash
helm install web helm-charts/nginx
```

### helm pull

```bash
helm pull helm-charts/nginx
```

### validation

```bash
helm list

NAME    NAMESPACE       REVISION        UPDATED                                 STATUS          CHART           APP VERSION
web     default         1               2024-06-19 09:25:52.074817 +0900 KST    deployed        nginx-0.1.0     1.16.0 
```
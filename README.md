# SD2411 Helm Chart Repository

## Get started

Add this repository to Helm.

-  `helm repo add myhelmrepo https://sieunhantanbao.github.io/sd2411-helm-charts/`

List the charts in the repo

-  `helm search repo myhelmrepo`

Install the helm charts

- Install database: `helm install -f mydatabase-values.yaml postgresdb myhelmrepo/postgresdb` ([Sample database values.yaml](https://github.com/sieunhantanbao/sd2411-helm-charts/blob/main/charts/postgresdb/values.yaml))

- Install backend: `helm install -f mybackend-values.yaml backend myhelmrepo/backend` ([Sample backend values.yaml](https://github.com/sieunhantanbao/sd2411-helm-charts/blob/main/charts/backend/values.yaml))

- Install frontend: `helm install -f myfrontend-values.yaml frontend myhelmrepo/frontend` ([Sample frontend values.yaml](https://github.com/sieunhantanbao/sd2411-helm-charts/blob/main/charts/frontend/values.yaml))

## Repositories
| Chart | Link to chart | Version |Notes|
|--|--|--|--|
|frontend|[myhelmrepo/frontend](https://github.com/sieunhantanbao/sd2411-helm-charts/tree/main/charts/frontend) |5.0.0 |No ingress controller|
|frontend|[myhelmrepo/frontend](https://github.com/sieunhantanbao/sd2411-helm-charts/tree/main/charts/frontend) |0.8.0 |With ingress controller|
|backend |[myhelmrepo/backend](https://github.com/sieunhantanbao/sd2411-helm-charts/tree/main/charts/backend) |0.3.0 ||
|postgresdb |[myhelmrepo/postgresdb](https://github.com/sieunhantanbao/sd2411-helm-charts/tree/main/charts/postgresdb)|0.2.5||
# SD2411 Helm Chart Repository

## Get started

Add this repository to Helm.

-  `helm repo add myhelmrepo https://sieunhantanbao.github.io/sd2411-helm-charts/`

List the charts in the repo

-  `helm search repo myhelmrepo`

Install the helm charts

- Install database: `helm install -f mydatabase-values.yaml mongo myhelmrepo/mongo` ([Sample database values.yaml](https://github.com/sieunhantanbao/sd2411-helm-charts/blob/main/charts/mongo/values.yaml))

- Install backend: `helm install -f mybackend-values.yaml backend myhelmrepo/backend` ([Sample backend values.yaml](https://github.com/sieunhantanbao/sd2411-helm-charts/blob/main/charts/backend/values.yaml))

- Install frontend: `helm install -f myfrontend-values.yaml frontend myhelmrepo/frontend` ([Sample frontend values.yaml](https://github.com/sieunhantanbao/sd2411-helm-charts/blob/main/charts/frontend/values.yaml))

## Repositories
| Chart | Link to chart | Version |Notes|
|--|--|--|--|
|frontend|[myhelmrepo/frontend](https://github.com/sieunhantanbao/sd2411-helm-charts/tree/main/frontend-1.0.0.tgz) |1.0.0 ||
|frontend|[myhelmrepo/frontend](https://github.com/sieunhantanbao/sd2411-helm-charts/tree/main/charts/frontend) |2.0.0 |Argo Rollout support|
|backend |[myhelmrepo/backend](https://github.com/sieunhantanbao/sd2411-helm-charts/tree/main/backend-1.0.0.tgz) |1.0.0 ||
|backend |[myhelmrepo/backend](https://github.com/sieunhantanbao/sd2411-helm-charts/tree/main/charts/backend) |2.0.0 |Argo Rollout support|
|mongo |[myhelmrepo/mongo](https://github.com/sieunhantanbao/sd2411-helm-charts/tree/main/charts/mongo)|1.0.0||
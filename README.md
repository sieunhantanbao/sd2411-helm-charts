# SD2411 Helm Chart Repository

## Get started

Add this repository to Helm.

-  `helm repo add myhelmrepo https://sieunhantanbao.github.io/sd2411-helm-charts/`

List the charts in the repo

-  `helm search repo myhelmrepo`

Install the helm charts

- Install database: `helm install frontend myhelmrepo/postgresdb`

- Install backend: `helm install frontend myhelmrepo/backend`

- Install frontend: `helm install frontend myhelmrepo/frontend`

## Repositories
| Chart | Link to chart | Version |Notes|
|--|--|--|--|
|frontend|[myhelmrepo/frontend](https://github.com/sieunhantanbao/sd2411-helm-charts/tree/main/charts/frontend) |5.0.0 |No ingress controller|
|frontend|[myhelmrepo/frontend](https://github.com/sieunhantanbao/sd2411-helm-charts/tree/main/charts/frontend) |0.8.0 |With ingress controller|
|backend |[myhelmrepo/backend](https://github.com/sieunhantanbao/sd2411-helm-charts/tree/main/charts/backend) |0.3.0 ||
|postgresdb |[myhelmrepo/postgresdb](https://github.com/sieunhantanbao/sd2411-helm-charts/tree/main/charts/postgresdb)|0.2.5||
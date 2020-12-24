# DevOps


build image

```sh
docker build -t react-notes:latest .

docker tag react-notes:latest hackerlinner/react-notes:latest
```

BITNAMI POSTGRESQL STACK HELM CHARTS

```sh
helm repo add bitnami https://charts.bitnami.com/bitnami

helm search repo postgresql
# bitnami/postgresql                      10.2.0          11.10.0         Chart for PostgreSQL, an object-relational data...
# bitnami/postgresql-ha                   6.3.3           11.10.0         Chart for PostgreSQL with HA architecture (usin...

helm pull bitnami/postgresql
```
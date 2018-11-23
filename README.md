# timescaledb

## kube deployment

1. `kubectl -n db create secret generic timescaledb --from-literal=postgres-password=<pass>`
1. `kubectl create -f timescaledb-pvc.yml`
1. `kubectl create -f timescaledb-db.yml`

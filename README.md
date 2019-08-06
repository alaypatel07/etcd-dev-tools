# etcd-dev-tools
This repository has tools to make etcd development and debugging easy.

### Spin a etcd cluster with docker-compose v2

1. Install docker-compose and clone the repo.
2. `cd etcd-dev-tools/etcd-v2`
3. Bring up the cluster by `docker-compose up -d`
4. Access the cluster:
    1. Get client shell: `docker exec -it etcd-v2_etcd-client_1 sh`
    2. Run etcdctl commands in the container: `etcdctl member list`

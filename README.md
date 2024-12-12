# ShafcoPharma
ShafcoPharma ERP
## steps to bring up the application:
```yaml
docker-compose up -d
```
check if the docker containers are running and healthy.

```sh
root@shafcopharma:~/odoo# docker ps
CONTAINER ID   IMAGE         COMMAND                  CREATED        STATUS             PORTS                                     NAMES
8564ef868a2b   odoo:13.0     "/entrypoint.sh odoo"    33 hours ago   Up About an hour   127.0.0.1:8069->8069/tcp, 8071-8072/tcp   odoo_odoo
9e0f627ebbad   postgres:13   "docker-entrypoint.s…"   33 hours ago   Up About an hour   5432/tcp                                  odoo_postgres
```


# Hacking on pg_dumpacl

A simple dev environment is described in `docker-compose.yml`:

``` console
$ docker-compose up -d
$ docker-compose exec build /bin/bash
root@ece3f6b4763e:/# cd /workspace
root@ece3f6b4763e:/workspace# make PG_CONFIG=/usr/lib/postgresql/9.6/bin/pg_config
root@ece3f6b4763e:/workspace# PGHOST=postgres PGUSER=postgres ./pg_dumpacl ...
```

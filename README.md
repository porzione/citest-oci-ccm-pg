# citest-oci-ccm-pg

Image for CircleCI build/test/deploy tasks with CCM and PostgreSQL
with added cassandra ccm and postgresql server

```
docker run -ti citest-oci-ccm-pg

docker run -e PG_USER=test -e PG_PASS=test -e PG_AUTH=md5 -e PG_DBNAME=test -e INFINITE_SLEEP=true citest-oci-ccm-pg

docker exec -ti $(docker ps -lq) bash
```

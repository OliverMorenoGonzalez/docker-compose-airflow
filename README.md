# docker-compose-airflow
docker compose apache airflow postgresql superset


Run this commands
```
 docker-compose up -d
```

Superset
```
  docker exec -it superset superset-init
```
Airflow-webserver create user change user and password for better security
```
  docker exec -it airflow-webserver airflow users --create --username airflow --lastname air --firstname flow --email airflow@example.com --role Admin --password airflow
```

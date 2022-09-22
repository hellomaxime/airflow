# airflow
Apache Airflow  

`mkdir -p ./dags ./logs ./plugins`  
`echo -e "AIRFLOW_UID=$(id -u)" > .env`  

`docker-compose up airflow-init`  

---

__Start Airflow__  
`docker-compose up -d`  

__Stop Airflow__  
`docker-compose stop`  

http://localhost:8080  

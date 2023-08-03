####  PARA SUBIR A APLICAÇÃO E VER OS TRACES

---

*1. Rodar o arquivo build.sh*

*2. docker compose -f docker-compose-elastic_collector.yml up -d* 

---

#### URLS


*UI Jaeger* 
http://localhost:16686/

*Endpoint Animals*
http://localhost:9000/api/v1/animals/random

*Endpoint Scientist*
http://localhost:8090/api/v1/scientists/random

*Endpoint Names*
http://localhost:8080/api/v1/names/random

*Kibana*
http://localhost:15601/app/home#/

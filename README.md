# Uses postgress in docker
docker run --name myPostgresDb -p 5432:5432 -e POSTGRES_USER=postgres -e POSTGRES_PASSWORD=passw0rd -e POSTGRES_DB=blog -d postgres

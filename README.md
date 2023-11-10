# go-hexagonal
Exemplo de arquitetura hexagonal (ports and adapters) na linguagem GO

docker-compose up -d
docker exec -it appproduct bash


mockgen -destination=application/mocks/application.go -source=application/product.go application

go mod tidy


# scripts
create table products(id string, name string, price float, status string);
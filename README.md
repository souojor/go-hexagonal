# go-hexagonal
Exemplo de arquitetura hexagonal (ports and adapters) na linguagem GO

go install github.com/spf13/cobra-cli@latest

docker-compose up -d
docker exec -it appproduct bash


mockgen -destination=application/mocks/application.go -source=application/product.go application

go mod tidy


# scripts
create table products(id string, name string, price float, status string);

# cobra client
~/go/bin/cobra-cli init --pkg-name=github.com/souojor/go-hexagonal
go mod tidy
~/go/bin/cobra-cli add cli

go run main.go cli -a=create -n=Product CLI -p=25.0
go run main.go cli -a=get --id=3836f0ee-ec2b-478f-b12d-9654ebadf1f5
# arquitetura-hexagonal


install docker

run docker-compose

docker exec  -it appproduct bash 

web service:

go run main.go http

usar postman para as requisições 

- create
- get
- enable


cli:


actions:

- create
- get

go run main.go cli --help

Flags:
  -a, --action string    Enable / Disable a product (default "enable")
  -h, --help             help for cli
  -i, --id string        Product ID
  -p, --price float      Product price
  -n, --product string   Product name

  usar flags exemplo:

  go run main.go cli -a create -n product1 -p 10.5

  go run main.go cli -a get -i //id do product criado
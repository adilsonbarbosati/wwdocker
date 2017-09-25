# stack-work-docker

Meus containers do docker para trabalhar com php + mysql + redis

# PHP
Na pasta do PHP executar o `Dockerfile` com o comando `docker build . `
E depois executar o `docker-compose.yml` com o `docker-compose up`



# Mysql e Redis
Executar o `docker-compose.yml` com o `docker-compose up` nas respectivas pastas.


# Acessar  o Mysql via terminal

Executar `docker ps` -  para listar os containers ativos
 
Executar `docker exec -it mysql5.6 bash` - para acessar o container
 
Executar `mysql -u root -p` - para acessar o mysql

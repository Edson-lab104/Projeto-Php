# Teste Apache + PHP 7 + MySQL + phpMyAdmin
> Ambiente local de desenvolvimento com Docker

Este repositório contém configurações Docker para a montagem de ambiente de desenvolvimento local com Apache, PHP 7, MySQL e phpMyAdmin.

**Pré requisitos:** Docker e Docker Compose

```bash
# Criar e levantar os containers
docker-compose up -d

# Iniciar o container Docker
docker-compose start

# Parar o container Docker
docker-compose stop

# Parar e remover containers da máquina
docker-compose down
```


**Acesso localhost**
```txt
http://localhost:4500
```

**Acesso phpMyAdmin**
```txt
http://localhost:8080

login: root
senha: root
```

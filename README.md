# Docker Cheatsheet

Anotações feitas durante o estudo do Docker para consultas posteriores.

## Comandos

#### docker

| Comando                      | Flag     | Descrição                                                                           |
| :--------------------------- | :------- | :---------------------------------------------------------------------------------- |
| `ps`                         |          | Mostra os containers rodando                                                        |
| `ps`                         | `-a`     | mostra todos os containers já executados na máquina                                 |
| `container ls`               |          | Mostra os containers rodando                                                        |
| `run ubuntu`                 |          | Baixa a imagem ubuntu (exemplo de imagem) e a roda em um container                  |
| `run ubuntu`                 | `-it`    | Roda o container e deixa executando no terminal                                     |
| `run ubuntu`                 | `-d`     | Modo detached, roda o container em background (não segura o terminal)               |
| `run ubuntu`                 | `-p`     | Expõe as portas do container (ex: 3000:80 expõe a 80 do terminal para a 3000 do PC) |
| `run ubuntu`                 | `--name` | Altera o nome aleatório quando criado o container                                   |
| `docker stop <name> ou <id>` |          | desativa o container em execucao de nome ou ID correspondentes                      |
| `docker start`               |          | Inicia um container já criado (o run sempre cria um novo container)                 |
| `docker rm <id>`             |          | Remove o container da máquina na qual estamos executando o docker                   |
| `docker rm <id>`             | `-f`     | Força a remover enquanto o container está sendo executado                           |
| `ps`                         |          | Mostra os containers rodando                                                        |

#### docker-compose

| Comando | Flag | Descrição |
| :------ | :--- | :-------- |
| ``      | ``   |           |

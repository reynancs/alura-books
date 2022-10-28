## :dart: Objetivo
Utilizar o Docker-Compose em um único arquivo com extensão `.yml` para definir e executar múltiplos containers de uma só vez e de maneira coordenada, evitando executar comandos individualmente no seu terminal.


## :pushpin: Descrição
Está prática é utilizando um arquivo `docker-compose` para criar e executar dois containers: um com uma aplicação web `alura-books` e outro para banco de dados mongoDB `meu-mongo` além de uma network definida como `compose-bridge` o qual estarão se comunicando através da porta 3000.
![Books Store](image.png)


## :computer: Como rodar a aplicação
1. Realize o fork do projeto e em seguida no seu terminal git bash dê o comando `git clone` para copiar o repositório para sua máquina local.
2. `docker-compose up -d` -> dar este comando no seu terminal do linux ou WSL2 no diretória da aplicação;
3. http://localhost:3000/seed -> Digite no seu web browser com o /seed para popular o banco (Aba 01)
4. http://localhost:3000 -> Digite no seu web browser para rodar a aplicação (Aba 02)

Outros comandos:
- `docker compose ps`: Lista os serviços do compose que foram criados
- `docker-compose down`: Remove os serviços de containers e rede que foram criados



## :triangular_flag_on_post: Pré-Requisitos
- VS Code v1.72.2
- WSL2 para Windows
- [Docker Desktop](https://docs.docker.com/desktop/install/windows-install/)
- [Docker Compose](https://docs.docker.com/compose/install/)


## :link: Links/Referência
[Documentação Oficial Docker-Compose](https://docs.docker.com/compose/)
[Docker:criando e gerenciando containers by Alura - 10h](https://cursos.alura.com.br/course/docker-criando-gerenciando-containers)


### :bookmark: Notas
A aplicação é exposta usando a porta 3000

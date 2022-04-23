# Docker Todo List

Docker Todo List é um projeto baseado em desafios de Docker, visando a prática dos comandos da CLI da ferramenta e da conteinerização de aplicações já existentes. Além disso, como um bônus, foi elaborado um arquivo YAML para configurar os serviços da aplicação e, com isso, utilizar o Docker Compose para orquestrar os contêineres.

As aplicações desse projeto, que envolvem todo o conteúdo das pastas `docker/todo-app/back-end` e `docker/todo-app/front-end` exceto os arquivos Dockerfile, foram fornecidas pela [Trybe](https://betrybe.com).

## Tecnologias utilizadas

O projeto foi desenvolvido utilizando [Docker](https://www.docker.com/), incluindo a ferramenta [Docker Compose](https://docs.docker.com/compose/).

## Desafios

Os desafios a seguir foram providos pela [Trybe](https://betrybe.com) e são uma forma adaptada dos desafios originais. Os comandos referentes a cada desafio se encontram na pasta `docker/docker-commands` nomeados como `commandN.dc` onde _N_ representa o número do desafio.

### 1. Crie um novo container de modo interativo sem roda-lo nomeando-o como `01container` e utilizando a imagem `alpine` usando a versão `3.12`.

### 2. Inicie o container `01container`.

### 3. Liste os containers filtrando pelo nome `01container`.

### 4. Execute o comando `cat /etc/os-release` no container `01container` sem se acoplar a ele.

### 5. Remova o container `01container` que está em andamento.

### 6. Faça o download da imagem `nginx` com a versão `1.21.3-alpine` sem criar ou rodar um container.

### 7. Rode um novo container com a imagem `nginx` com a versão `1.21.3-alpine` em segundo plano nomeando-o como `02images` e mapeando sua porta padrão de acesso para porta `3000` do sistema hospedeiro.

### 8. Pare o container `02images` que está em andamento.

### 9. Gere uma build a partir do Dockerfile do `back-end` do `todo-app` nomeando a imagem para `todobackend`.

**O Dockerfile criado neste desafio se encontra na pasta `docker/todo-app/back-end`**

### 10. Gere uma build a partir do Dockerfile do `front-end` do `todo-app` nomeando a imagem para `todofrontend`.

**O Dockerfile criado neste desafio se encontra na pasta `docker/todo-app/front-end`**

### 11. Suba uma orquestração em segundo plano com o docker-compose de forma que `backend` e `frontend` consigam se comunicar.

**O arquivo `docker-compose.yml` criado neste desafio se encontra na pasta `docker`**

---

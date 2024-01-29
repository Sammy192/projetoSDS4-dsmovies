![Static Badge](https://img.shields.io/badge/React-blue?logo=REACT)
![Static Badge](https://img.shields.io/badge/Type%20Script-black?logo=typescript)

![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)


Este repositório contém o projeto desenvolvido durante a semana DevSuperior SDS4 ministrado pelo
professor [Nelio Alves](https://www.udemy.com/user/nelio-alves/), oferecido pela plataforma [DevSuperior](https://devsuperior.com.br/).</br></br>
Este projeto visa criar um WebSite Movies que exibe uma lista de filmes e seus votos de qualidade.
Usando tecnologias **Java, Spring Boot, Spring Data JPA, React, Type Script**.</br>

## Modelo conceitual

![image](https://github.com/Sammy192/projetoSDS4-dsmovies/assets/53224915/37a8c969-9624-4e1d-aacc-8fc58433781b)

## Layout

Acesso para layout no figma -> https://www.figma.com/file/hpQuzpGHq2MmrI87xnfMoT/DSMovie1?type=design&node-id=0-1&mode=design

![image](https://github.com/Sammy192/projetoSDS4-dsmovies/assets/53224915/49115a98-c322-424d-b7e0-b7c928084dec)

![image](https://github.com/Sammy192/projetoSDS4-dsmovies/assets/53224915/d47fd687-cc78-41f2-a0b9-b4a9967fab68)

## Como executar este projeto

IDEs utilizadas normalmente:
- **Java 17**: [JDK 17](https://www.oracle.com/java/technologies/downloads/) ou superior.
- **IDEs**: [IntelliJ IDEA](https://www.jetbrains.com/idea/download/) ou [Spring Tools](https://spring.io/tools).
- **VsCode** para o front-end

Realizar o download ou clone do repositório.
Para executar o back-end:
Importe a pasta 'backend' na sua IDE de preferência e execute a classe principal do projeto.

Para executar o front-end:
Importe a pasta 'front-end' na sua IDE de preferência.
Execute o comando:
```
npm install
após executar
yarn start
```
Aguarde o projeto ser carregado no seu navegador.

## Endpoints da API:
Download coleção do postman -> [https://drive.google.com/file/d/1fNtgZ_zBgpKaCGFfWpBNzLX6PtRJ_Puy/view?usp=sharing](https://drive.google.com/file/d/1Gavob4p6IdvqVLxF-4CUwNm3Qhfk0UhD/view?usp=sharing)
Pode ser importado os endpoints no postman

```

GET /movies - Retorna lista de filmes.

GET /movies/1- Retorna um filme buscado pelo ID

PUT /scores - Envia um voto de avaliação para um determinado filme

```


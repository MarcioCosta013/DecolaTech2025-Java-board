[JAVA_BADGE]:https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white

[SPRING_BADGE]: https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white

[GRADLE_BADGE]: https://img.shields.io/badge/Gradle-02303A.svg?style=for-the-badge&logo=Gradle&logoColor=white

[DOCKER_BADGE]: https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white

<h1 id="portugues" align="center"> Board Java DecolaTech 2025 </h1>

![java][JAVA_BADGE]
![spring][SPRING_BADGE]
![Gradle][GRADLE_BADGE]
![Docker][DOCKER_BADGE]

**English version** : [Click here](#ingles) .

Repositório original do Fork: [DigitalInnovationOne - Board](https://github.com/digitalinnovationone/board) .

## Descrição do projeto

Este projeto é um gerenciador de boards desenvolvido em Java. Ele permite criar, selecionar e excluir boards, além de realizar operações em cards.

## Tecnologias utilizadas

* Java 11
* Spring Boot
* Gradle
* MySQL

## Estrutura do projeto

O projeto é dividido em pacotes principais:

* `br.com.dio`: pacote principal do projeto
* `br.com.dio.ui`: pacote de classes de interface do usuário
* `br.com.dio.persistence`: pacote de classes de persistência de dados
* `br.com.dio.service`: pacote de classes de 

```
src/
├── main/
│ ├── java/
│ │ ├── br/
│ │ │ ├── com/
│ │ │ │ ├── dio/
│ │ │ │ │ ├── Board.java # Classe Board
│ │ │ │ │ ├── BoardColumn.java # Classe BoardColumn
│ │ │ │ │ ├── BoardService.java # Serviço de Board
│ │ │ │ │ └── ...
│ │ │ │ ├── ui/
│ │ │ │ │ ├── MainMenu.java # Classe MainMenu
│ │ │ │ │ ├── BoardMenu.java # Classe BoardMenu
│ │ │ │ │ └── ...
│ │ │ │ ├── persistence/
│ │ │ │ │ ├── dao/
│ │ │ │ │ │ ├── BoardDAO.java # DAO de Board
│ │ │ │ │ │ ├── BoardColumnDAO.java # DAO de BoardColumn
│ │ │ │ │ │ └── ...
│ │ │ │ │ ├── entity/
│ │ │ │ │ │ ├── BoardEntity.java # Entidade Board
│ │ │ │ │ │ ├── BoardColumnEntity.java # Entidade BoardColumn
│ │ │ │ │ │ └── ...
│ │ │ │ │ └── ...
│ │ │ │ ├── service/
│ │ │ │ │ ├── BoardService.java # Serviço de Board
│ │ │ │ │ ├── BoardColumnService.java # Serviço de BoardColumn
│ │ │ │ │ └── ...
│ │ │ │ └── ...
│ │ │ └── ...
│ │ └── ...
│ └── ...
├── resources/
│ ├── application.properties # Configurações de aplicação
│ └── ...
├── test/
│ ├── java/
│ │ ├── br/
│ │ │ ├── com/
│ │ │ │ ├── dio/
│ │ │ │ │ ├── BoardTest.java # Teste de Board
│ │ │ │ │ ├── BoardColumnTest.java # Teste de BoardColumn
│ │ │ │ │ └── ...
│ │ │ │ └── ...
│ │ └── ...
│ └── ...
└── ...
```

## Funcionalidades

* Criar um novo board
* Selecionar um board existente
* Excluir um board
* Realizar operações em cards (criar, mover, bloquear, desbloquear, cancelar)

## Dependências

* `org.springframework.boot:spring-boot-starter-web`
* `org.springframework.boot:spring-boot-starter-data-jpa`
* `mysql:mysql-connector-java`

## Configuração

Para configurar o projeto, é necessário definir as seguintes variáveis de ambiente:

* `JAVA_HOME`: caminho para a instalação do Java
* `GRADLE_HOME`: caminho para a instalação do Gradle
* `DB_URL`: URL do banco de dados MySQL
* `DB_USERNAME`: nome de usuário do banco de dados
* `DB_PASSWORD`: senha do banco de dados

## Execução

Para executar o projeto, é necessário executar o comando `gradle bootRun` na raiz do projeto.

## 😎 Minhas Redes Sociais:

 **Marcio Costa**

* Github: [MarcioCosta013](https://github.com/MarcioCosta013)
* LinkedIn: [linkedin.com\/in\/marcio-jcosta\/](https://linkedin.com/in/https:\/\/www.linkedin.com\/in\/marcio-jcosta\/)
* Instagran: [@marcio_costa013](https://www.instagram.com/marcio_costa013/)

## 🙏🏿 Mais Ajuda

Para obter mais ajuda sobre o Angular CLI, use `ng help` ou confira a [documentação oficial do Angular CLI](https://angular.io/cli).

## 🤝 Contribuição

Contribuições, problemas e solicitações de recursos são bem-vindos!<br />Fique à vontade para conferir [issues page](https://github.com/MarcioCosta013/DecolaTech2025-angular-blog/issues). 

## 🤩 Mostre seu apoio

Dê uma ⭐️ se este projeto te ajudou!


</br></br></br></br></br></br></br>


<h1 id="ingles" align="center"> Board Java DecolaTech 2025 </h1>

![java][JAVA_BADGE]
![spring][SPRING_BADGE]
![Gradle][GRADLE_BADGE]
![Docker][DOCKER_BADGE]

**Versão em Português** : [Click Aqui](#portugues) . 

Original repository of the Fork: [DigitalInnovationOne - Board](https://github.com/digitalinnovationone/board) .


## Project Description

This project is a board manager developed in Java. It allows creating, selecting, and deleting boards, as well as performing operations on cards.

## Technologies 

- Java 11
- Spring Boot
- Gradle
- MySQL

## Project Structure

The project is divided into main packages:

* `br.com.dio`: main project package
* `br.com.dio.ui`: user interface classes package
* `br.com.dio.persistence`: data persistence classes package
* `br.com.dio.service`: service classes package

```
src/
├── main/
│ ├── java/
│ │ ├── br/
│ │ │ ├── com/
│ │ │ │ ├── dio/
│ │ │ │ │ ├── Board.java # Board class
│ │ │ │ │ ├── BoardColumn.java # BoardColumn class
│ │ │ │ │ ├── BoardService.java # Board service
│ │ │ │ │ └── ...
│ │ │ │ ├── ui/
│ │ │ │ │ ├── MainMenu.java # MainMenu class
│ │ │ │ │ ├── BoardMenu.java # BoardMenu class
│ │ │ │ │ └── ...
│ │ │ │ ├── persistence/
│ │ │ │ │ ├── dao/
│ │ │ │ │ │ ├── BoardDAO.java # Board DAO
│ │ │ │ │ │ ├── BoardColumnDAO.java # BoardColumn DAO
│ │ │ │ │ │ └── ...
│ │ │ │ │ ├── entity/
│ │ │ │ │ │ ├── BoardEntity.java # Board entity
│ │ │ │ │ │ ├── BoardColumnEntity.java # BoardColumn entity
│ │ │ │ │ │ └── ...
│ │ │ │ │ └── ...
│ │ │ │ ├── service/
│ │ │ │ │ ├── BoardService.java # Board service
│ │ │ │ │ ├── BoardColumnService.java # BoardColumn service
│ │ │ │ │ └── ...
│ │ │ │ └── ...
│ │ │ └── ...
│ │ └── ...
│ └── ...
├── resources/
│ ├── application.properties # Application configuration
│ └── ...
├── test/
│ ├── java/
│ │ ├── br/
│ │ │ ├── com/
│ │ │ │ ├── dio/
│ │ │ │ │ ├── BoardTest.java # Board test
│ │ │ │ │ ├── BoardColumnTest.java # BoardColumn test
│ │ │ │ │ └── ...
│ │ │ │ └── ...
│ │ └── ...
│ └── ...
└── ...
```


## Features

* Create a new board
* Select an existing board
* Delete a board
* Perform operations on cards (create, move, block, unblock, cancel)

## Dependencies

* `org.springframework.boot:spring-boot-starter-web`
* `org.springframework.boot:spring-boot-starter-data-jpa`
* `mysql:mysql-connector-java`

## Configuration

To configure the project, you need to set the following environment variables:

* `JAVA_HOME`: path to Java installation
* `GRADLE_HOME`: path to Gradle installation
* `DB_URL`: MySQL database URL
* `DB_USERNAME`: database username
* `DB_PASSWORD`: database password

## Execution

To run the project, execute the `gradle bootRun` command at the project root.

## 😎 My social networks:

**Marcio Costa**

* Github: [MarcioCosta013](https://github.com/MarcioCosta013)
* LinkedIn: [linkedin.com\/in\/marcio-jcosta\/](https://linkedin.com/in/https:\/\/www.linkedin.com\/in\/marcio-jcosta\/)
* Instagram: [@marcio_costa013](https://www.instagram.com/marcio_costa013/)


## 🤝 Contribution

Contributions, issues, and feature requests are welcome!<br />Feel free to check the [issues page](https://github.com/MarcioCosta013/DecolaTech2025-angular-blog/issues).

## 🤩 Show your support

Give a ⭐️ if this project helped you!

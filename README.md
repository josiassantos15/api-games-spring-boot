# API de Games com Spring Boot

Este projeto é uma API de Games desenvolvida utilizando o framework Spring Boot e a ferramenta de gerenciamento de dependências Maven. A API segue o padrão de arquitetura REST e tem como objetivo fornecer endpoints para a manipulação de informações relacionadas a jogos.

## Pré-requisitos

Antes de executar este projeto, certifique-se de ter os seguintes componentes instalados:

- Java Development Kit (JDK) versão 8 ou superior
- Maven
- Spring Boot

## Executando o projeto

Para executar a API de Games, siga os passos abaixo:

1. Clone este repositório em sua máquina local:

```
git clone https://github.com/seu-usuario/api-games-spring-boot.git
```

2. Acesse o diretório do projeto:

```
cd api-games-spring-boot
```

3. Compile o projeto utilizando o Maven:

```
mvn compile
```

4. Execute a aplicação:

```
mvn spring-boot:run
```

Após a execução bem-sucedida, a API estará disponível em `http://localhost:8080`.

## Endpoints

A API de Games possui os seguintes endpoints principais:

- `GET /games`: Retorna a lista completa de jogos.
- `GET /games/{id}`: Retorna as informações de um jogo específico pelo seu ID.
- `POST /games`: Cria um novo jogo com base nas informações fornecidas.
- `PUT /games/{id}`: Atualiza as informações de um jogo existente.
- `DELETE /games/{id}`: Remove um jogo pelo seu ID.

Certifique-se de fornecer as informações corretas nos payloads de requisição quando necessário.

## Documentação

Para obter mais detalhes sobre os endpoints disponíveis e os dados esperados nas requisições, consulte a documentação completa da API. Acesse `http://localhost:8080/swagger-ui.html` após iniciar a aplicação para visualizar a documentação interativa.

## Contribuição

Se você deseja contribuir para este projeto, fique à vontade para abrir uma issue ou enviar um pull request. Sua colaboração é muito bem-vinda!

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

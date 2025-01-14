# Hello

Este é um projeto simples desenvolvido com Spring Boot. Ele contém apenas um controlador que expõe um endpoint para retornar uma mensagem de "Hello World!".

## Requisitos

Certifique-se de ter os seguintes requisitos instalados em sua máquina antes de executar o projeto:

- Java 11 ou superior
- Maven 3.6 ou superior

## Como executar o projeto

1. Clone este repositório em sua máquina local:
   ```bash
   git clone https://github.com/gsmzupper/Helo.git
   cd Hello

mvn spring-boot:run

3. 
O projeto estará disponível em: http://localhost:8080/
Endpoint disponível
GET /
Retorna a mensagem "Hello World!".
Estrutura do projeto
O projeto contém a seguinte estrutura básica:
src/ ├── main/ │ ├── java/ │ │ └── com.example.hello/ │ │ └── HelloController.java │ └── resources/ │ └── application.properties
HelloController.java: Contém o endpoint que retorna a mensagem "Hello World!".
application.properties: Arquivo de configuração do Spring Boot.
Exemplo de resposta
Ao acessar o endpoint http://localhost:8080/, você receberá a seguinte resposta:
{
  "message": "Hello World!"
3}
Tecnologias utilizadas
Spring Boot
Maven
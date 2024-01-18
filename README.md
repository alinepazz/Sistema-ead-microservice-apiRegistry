# EAD - SERVICE REGISTRY
## Sobre o projeto
Projeto Decoder EAD - Arquitetura de microservices, tem como maior
objetivo colocar em prática todos os conceitos abordados.

Cada funcionalidade da plataforma é abordada como um serviço independente, promovendo flexibilidade e isolamento de responsabilidades.

### Alguns dos conceitos abordados ao longo do projeto
`Shared Database Pattern`
`Event Driven Pattern`
`Comunicação por Coreografia`
`Authentication e Authorization com JWT`
`Observability`
`SAGA Pattern`
`Cross
Cutting`
`Event Carried State Transfer Pattern`

### Desenho da solução
![Desenho da solucao ead](imagens/projeto.png)

## Sobre a API
Implementação de um serviço de registro que monitora e armazena as instâncias e localizações dos microservices, possibilitando a descoberta dinâmica desses services pelos clients.

## Tecnologias utilizadas
- Java 11
- Spring boot
- Maven
- Eureka Server
- Spring Security

# Como executar o projeto
Pré-requisitos: Java 11

```bash
# clonar repositório
git clone https://github.com/alinepazz/sistema-ead-microservice-api-registry.git

# entrar na pasta raiz do projeto

# executar o projeto
mvn spring-boot:run
```
### Autor
Aline Soares da Paz

https://www.linkedin.com/in/alinepazz/


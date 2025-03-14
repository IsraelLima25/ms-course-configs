# 🌩️ Mono repo - Microserviços com Spring Cloud

Projeto desenvolvido para explorar o ecossistema **Spring Cloud**, permitindo a experimentação de um fluxo de dados publicado em tópicos do **Kafka**, consumido e persistido em uma base de dados. O código demonstra o uso das ferramentas do **Spring Cloud** para:

- Gerenciamento de transações;
- Consumo e publicação de mensagens;
- Comunicação rest http
- Descoberta e registro de microserviços;
- Integração com **Docker** para conteinerização dos serviços.


## 🚀 Tecnologias

- Java 17+  
- Spring Boot  
- Spring Cloud (Eureka, OpenFeign, Config Server, etc.)  
- Docker   
- Mensageria Kafka
- Banco de Dados (PostgreSQL/MySQL, se aplicável)  

## 📥 Instalação e Execução

1. Clone o repositório:
   ```sh
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   ```

2. Configure as variáveis de ambiente ou o **Config Server**.  
3. Suba os serviços (caso tenha dependências como Eureka, Config Server, etc.):
   ```sh
   docker-compose up -d
   ```

4. Execute a aplicação:
   ```sh
   mvn spring-boot:run
   ```

## 📌 Funcionalidades

- 🔹 Descoberta de serviços com **Eureka**  
- 🔹 Comunicação entre microserviços com **OpenFeign**  
- 🔹 Configuração centralizada com **Spring Cloud Config**  
- 🔹 Balanceamento de carga com **Spring Cloud LoadBalancer**  
- 🔹 Mensageria com **Kafka**

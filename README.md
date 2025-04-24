
# Projeto Dev com a Digital Innovation One 🚀

Aplicação desenvolvida durante a **Santander Dev Week 2023**, simulando uma API REST de um banco digital. O projeto foi construído com **Spring Boot**, utilizando boas práticas de arquitetura e organização em camadas.

## 📦 Sobre o Projeto

Este projeto tem como objetivo simular os dados bancários de um usuário, como conta, cartão, funcionalidades e notícias, através de uma API REST estruturada.

### 🔧 Tecnologias utilizadas

- Java 17
- Spring Boot
- Spring Data JPA
- H2 Database (banco em memória)
- Gradle
- Lombok
- Heroku (para deploy)
- Swagger (para documentação da API)

---

## 📁 Estrutura do Projeto

```
src
├── main
│   └── java
│       └── me.dio
│           ├── controller           # Camada de controle (REST Controllers)
│           ├── domain
│           │   ├── model           # Entidades do sistema
│           │   └── repository      # Interfaces dos repositórios JPA
│           └── Application.java    # Classe principal (Spring Boot)
│
├── resources
│   ├── application.properties      # Configurações do projeto
```

---

## 🚀 Como executar

### Pré-requisitos
- Java 17+
- Gradle instalado (ou usar os scripts `gradlew`)

### Passo a passo

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/santander-dev-week-2023.git
cd santander-dev-week-2023

# Execute o projeto
./gradlew bootRun
```

Acesse: `http://localhost:8080`

---

## 🧪 Endpoints principais

- `GET /users/{id}` - Retorna os dados do usuário
- `POST /users` - Cadastra um novo usuário
- `GET /users` - Lista todos os usuários

> Documentação interativa disponível via Swagger em `/swagger-ui.html` (caso esteja configurado)

---

## 🧠 Aprendizados

Este projeto cobre conceitos como:
- Arquitetura em camadas
- Integração com banco de dados usando Spring Data
- Tratamento global de exceções
- Uso de anotações do Lombok para reduzir boilerplate
- Deploy com Heroku

---

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## 💬 Contato

Desenvolvido por [Gabriel](https://github.com/GabrielSmash) ✨  
Fique à vontade para abrir issues, dar sugestões ou contribuir com melhorias!

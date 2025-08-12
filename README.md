# 📊 App de Gestão de Orçamento

Aplicação para **gestão financeira pessoal**, com backend em **Java Spring Boot** e frontend em **Angular**, permitindo controle simples e eficiente de contas, créditos e débitos.

---

## 🚀 Funcionalidades Atuais

* 👤 Cadastro básico de um único usuário
* 🏦 Cadastro de diferentes contas (bancos)
* 💰 CRUD de Créditos e Débitos (adicionar, visualizar, editar e excluir)

---

## 📌 Próximas Funcionalidades

* 📅 Contas a pagar (com notificação de vencimento próximo)
* 📈 Relatórios por banco e geral
* 👥 Suporte a múltiplos usuários

---

## 🛠 Tecnologias Utilizadas

* **Backend:** Java 17 / Spring Boot 3
* **Banco de Dados:** MySQL / PostgreSQL / H2 (para testes)
* **Frontend:** Angular
* **Ferramentas:** Maven, Git, Docker (opcional)

---

## ☁ Futuro do Projeto (Deploy na AWS)

* Amazon EC2 / Elastic Beanstalk para hospedagem
* Amazon RDS / DynamoDB para banco de dados
* Amazon SNS para notificações

---

## 🌐 Front-end Angular

O front-end está no diretório `frontend/`.

### Desenvolvimento

```bash
cd frontend
npm install
ng serve
```

Acesse: `http://localhost:4200`

O backend deve estar rodando em `http://localhost:8080` para comunicação via API.

### Build para produção e integração com backend

```bash
cd frontend
ng build --prod
```

Copie o conteúdo gerado para o backend:

```bash
cp -r dist/* ../backend/src/main/resources/static/
```

Ao rodar o backend, o front estará disponível em: `http://localhost:8080`

---

## 🚀 Backend Spring Boot

### Rodar o backend

```bash
cd backend
mvn install
mvn spring-boot:run
```

Ou:

```bash
java -jar target/gestao-orcamento.jar
```

Acesse: `http://localhost:8080`

---

## 📂 Estrutura do Projeto

```
gestao-orcamento/
│
├── backend/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   ├── resources/
│   │   │   │   └── static/       # Build Angular para produção
│   │   └── test/
│   ├── pom.xml
│
├── frontend/
│   ├── src/
│   ├── e2e/
│   ├── angular.json
│   ├── package.json
│   └── tsconfig.json
│
├── README.md
└── .gitignore
```

---

## 🤝 Como Contribuir

1. Fork o projeto
2. Crie uma branch para sua feature:

   ```bash
   git checkout -b minha-feature
   ```
3. Faça commit das alterações:

   ```bash
   git commit -m "Minha nova feature"
   ```
4. Envie para o remoto:

   ```bash
   git push origin minha-feature
   ```
5. Abra um Pull Request

---

## 📜 Licença

Este projeto está sob a licença **MIT**.

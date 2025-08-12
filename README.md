# 📊 App de Gestão de Orçamento

Um aplicativo básico para gestão financeira pessoal, permitindo o controle de contas, créditos e débitos de forma simples e objetiva.

---

## 🚀 Funcionalidades Atuais

* **Cadastro básico de um único usuário**
* **Cadastro de diferentes contas (bancos)**
* **CRUD de Créditos e Débitos** (adicionar, visualizar, editar e excluir)

---

## 🛠️ Tecnologias Utilizadas

> *(Ajuste de acordo com o stack que você usou)*

* **Backend:** Java / Spring Boot
* **Banco de Dados:** MySQL / PostgreSQL / H2
* **Frontend:** HTML / CSS / JavaScript ou framework usado
* **Ferramentas:** Git, Maven/Gradle, Docker (opcional)

---

## 📌 Próximas Funcionalidades

* **Contas a pagar** (com notificação quando próximo do vencimento)
* **Relatórios por banco e geral**
* **Suporte a múltiplos usuários**

---

## 📦 Como Executar o Projeto

1. **Clone o repositório**

   ```bash
   git clone https://github.com/Morais453/GestaoOrcamentaria.git
   ```

2. **Acesse o diretório do projeto**

   ```bash
   cd NOME_DO_REPOSITORIO
   ```

3. **Instale as dependências** *(se necessário)*

   ```bash
   mvn install
   ```

4. **Inicie o servidor**

   ```bash
   mvn spring-boot:run
   ```

   ou

   ```bash
   java -jar target/gestao-orcamento.jar
   ```

5. **Acesse no navegador:**

   ```
   http://localhost:8080
   ```

---

## 📂 Estrutura do Projeto

```
gestao-orcamento/
│── src/
│   ├── main/
│   │   ├── java/        # Código fonte backend
│   │   ├── resources/   # Configurações e templates
│   └── test/            # Testes automatizados
│── pom.xml              # Configuração Maven
│── README.md            # Documentação do projeto
```

---

## 🤝 Contribuição

1. Faça um **fork** do projeto
2. Crie uma branch para sua feature:

   ```bash
   git checkout -b minha-feature
   ```
3. Faça commit das alterações:

   ```bash
   git commit -m 'Minha nova feature'
   ```
4. Envie para o repositório remoto:

   ```bash
   git push origin minha-feature
   ```
5. Abra um **Pull Request**

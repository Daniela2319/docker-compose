# 🐳 Projeto Docker Compose: PostgreSQL + Adminer

Este projeto configura um ambiente com **PostgreSQL** e **Adminer** usando Docker Compose.  
É ideal para desenvolvimento, testes e aprendizado com bancos de dados SQL, com uma interface web para interagir com os dados.



## 🚀 Tecnologias utilizadas

- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)
- [PostgreSQL](https://www.postgresql.org/)
- [Adminer](https://www.adminer.org/)



## 📁 Estrutura do projeto

```
compose-postgres-adminer/
├── docker-compose.yml
├── postgres/
│ └── Dockerfile (opcional - imagem personalizada)
├── adminer/
│ └── Dockerfile (opcional - imagem personalizada)
└── README.md
```

---
## 🖼️ Tela do Adminer

![Tela do Adminer](https://github.com/user-attachments/assets/7dca0fb3-afdf-4e48-9afe-a683504ec053)




## ⚙️ Como executar o projeto

### ✅ Pré-requisitos

- Docker instalado
- Docker Compose instalado
- Git instalado (opcional)

### 🛠️ Clonar o repositório

```bash
git clone https://github.com/Daniela2319/docker-compose.git
cd docker-compose
```
## ⚙ Subir os containers

```
docker-compose up -d --build
```

## 🌐 Acessar os serviços
### 🗄️ Adminer
Acesse via navegador:

```
http://localhost:8080
```

Preencha os seguintes dados para acessar o PostgreSQL:

* Sistema: PostgreSQL

* Servidor: postgres

* Usuário: admin

* Senha: admin123

* Banco de dados: minhaaplicacao

📦 Configurações do PostgreSQL
Essas configurações estão definidas no arquivo `docker-compose.yml`:
```
POSTGRES_USER: admin
POSTGRES_PASSWORD: admin123
POSTGRES_DB: minhaaplicacao

```

## 🔍 Verificar containers em execução

```
docker ps
```
## 📌 Observações
* Este projeto é focado no uso de containers para testes e estudos.

* Você pode expandir esse ambiente para incluir uma aplicação backend conectada ao PostgreSQL.

* Pode também substituir o Adminer por outras ferramentas como pgAdmin, DBeaver, etc.

## 👩‍💻 Autora
Daniela Velter
## 🔗 GitHub - @Daniela2319


---




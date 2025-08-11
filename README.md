# 🐳 Databases-Docker

Este repositório reúne **ambientes prontos de banco de dados** usando Docker Compose.  
Cada pasta contém um ficheiro `docker-compose.yml` já configurado para inicializar rapidamente o serviço correspondente.

## 📌 Objetivo
Facilitar a criação de ambientes locais para **desenvolvimento**, **testes** e **aprendizagem** sem precisar instalar manualmente cada SGBD na máquina.

## 👥 Público-Alvo
- **Desenvolvedores** que trabalham com múltiplas bases de dados.
- **Estudantes** de SQL ou NoSQL.
- **Equipes de QA** que precisam de ambientes de teste isolados.
- **Integradores** que necessitam validar aplicações em diferentes SGBDs.

---

## 📂 Estrutura do Repositório

```plaintext
/
├── Azurite/           # Emulador de Azure Storage (Tabelas, Blobs, Filas)
│   └── docker-compose.yml
├── MariaDB/           # Banco de dados MariaDB
│   └── docker-compose.yml
├── MySQL 8.x/         # Banco de dados MySQL 8
│   └── docker-compose.yml
├── PostgreSQL/        # Banco de dados PostgreSQL 16
│   └── docker-compose.yml
├── SQL Server 2022/   # Banco de dados SQL Server 2022
│   └── docker-compose.yml

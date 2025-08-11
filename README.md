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

## 🚀 Como Usar

Entre na pasta do serviço desejado, por exemplo:

  cd "SQL Server 2022"
  
Execute o container:
  docker compose up -d
  
Para parar o container:
  docker compose down

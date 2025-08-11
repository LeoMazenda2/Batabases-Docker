# 🐳 Databases-Docker

Este repositório reúne **ambientes prontos de banco de dados** usando **Docker Compose**.  
Cada pasta contém um ficheiro `docker-compose.yml` configurado para inicializar rapidamente o serviço correspondente, sem complicações.

---

## ℹ️ Sobre o Repositório
Este projeto foi criado para fornecer um **conjunto de configurações Docker Compose** que permitem subir rapidamente ambientes de diferentes Sistemas de Gestão de Bases de Dados (**SQL Server, MySQL, MariaDB, PostgreSQL, MongoDB e Azurite**).  

Com ele, qualquer pessoa pode:
- Criar **ambientes de desenvolvimento** de forma rápida e padronizada.
- Realizar **testes isolados** sem interferir no ambiente local.
- Aprender e praticar SQL ou NoSQL com facilidade.
- Ter um ambiente multi-banco de dados pronto para **projetos de integração**.

💡 **Utilidade prática:**  
Ideal para **desenvolvedores, estudantes, testadores e integradores** que precisam de ambientes prontos, confiáveis e descartáveis para uso local.

---

## 📌 Objetivo
Facilitar a criação de ambientes locais para:
- **Desenvolvimento**
- **Testes**
- **Aprendizagem**

Tudo isso **sem instalar manualmente** cada SGBD na máquina.

---

## 👥 Público-Alvo
- 👨‍💻 **Desenvolvedores** que trabalham com múltiplos bancos de dados.
- 🎓 **Estudantes** de SQL ou NoSQL.
- 🧪 **Equipes de QA** que precisam de ambientes de teste isolados.
- 🔗 **Integradores** que necessitam validar aplicações com diferentes SGBDs.

---

## 🛠 Pré-requisitos

Antes de utilizar este repositório, certifique-se de ter:

1. **Docker Desktop** instalado e atualizado.  
   - [Download Docker Desktop](https://www.docker.com/products/docker-desktop)
   - Disponível para **Windows**, **macOS** e **Linux**.

2. **Docker Compose** instalado (versão 2.x ou superior).  
   - Já vem incluso no Docker Desktop, mas em Linux pode ser necessário instalar manualmente:
     ```bash
     sudo apt install docker-compose-plugin
     ```

3. **Portas livres** para evitar conflitos:  
   - **1433** → SQL Server  
   - **3306** → MySQL / MariaDB  
   - **5432** → PostgreSQL  
   - **27017** → MongoDB  
   - **10002** → Azurite (Tabelas)

4. **Acesso ao terminal** ou linha de comando:
   - Windows → PowerShell / CMD
   - macOS / Linux → Terminal

5. **Permissões de administrador** para rodar o Docker.

---

## 🚀 Como Usar

- **Entre na pasta do serviço desejado** por exemplo:.
- **Execute o container**

  ```bash
  docker compose up -d

# 🐳 Ambientes de Banco de Dados com Docker Compose

Este repositório contém **5 configurações Docker Compose** para inicializar rapidamente ambientes de bases de dados populares, ideais para **desenvolvimento**, **testes** e **aprendizagem**.

## 📋 Lista de Serviços

| Serviço         | Porta Padrão | Usuário | Senha          | Base de Dados Padrão |
|-----------------|--------------|--------|---------------|----------------------|
| 🗄 SQL Server 2022 | 1433         | sa     | @Nunsey123#   | — (criar manualmente)|
| 🐬 MySQL 8.x     | 3306         | admin  | @Nunsey123#   | appdb                |
| 🐬 MariaDB 11.x  | 3306         | admin  | @Nunsey123#   | appdb                |
| 🍃 MongoDB 7.x   | 27017        | admin  | @Nunsey123#   | — (criar manualmente)|
| 🐘 PostgreSQL 16 | 5432         | admin  | @Nunsey123#   | appdb                |

> ⚠️ **Atenção:** Estas senhas são para uso local e não devem ser utilizadas em produção.

---

## 🚀 Pré-requisitos
- [Docker](https://www.docker.com/products/docker-desktop) instalado
- Portas padrão livres no sistema
- Conhecimentos básicos de terminal

---

## 🛠 Como Usar

### 1️⃣ Subir o serviço
No diretório do serviço desejado:
```bash
docker compose up -d

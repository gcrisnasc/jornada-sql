# 📂 Módulo 01: Fundamentos de SQL e Bancos de Dados

Este diretório contém a base conceitual e prática da minha jornada em SQL com PostgreSQL. Cada submódulo está estruturado para ligar a sintaxe técnica a problemas reais de negócios e preparação de dados.

---

## 🗺️ Trilha de Aprendizado

### Módulo 1: Conceitos de Bancos de Dados Relacionais
* **🧠 Anotações Conceituais:** O que é um SGBD, tabelas, chaves primárias (PK) e estrangeiras (FK), e por que estruturar dados dessa forma.
* **🔧 Conceitos Chave:** Modelo Entidade-Relacionamento (MER) e integridade referencial.
* **🎯 Questão de Objetivo:** Como a modelagem correta evita a duplicidade de dados e inconsistências em relatórios de BI.
* **✍️ Exercícios & Gabaritos:** Identificação de entidades e relacionamentos em cenários reais.

### Módulo 2: DDL (Data Definition Language) — Criando a Estrutura
* **🧠 Anotações Conceituais:** O porquê de tipar dados corretamente (INT, VARCHAR, DATE) e a importância das Constraints (`NOT NULL`, `UNIQUE`).
* **🔧 Tabela de Comandos Essenciais:** `CREATE TABLE`, `ALTER TABLE`, `DROP TABLE`.
* **🎯 Questão de Objetivo:** Traduzindo para o negócio: "Precisamos criar uma nova tabela no sistema para cadastrar nossos clientes sem permitir e-mails duplicados."
* **✍️ Exercícios & Gabaritos:** Criação e modificação de tabelas via script.

### Módulo 3: DML (Data Manipulation Language) — Alimentando os Dados
* **🧠 Anotações Conceituais:** Como alimentar o banco de forma segura e o impacto de um `UPDATE` ou `DELETE` sem a cláusula `WHERE`.
* **🔧 Tabela de Comandos Essenciais:** `INSERT INTO`, `UPDATE`, `DELETE`.
* **🎯 Questão de Objetivo:** Traduzindo para o negócio: "O cliente X mudou de endereço, precisamos atualizar o cadastro dele de forma isolada."
* **✍️ Exercícios & Gabaritos:** Inserção em massa e atualização segura de registros.

### Módulo 4: DQL (Data Query Language) — Consultando Informações
* **🧠 Anotações Conceituais:** A lógica de extração de dados, filtragem elementar e ordenação para análise de indicadores.
* **🔧 Tabela de Comandos Essenciais:** `SELECT`, `FROM`, `WHERE`, `ORDER BY`, `LIMIT`.
* **🎯 Questão de Objetivo:** Traduzindo para o negócio: "Quais foram os 10 clientes do estado de SP que se cadastraram este mês?"
* **✍️ Exercícios & Gabaritos:** Queries de filtragem e seleção de colunas específicas.

### Módulo 5: DCL & DTL (Control & Transaction) — Segurança e Consistência
* **🧠 Anotações Conceituais:** A importância de garantir permissões de acesso e o conceito de Transações (ACID) para evitar perda de dados em falhas.
* **🔧 Tabela de Comandos Essenciais:** `GRANT`, `REVOKE`, `BEGIN`, `COMMIT`, `ROLLBACK`.
* **🎯 Questão de Objetivo:** Traduzindo para o negócio: "Garantir que a transferência bancária só saia da conta A se ela efetivamente entrar na conta B."
* **✍️ Exercícios & Gabaritos:** Simulação de Rollback em falhas e controle de acessos de usuários.

---

## 🚀 Como Estou Praticando

1. **Teoria com IA:** Solicito o detalhamento conceitual de cada pilar técnico focando no impacto de negócio.
2. **Execução no pgAdmin 4:** Digito e executo cada comando manualmente para fixar a sintaxe no PostgreSQL 18.
3. **Validação:** Resolvo os exercícios de forma isolada antes de consultar as respostas sugeridas.

# 📂 Módulo 01: Fundamentos de SQL e Bancos de Dados

Este diretório reúne a base conceitual e prática da minha jornada em SQL com PostgreSQL. Cada submódulo liga a sintaxe técnica a problemas reais de negócio.

> 🌱 **Este módulo está em construção.** O cronograma abaixo é o meu plano de estudos: as seções e pastas serão preenchidas e linkadas conforme eu avançar nas aulas.

**Legenda de status:** ✅ Concluído · 🟡 Em andamento · ⚪ Planejado

---

## 📅 Cronograma do Módulo

| # | Tópico | Foco principal | Status |
|---|--------|----------------|--------|
| 1 | Conceitos de Bancos de Dados Relacionais | SGBD, tabelas, PK, FK, MER, normalização | 🟡 Em andamento |
| 2 | DDL (Data Definition Language) | `CREATE TABLE`, `ALTER TABLE`, `DROP TABLE`, constraints | 🟡 Iniciado |
| 3 | DML (Data Manipulation Language) | `INSERT INTO`, `UPDATE`, `DELETE` | ⚪ Planejado |
| 4 | DQL (Data Query Language) | `SELECT`, `FROM`, `WHERE`, `ORDER BY`, `LIMIT` | ⚪ Planejado |
| 5 | DCL & TCL (Controle e Transações) | `GRANT`, `REVOKE`, `BEGIN`, `COMMIT`, `ROLLBACK` | ⚪ Planejado |

---

## 📚 Aulas Publicadas

## 📚 Aulas Publicadas

| Aula | Tema | O que foi praticado | Link |
|------|------|---------------------|------|
| 01 | Introdução ao Banco de Dados Relacional | Entidades, cardinalidade, normalização (1FN a 3FN), PK e FK, famílias de comandos, `CREATE TABLE` no pgAdmin 4 | [Abrir aula 01](./aula-01) |
| 02 | *A publicar* | — | — |

> Cada nova aula ganha uma linha nesta tabela assim que for publicada.

---

## 🗺️ Trilha de Aprendizado (detalhamento)

### 1. Conceitos de Bancos de Dados Relacionais
- **🧠 Anotações:** O que é um SGBD, tabelas, chaves primárias (PK) e estrangeiras (FK), e por que estruturar dados dessa forma.
- **🔧 Conceitos-chave:** Modelo Entidade-Relacionamento (MER), cardinalidade e integridade referencial.
- **🎯 Questão de objetivo:** Como a modelagem correta evita duplicidade de dados e inconsistências em relatórios de BI.
- **✍️ Exercícios:** Identificação de entidades e relacionamentos em cenários reais.

### 2. DDL: Criando a Estrutura
- **🧠 Anotações:** Por que tipar os dados corretamente (`INT`, `VARCHAR`, `DATE`) e a importância das constraints (`NOT NULL`, `UNIQUE`, `CHECK`).
- **🔧 Comandos essenciais:** `CREATE TABLE`, `ALTER TABLE`, `DROP TABLE`.
- **🎯 Questão de objetivo:** "Precisamos criar uma nova tabela para cadastrar clientes sem permitir e-mails duplicados."
- **✍️ Exercícios:** Criação e modificação de tabelas via script.

### 3. DML: Alimentando os Dados
- **🧠 Anotações:** Como alimentar o banco com segurança e o impacto de um `UPDATE` ou `DELETE` sem a cláusula `WHERE`.
- **🔧 Comandos essenciais:** `INSERT INTO`, `UPDATE`, `DELETE`.
- **🎯 Questão de objetivo:** "O cliente X mudou de endereço, precisamos atualizar o cadastro dele de forma isolada."
- **✍️ Exercícios:** Inserção em massa e atualização segura de registros.

### 4. DQL: Consultando Informações
- **🧠 Anotações:** A lógica de extração de dados, filtragem elementar e ordenação para análise de indicadores.
- **🔧 Comandos essenciais:** `SELECT`, `FROM`, `WHERE`, `ORDER BY`, `LIMIT`.
- **🎯 Questão de objetivo:** "Quais foram os 10 clientes do estado de SP que se cadastraram este mês?"
- **✍️ Exercícios:** Consultas de filtragem e seleção de colunas específicas.

### 5. DCL & TCL: Segurança e Consistência
- **🧠 Anotações:** A importância das permissões de acesso e o conceito de transações (ACID) para evitar perda de dados em falhas.
- **🔧 Comandos essenciais:** `GRANT`, `REVOKE`, `BEGIN`, `COMMIT`, `ROLLBACK`.
- **🎯 Questão de objetivo:** "Garantir que a transferência bancária só saia da conta A se ela efetivamente entrar na conta B."
- **✍️ Exercícios:** Simulação de rollback em falhas e controle de acesso de usuários.

---

## 🚀 Como Estou Praticando

1. **Teoria com IA:** Peço o detalhamento conceitual de cada pilar técnico focando no impacto de negócio, e depois reescrevo com as minhas palavras.
2. **Execução no pgAdmin 4:** Digito e executo cada comando manualmente para fixar a sintaxe no PostgreSQL 18.
3. **Validação:** Resolvo os exercícios de forma isolada antes de consultar as respostas sugeridas.
4. **Registro dos erros:** Anoto o que errei e como corrigi, porque aprendo muito com isso.

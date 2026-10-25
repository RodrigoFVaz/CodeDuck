# 🐥 Codeduck — Sistema de Gestão (Projeto Académico)

Este repositório contém o modelo de base de dados **Codeduck**, desenvolvido como parte do meu percurso académico em **Cibersegurança no ISTEC**.  
O objetivo é demonstrar competências em:

- Modelação de bases de dados  
- Normalização  
- Relações entre entidades  
- Boas práticas SQL  
- Organização de projetos técnicos  

---

## 🐥 O que é o CodeDuck?

CodeDuck é um projeto académico, cujo, a ideia era criar um servidor de gestão de Websites, ou seja, a "CodeDuck" iria guardar websites no seu servidor e cuidar destes websites a nível de cibersegurança. Onde um cliente poderia ter mais do que um site e por isso nas tabelas existe um interligação "User <-> Site".

---

## 🗄️ Modelo Relacional

O sistema inclui as seguintes entidades:

- **tb_Users** — Gestão de utilizadores
- **tb_Login** — Autenticação e segurança
- **tb_Site** — Sites associados ao utilizador
- **tb_MetodoPagamento** — Métodos de pagamento disponíveis
- **tb_Contratos** — Contratos entre utilizadores e serviços

---

## 🧱 Script SQL

O ficheiro `schema.sql` contém:

✅ Chaves primárias e estrangeiras  
✅ Cascading para integridade referencial  
✅ Campos normalizados  
✅ Charset `utf8mb4`  
✅ Boas práticas de segurança (ex.: tamanho de senha para hashes)

---

## 🎓 Colegas de Trabalho 
- <a href="https://www.github.com/RodrigoFVaz">Rodrigo Vaz</a>
- Tiago Rodrigues
- <a href="https://www.github.com/CadelDavid">David Cadel</a>

---

## 🚀 Objetivo
Portfólio académico e profissional, demonstrando a minha evolução na área de **Cibersegurança**, com foco em:

- Estruturação de sistemas  
- Segurança de dados  
- Boas práticas SQL  
- Organização de projetos técnicos  

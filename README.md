# GarageFlow

> Sistema de gestão para oficinas mecânicas.

O **GarageFlow** é uma aplicação desenvolvida para centralizar a operação de uma oficina mecânica, abrangendo clientes, veículos, serviços, peças, estoque, ordens de serviço, orçamentos, pagamentos e histórico operacional.

O projeto foi desenvolvido como um produto completo, desde a definição das regras de negócio até a implementação da API e da aplicação web.

---

## 📌 Sobre o projeto

O sistema foi projetado para substituir processos descentralizados, como planilhas, mensagens e controles manuais, por uma operação centralizada e rastreável.

### Principais funcionalidades

* 👤 Gestão de usuários, grupos e permissões
* 👥 Gestão de clientes
* 🚗 Gestão de veículos
* 🔧 Catálogo de serviços
* ⚙️ Catálogo de peças
* 📦 Controle e movimentação de estoque
* 📋 Ordens de serviço
* 💰 Orçamentos
* 💳 Pagamentos e abatimentos
* 🔄 Interrupção e regularização de serviços
* 📜 Histórico operacional
* 🚘 Controle de entrega de veículos

---

## 🏗️ Arquitetura

```text
┌─────────────────────┐
│                     │
│   Vue.js Frontend   │
│                     │
└──────────┬──────────┘
           │
           │ REST API
           ▼
┌─────────────────────┐
│                     │
│   Django Backend    │
│                     │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│     PostgreSQL      │
└─────────────────────┘
```

---

## 📚 Repositórios

### Backend

API REST responsável pelas regras de negócio, autenticação, autorização, persistência e processamento das operações.

➡️ [garageflow-backend]()

### Frontend

Aplicação web responsável pela interface e interação dos usuários com o sistema.

➡️ [garageflow-frontend]()

---

## 🛠️ Tecnologias

### Backend

* Python
* Django
* Django REST Framework
* PostgreSQL
* Docker

### Frontend

* Vue.js
* JavaScript / TypeScript
* [Adicionar bibliotecas utilizadas]

---

## 🧠 Principais desafios técnicos

O projeto possui foco especial em regras de negócio, consistência e integridade dos dados.

Entre os principais desafios estão:

* Controle de permissões baseado em grupos
* Histórico imutável de operações
* Preservação de valores históricos de serviços e peças
* Reserva e consumo de estoque
* Controle de concorrência nas reservas
* Fluxos de aprovação e rejeição de orçamento
* Ordens de serviço complementares
* Interrupção e regularização de serviços
* Controle financeiro com pagamentos e abatimentos
* Regras de consistência para entrega do veículo

---

## 🗺️ Status do projeto

🚧 **Em desenvolvimento**

O projeto está sendo desenvolvido incrementalmente, começando pela API e posteriormente integrando a aplicação frontend.

---

## 📖 Documentação

A documentação será expandida conforme o desenvolvimento do projeto.

* [Backend](SEU-LINK-BACKEND)
* [Frontend](SEU-LINK-FRONTEND)

---

## 👨‍💻 Autor

**Jean França**

Software Developer

[LinkedIn](www.linkedin.com/in/jean-franca) · [GitHub]()

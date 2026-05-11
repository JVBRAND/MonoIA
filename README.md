# 🤖 MonoIA — Chatbot de Atendimento para Cartão de Crédito

O MonoIA é um chatbot de atendimento ao cliente desenvolvido para simular o suporte de um cartão de crédito. O sistema permite que o usuário consulte sua fatura, limite, status do cartão, parcelas e senha, além de realizar atualizações e exclusão de conta, tudo via linguagem natural.

---

## 👥 Participantes

| João Victor Brandão | 2359197 |
| Victor Borges Quintella | 2544963 |
| Kathleen Aquino | 2364196 |
| Lucas Costa Pereira | 2361186 |

**Disciplina:** Inteligência Artificial

---

## 🚀 Tecnologias Utilizadas

- **Python 3** — linguagem principal do backend
- **Flask** — framework web para criação da API REST
- **Flask-CORS** — suporte a requisições entre frontend e backend
- **SQLite** — banco de dados relacional para armazenamento dos clientes
- **HTML, CSS e JavaScript** — interface do usuário (frontend)

---

## ⚙️ Funcionalidades

- 🔐 Login por CPF
- 💰 Consulta de fatura atual
- 💳 Consulta de limite disponível
- 🔒 Verificação de bloqueio do cartão
- 📦 Consulta de parcelamentos
- 🔑 Orientação para troca de senha
- ✏️ Atualização de fatura e limite via chat
- 🗑️ Exclusão de conta com confirmação

---

## 🗂️ Estrutura do Projeto

MonoIA
├── app.py          # Rotas e lógica principal do chatbot
├── crud.py         # Operações com o banco de dados
├── database.py     # Criação e população do banco
├── clientes.db     # Banco de dados SQLite
├── index.html      # Interface do usuário
├── perguntas.csv   # Base de perguntas por categoria
└── respostas.json  # Base de respostas por categoria
```

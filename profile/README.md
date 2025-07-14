# 🧠 Ferramenta Ágil de Estimativa de Esforço com IA

**Uma aplicação web inteligente para planejamento ágil com apoio de Inteligência Artificial.**

---

## 📌 Visão Geral

Esta ferramenta centraliza o processo de estimativa de esforço em projetos ágeis. Com módulos para gerenciamento de projetos, equipes e sessões de *Planning Poker*, a aplicação incorpora uma IA para sugerir estimativas com base em histórico e características dos projetos.

**Principais Recursos:**

- Cadastro de projetos, tarefas e equipes
- Sessões virtuais de *Planning Poker*
- Sugestões de esforço com IA (Google Gemini)
- Histórico de estimativas para análise
- Interface moderna e responsiva

---

## 🧑‍💻 Histórias de Usuário

### 📁 Módulo de Projetos e Tarefas

- Como **Gerente de Projeto**, quero cadastrar, visualizar, editar e excluir projetos e tarefas.
- Como **Gerente de Projeto**, quero organizar tarefas por categorias.
- Como **Gerente de Projeto**, quero uma visão geral das tarefas de um projeto.

### 👥 Módulo de Equipes e Usuários

- Como **Gerente de Projeto**, quero cadastrar membros da equipe e associá-los aos projetos.
- Como **Membro da Equipe**, quero criar conta, fazer login e visualizar projetos e equipes.

### 🃏 Módulo de Planning Poker

- Como **Gerente de Projeto**, quero iniciar sessões de *Planning Poker* para estimar tarefas com a equipe.
- Como **Membro da Equipe**, quero votar usando a sequência de Fibonacci.
- Como **Gerente de Projeto**, quero visualizar votos, calcular média e salvar estimativas no histórico.

### 🤖 Módulo de Predição de Esforço (IA)

- Como **Gerente de Projeto**, quero receber uma **sugestão automática de esforço** baseada no tipo de projeto, equipe e categoria.
- Quero também **analisar o histórico** de estimativas anteriores para apoiar a tomada de decisão.

---

## ⚙️ Stack Tecnológica

| Camada      | Tecnologia                         |
|-------------|-------------------------------------|
| Backend     | Python (FastAPI ou Django REST)     |
| Frontend    | JavaScript (React ou Vue.js)        |
| Banco de Dados | PostgreSQL                      |
| Ambiente    | Docker                             |
| IA          | API do Google Gemini                |
| Versionamento | Git + GitHub Kanban              |

---

## 🧑‍🤝‍🧑 Equipe do Projeto

### 🎯 Scrum Master
- Rubson Lima — `rubson.lima@ufrpe.br`

### 🛠️ Backend
Responsáveis por API, banco de dados e integração com IA:

- **Edivaldo Neto**
- **Marcelo Maia** — `marcelo.maia@ufrpe.br`

### 🎨 Frontend
Responsáveis pela interface e consumo da API:

- **Mateus Rodrigo** — `mateusrodrigo9122@gmail.com`
- **José Edson Sebastião** — `joseedson.sebastiao@ufrpe.br`

---

## 🗂️ Organização e Planejamento

### 📋 Backlog no GitHub

Utilizaremos o **Kanban Board do GitHub** para organizar o trabalho em 5 sprints semanais. Cada tarefa será registrada como *issue*, com labels para categoria, prioridade e sprint.

| Sprint | Objetivo Principal                              |
|--------|--------------------------------------------------|
| 1      | Infraestrutura: Docker, Auth, estrutura inicial  |
| 2      | Cadastro e visualização de projetos e tarefas    |
| 3      | Módulo de Planning Poker                         |
| 4      | Módulo de IA e Histórico                         |
| 5      | Refino, testes e deploy                          |

---

### 📋 Relatório completo:
 - Frontend: [clique aqui](https://github.com/Projeto-Estimativa-de-Esforco-com-IA/frontend/tree/main/front/docs)
 - Backend:  [clique aqui]()

## 🚀 Primeiros Passos

### 1. Clone o repositório frontend/backend

### 2. Suba o ambiente com Docker

### 3. Acesse o Frontend

### 4. API Backend

## 🧠 Como Funciona a IA
- O modelo de IA utiliza o Google Gemini para prever o esforço com base em:

   - Tipo do projeto

   - Categoria das tarefas

   - Tamanho e composição da equipe

   - Estimativas passadas

- As estimativas geradas servem como sugestão para apoio à decisão antes do Planning Poker.

## 📈 Métricas e Análises Futuras
 - Precisão da IA nas previsões de esforço

 - Comparação entre estimativas humanas e automáticas

 - Histórico visual de tarefas estimadas

✅ Contribuindo
 - Contribuições são bem-vindas! Para colaborar:

 - Crie um fork

 - Crie uma branch com sua feature: git checkout -b feature/nome-da-feature

 - Commit suas alterações: git commit -m 'feat: nova funcionalidade'

 - Push para a branch: git push origin feature/nome-da-feature

 - Abra um Pull Request

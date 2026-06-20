# 📱 Agenda de Tarefas em Flutter

Este projeto é uma aplicação mobile desenvolvida em Flutter com o objetivo de simular um sistema de agenda de tarefas diárias, contendo funcionalidades de login, cadastro, calendário e gerenciamento de tarefas.

---

## 🚀 Funcionalidades

- 🔐 Tela de Login e Cadastro (simulado localmente)
- 📅 Calendário interativo para seleção de datas
- 📝 Adição de tarefas por dia
- ❌ Remoção de tarefas
- ✅ Marcação de tarefas como concluídas
- 🔃 Ordenação automática:
  - Tarefas pendentes aparecem primeiro
  - Tarefas concluídas aparecem depois
  - Ambas em ordem alfabética
- 🎨 Interface moderna com gradiente e design personalizado

---

## 📸 Screenshots do Projeto

> Adicione aqui os prints solicitados pelo professor

### Tela de Login
(Insira imagem aqui)

### Tela de Calendário
(Insira imagem aqui)

### Tela de Lista de Tarefas
(Insira imagem aqui)

---

## 🛠️ Tecnologias Utilizadas

- Flutter
- Dart
- Material Design
- table_calendar (calendário)
- google_fonts (estilização de texto)

---

## 📦 Dependências

```yaml
dependencies:
  flutter:
    sdk: flutter
  table_calendar: ^3.2.0
  google_fonts: ^8.1.0

---

## 📂 Estrutura do Projeto

lib/
│
├── main.dart
│
├── models/
│   └── tarefa.dart
│
├── screens/
│   ├── login_screen.dart
│   ├── cadastro_screen.dart
│   ├── calendario_screen.dart
│   └── tarefas_screen.dart
│
└── widgets/

---

## 🎯 Objetivo do Projeto

Este projeto foi desenvolvido com fins acadêmicos para praticar:

- Navegação entre telas no Flutter
- Manipulação de estado
- Listas dinâmicas
- Organização de código em camadas (models, screens)
- Uso de widgets interativos
- UI/UX com Flutter

---

## ⚙️ Regras de Negócio

- Cada tarefa pertence a uma data específica
- Tarefas iniciam como “pendentes”
- Usuário pode marcar/desmarcar como concluída
- Ordenação automática:
- Pendentes primeiro
- Concluídas depois
- Ordem alfabética dentro de cada grupo

---

## ✨ Melhorias Futuras
- Integração com Firebase
- Autenticação real de usuários
- Persistência de dados local (SQLite ou Hive)
- Notificações de tarefas
- Edição de tarefas

---
## 👩‍💻 Desenvolvido por
- Jullia Karolina de Paula
- julliakarolinadev@gmail.com

Projeto acadêmico desenvolvido em Flutter para fins educacionais.

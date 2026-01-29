# 📱 IPConnect - Sistema de Gestão Académica

Bem-vindo ao repositório oficial do IPConnect. Este projeto integra uma aplicação Android e um Painel Web através de uma API em PHP.

## 🗺️ Roadmap de Desenvolvimento 

O projeto foi construído por fases para garantir a integridade dos dados e a segurança:

### 🏁 Fase 1: Arquitetura e Backend
- Modelação da Base de Dados MySQL (`utilizadores`, `horarios`, `cursos`).
- Desenvolvimento da **API em PHP** para comunicação JSON.
- Testes de conexão local via XAMPP.

### 📱 Fase 2: Aplicação Android
- Criação do layout móvel no Android Studio.
- Integração com a API para login e visualização de horários.
- Leitura de JSON para mostrar dados em tempo real.

### 💻 Fase 3: Painel Administrativo Web (SaaS)
- Desenvolvimento do Dashboard para gestão de conteúdos.
- Implementação de **Sidebar Fixa** e **Modais** para UX moderna.
- Funcionalidades de segurança: Logout, Alteração de Senha e Remoção de Utilizadores.

### 🚀 Fase 4: Integração Final e Alertas
- Sistema de **Alertas em Tempo Real** (Admin escreve -> App recebe).
- Sincronização final entre Web e Mobile.

---
## 📂 Estrutura do Repositório
- `/app`: Código fonte Android (Java/Kotlin).
- `/web`: Painel Administrativo e API (PHP/CSS).
- `/sql`: Script de instalação da Base de Dados.

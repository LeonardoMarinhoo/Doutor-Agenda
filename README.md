# Doutor Agenda

<p align="center">
  <img src="public/logo.svg" alt="Doutor Agenda Logo" width="120"/>
</p>

<p align="center">
  Plataforma de agendamento médico para clínicas e consultórios.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Next.js-15-black?style=for-the-badge&logo=next.js"/>
  <img src="https://img.shields.io/badge/TypeScript-5-blue?style=for-the-badge&logo=typescript"/>
  <img src="https://img.shields.io/badge/Tailwind_CSS-4-38bdf8?style=for-the-badge&logo=tailwindcss"/>
  <img src="https://img.shields.io/badge/PostgreSQL-DrizzleORM-4CAF50?style=for-the-badge&logo=postgresql"/>
  <img src="https://img.shields.io/badge/Stripe-Pagamentos-635BFF?style=for-the-badge&logo=stripe"/>
</p>

---

## Sobre o Projeto

O **Doutor Agenda** é uma aplicação full-stack para gerenciamento de clínicas médicas. Permite cadastrar médicos e pacientes, controlar disponibilidade de horários e realizar agendamentos de consultas, tudo com autenticação segura e plano de assinatura integrado.

---

## Screenshots

> Em breve

---

## Tecnologias

- **[Next.js 15](https://nextjs.org/)** — Framework React com App Router
- **[TypeScript](https://www.typescriptlang.org/)** — Tipagem estática
- **[Tailwind CSS 4](https://tailwindcss.com/)** — Estilização
- **[shadcn/ui](https://ui.shadcn.com/)** — Componentes de interface
- **[Drizzle ORM](https://orm.drizzle.team/)** — ORM para PostgreSQL
- **[Better Auth](https://www.better-auth.com/)** — Autenticação (e-mail/senha e Google)
- **[Stripe](https://stripe.com/)** — Pagamentos e assinaturas
- **[React Hook Form](https://react-hook-form.com/)** + **[Zod](https://zod.dev/)** — Formulários e validação
- **[TanStack Query](https://tanstack.com/query)** — Gerenciamento de estado assíncrono

---

## Funcionalidades

- Autenticação com e-mail/senha e login social com Google
- Cadastro e gerenciamento de clínica
- Cadastro, edição e remoção de médicos com controle de disponibilidade
- Cadastro, edição e remoção de pacientes
- Criação, listagem e remoção de agendamentos
- Dashboard com estatísticas e gráficos
- Plano de assinatura via Stripe

---

## Como Rodar Localmente

### Pré-requisitos

- Node.js 18+
- PostgreSQL (recomendado: [Neon](https://neon.tech))
- Conta no [Stripe](https://stripe.com)
- Credenciais OAuth do [Google](https://console.cloud.google.com)

### Instalação

```bash
# Clone o repositório
git clone https://github.com/LeonardoMarinhoo/Doutor-Agenda.git
cd Doutor-Agenda

# Instale as dependências
npm install
```

### Variáveis de Ambiente

Crie um arquivo `.env` na raiz do projeto com base no `.env.example`:

```bash
cp .env.example .env
```

Preencha as variáveis no arquivo `.env`.

### Banco de Dados

```bash
# Rode as migrations
npx drizzle-kit push
```

### Rodando o Projeto

```bash
npm run dev
```

Acesse [http://localhost:3000](http://localhost:3000).

---

## Planejamento

### Semana 01: Setup do Projeto

- [x] Inicialização do projeto Next.js
- [x] Configuração de ferramentas (ESlint, Prettier, Tailwind)
- [x] Configuração do Drizzle e banco de dados
- [x] Configuração do shadcn/ui

### Semana 02: Autenticação e Configurações do Estabelecimento

- [x] Tela de login e criação de conta
- [x] Login com e-mail e senha
- [x] Login com o Google
- [x] Fundamentos do Next.js (Rotas, Páginas, Layouts)
- [x] Criação de clínica

### Semana 03: Gerenciamento de Profissionais e Disponibilidade

- [x] Sidebar e Route Groups
- [x] Página de médicos
- [x] Criação de médicos & NextSafeAction
- [x] Listagem de médicos
- [x] Atualização de médicos
- [x] Deleção de médicos

### Semana 04: Gerenciamento de Pacientes e Agendamentos

- [x] Criação de pacientes
- [x] Edição de pacientes
- [x] Listagem de pacientes
- [x] Deleção de pacientes
- [x] Criação de agendamentos
- [x] Listagem de agendamentos
- [x] Deleção de agendamentos

---

## Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

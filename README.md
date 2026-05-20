# 🫀 CoraApp — Aplicação Web

> Aplicação web de acompanhamento pós-cirúrgico para pacientes submetidos a cirurgias vasculares. Desenvolvida pela Universidade Federal da Bahia (UFBA) em parceria com o HUPES (Salvador/BA) e o Hospital Felício Rocho (Belo Horizonte/MG).

> 🔒 **Repositório privado** — este repositório contém apenas a documentação do projeto. O código-fonte é privado por questões de segurança e privacidade dos dados de pesquisa.

🌐 **Acesso:** [saudecora.com.br/coraapp](https://www.saudecora.com.br/coraapp)

---

## Sobre

Este repositório contém a **aplicação web** do CoraApp — o sistema principal de pesquisa, onde pacientes acessam orientações educativas, assinam o TCLE, enviam fotos da ferida cirúrgica e respondem questionários ao longo de até 90 dias após a cirurgia.

A aplicação é acessada pelo domínio [saudecora.com.br](https://www.saudecora.com.br) via máscara de endereço. O site institucional e o projeto mobile são repositórios separados.

---

## Stack tecnológica

### Core

| Tecnologia | Versão | Função |
|---|---|---|
| [Next.js](https://nextjs.org/) | 16.0.10 | Framework React com SSR/SSG e roteamento |
| [React](https://react.dev/) | 19.1.0 | Biblioteca de UI |
| [TypeScript](https://www.typescriptlang.org/) | 5.x | Tipagem estática |

### Backend & Banco de dados

| Tecnologia | Versão | Função |
|---|---|---|
| [Supabase](https://supabase.com/) | 2.100.0 | Banco de dados PostgreSQL, autenticação e storage |
| [@supabase/ssr](https://supabase.com/docs/guides/auth/server-side) | 0.9.0 | Integração Supabase com SSR no Next.js |

### Estilização

| Tecnologia | Versão | Função |
|---|---|---|
| [Tailwind CSS](https://tailwindcss.com/) | 4.1.9 | Utility-first CSS framework |
| [tailwind-merge](https://github.com/dcastil/tailwind-merge) | 3.3.1 | Merge de classes Tailwind sem conflito |
| [class-variance-authority](https://cva.style/) | 0.7.1 | Variantes de componentes tipadas |
| [clsx](https://github.com/lukeed/clsx) | 2.1.1 | Utilitário para classes condicionais |
| [tailwindcss-animate](https://github.com/jamiebuilds/tailwindcss-animate) | 1.0.7 | Animações CSS via Tailwind |

### Componentes UI

| Biblioteca | Função |
|---|---|
| [Radix UI](https://www.radix-ui.com/) | Componentes acessíveis e sem estilo |
| [shadcn/ui](https://ui.shadcn.com/) | Sistema de componentes sobre Radix UI + Tailwind |
| [Lucide React](https://lucide.dev/) | Ícones SVG |
| [cmdk](https://cmdk.paco.me/) | Command palette |
| [Sonner](https://sonner.emilkowal.ski/) | Notificações toast |
| [Vaul](https://vaul.emilkowal.ski/) | Drawer acessível |

### Formulários e validação

| Biblioteca | Versão | Função |
|---|---|---|
| [React Hook Form](https://react-hook-form.com/) | 7.60.0 | Gerenciamento de formulários |
| [Zod](https://zod.dev/) | 3.25.76 | Schema validation e tipagem |
| [@hookform/resolvers](https://github.com/react-hook-form/resolvers) | 3.10.0 | Integração RHF + Zod |
| [input-otp](https://github.com/guilhermerodz/input-otp) | 1.4.1 | Input OTP |

### Dados e visualização

| Biblioteca | Versão | Função |
|---|---|---|
| [Recharts](https://recharts.org/) | 2.15.4 | Gráficos e visualização de dados |
| [date-fns](https://date-fns.org/) | 4.1.0 | Manipulação de datas |
| [react-day-picker](https://react-day-picker.js.org/) | 9.8.0 | Seletor de datas |

### UX & Layout

| Biblioteca | Versão | Função |
|---|---|---|
| [Embla Carousel](https://www.embla-carousel.com/) | 8.5.1 | Carrossel acessível |
| [react-resizable-panels](https://github.com/bvaughn/react-resizable-panels) | 2.1.7 | Painéis redimensionáveis |

### Infraestrutura

| Serviço | Função |
|---|---|
| [Vercel](https://vercel.com/) | Hospedagem, deploy contínuo e CDN |
| [@vercel/analytics](https://vercel.com/analytics) | Analytics de uso |

---

## Funcionalidades

- 📋 Apresentação e aceite do TCLE por hospital (HUPES e HFR)
- 🔔 Questionários e notificações em datas pós-cirúrgicas agendadas
- 📷 Envio de fotos da ferida cirúrgica
- 👤 Visualização de perfil e dados cirúrgicos cadastrados
- 💬 Contato direto com a equipe do projeto
- 📚 Conteúdo educativo de orientação em saúde
- 🔐 Autenticação e controle de acesso via Supabase
- ⚙️ Gerenciamento de conta (atualização de e-mail e senha de login)
- ♿ Componentes acessíveis (Radix UI)

---

## Aspectos éticos e de privacidade

O CoraApp foi aprovado pelos Comitês de Ética em Pesquisa do HUPES e do HFR, em conformidade com a Resolução CNS nº 466/12. Todos os dados são coletados com consentimento explícito, codificados sem identificação direta, e não são compartilhados com terceiros para fins comerciais. Para mais detalhes, acesse [saudecora.com.br](https://www.saudecora.com.br) .

---

## Contato

- 📧 alessandramartins@saudecora.com.br

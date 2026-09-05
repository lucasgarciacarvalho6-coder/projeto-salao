# 💇‍♀️ L'EQUIPE - Sistema de Gestão e Agendamentos de Salão de Beleza

> Plataforma web moderna e sofisticada desenvolvida para o salão de beleza **L'EQUIPE**, unindo identidade visual de alto padrão, experiência de usuário intuitiva e um painel administrativo seguro.

---

## 🚀 Sobre O Projeto

O projeto foi construído sob medida para otimizar a experiência das clientes e a gestão interna do salão. A aplicação conta com um site institucional imersivo (Dark Mode de luxo), um **calendário interativo inteligente** que restringe automaticamente os dias e horários de funcionamento, além de um **Painel Administrativo protegido por autenticação** em tempo real.

---

## 🛠️ Tecnologias e Ferramentas Utilizadas

Este projeto foi desenvolvido utilizando tecnologias modernas do ecossistema JavaScript/TypeScript:

* **Next.js (App Router)**: Framework React moderno para renderização híbrida, otimização de rotas e alta performance.
* **React**: Biblioteca JavaScript para construção de interfaces de usuário reativas baseadas em componentes.
* **TypeScript**: Superset do JavaScript que adiciona tipagem estática para maior segurança e escalabilidade do código.
* **Tailwind CSS**: Framework CSS utilitário para estilização rápida, responsiva e com design system customizado.
* **Supabase**: Plataforma backend-as-a-service (BaaS) baseada em PostgreSQL utilizada para banco de dados relacional e autenticação segura (Supabase Auth).

---

## ✨ Funcionalidades Principais

* **Identidade Visual Sofisticada**: Estética minimalista e elegante em tons de preto, cinza e branco.
* **Links de Acesso Rápido**: Atalhos flutuantes e direcionamentos diretos para o Instagram e WhatsApp do salão.
* **Calendário de Agendamento Inteligente**: Exibição dinâmica dos meses com filtro automático de dias úteis (terça a sábado) e horários das 08:00 às 18:00.
* **Painel Administrativo Restrito (/admin)**: Tela de login segura para validação de credenciais e listagem em tempo real de todos os horários marcados pelas clientes.

---

## 📂 Estrutura do Projeto

- salao-app/
  - app/
    - admin/page.tsx (Painel administrativo protegido)
    - globals.css (Estilos globais e Tailwind)
    - layout.tsx (Layout raiz e metadados)
    - page.tsx (Página principal e calendário)
  - lib/
    - supabase.ts (Configuração do cliente Supabase)
  - public/
    - logo.png (Ativos estáticos do salão)
  - .env.local (Variáveis de ambiente protegidas)

---

## ⚙️ Como Executar o Projeto Localmente

1. Clone o repositório e acesse a pasta do projeto digitando: cd salao-app
2. Instale todas as dependências executando: npm install
3. Configure as variáveis de ambiente criando um arquivo .env.local na raiz contendo:
   NEXT_PUBLIC_SUPABASE_URL=sua_url_do_supabase_aqui
   NEXT_PUBLIC_SUPABASE_ANON_KEY=sua_chave_anon_aqui
4. Inicie o servidor de desenvolvimento executando: npm run dev
5. Acesse http://localhost:3000 no seu navegador.

---

## 👨‍💻 Desenvolvido por

* **Lucas Willian Garcia Carvalho**

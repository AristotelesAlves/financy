<p align="center">
  <img width="996" height="532" alt="image" src="https://github.com/user-attachments/assets/ca02f108-3d4b-4b05-9e09-63e8ab6277f2" />
</p>

<h1 align="center">Financy Community</h1>

<p align="center">
  Plataforma front end desenvolvida com <strong>Vue.js 3</strong>, <strong>TypeScript</strong> e <strong>Tailwind CSS</strong>, com foco em aprendizado colaborativo e boas práticas de desenvolvimento em equipe.
</p>

<div align="center">

![Vue.js](https://img.shields.io/badge/vuejs-%2335495e.svg?style=for-the-badge&logo=vuedotjs&logoColor=%234FC08D)
![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
![PNPM](https://img.shields.io/badge/pnpm-%234a4a4a.svg?style=for-the-badge&logo=pnpm&logoColor=f69220)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white)

</div>

---

## 📌 Sobre o Projeto

O **Financy Community** é um projeto front end desenvolvido em equipe com o objetivo de evoluir conhecimentos técnicos e práticos em desenvolvimento web moderno, seguindo fielmente o layout proposto no Figma.

---

## 🧱 Tecnologias Utilizadas

- Vue.js 3
- TypeScript
- Tailwind CSS
- Vite
- pnpm  

---

## 🧱 Arquitetura do Projeto

A estrutura do projeto foi pensada para ser escalável, organizada e de fácil manutenção.

```bash
src/
├─ assets/                    # Imagens, ícones, fontes
│
├─ components/                # Componentes reutilizáveis
│  ├─ ui/                     # Design system (sem lógica)
│  │  # Button, Input, Modal, Tooltip...
│  │
│  ├─ layout/                 # Estrutura visual das páginas
│  │  # Header, Footer, Sidebar, Container
│  │
│  ├─ common/                 # Reutilizáveis com lógica leve
│  │  # Loader, EmptyState, Pagination, ErrorState
│  │
│  ├─ forms/                  # Componentes de formulário
│  │  # Form, Field, Select, Checkbox
│  │
│  └─ index.ts                # Barrel file de components
│
├─ pages/                     # Páginas (views / rotas)
│  ├─ _app/                   # Camada base da aplicação
│  │  ├─ AppLayout.vue        # Layout global
│  │  └─ AuthGuard.ts         # Guards globais (opcional)
│  │
│  ├─ auth/                   # Fluxo de autenticação
│  │  ├─ Login.page.vue
│  │  ├─ Register.page.vue
│  │  └─ ForgotPassword.page.vue
│  │
│  ├─ dashboard/              # Área principal logada
│  │  ├─ Dashboard.page.vue
│  │  └─ components/          # Componentes exclusivos do dashboard
│  │
│  ├─ errors/                 # Páginas de erro
│  │  ├─ NotFound.page.vue
│  │  └─ Forbidden.page.vue
│  │
│  └─ index.ts                # Export central (opcional)
│
├─ router/                    # Vue Router
│  ├─ index.ts                # Instância do router
│  ├─ routes.ts               # Definição das rotas
│  └─ guards.ts               # Guards de rota
│
├─ services/                  # Comunicação com APIs
│  ├─ api/
│  │  └─ http.ts              # Client HTTP configurado
│  ├─ auth.service.ts
│  └─ user.service.ts
│
├─ composables/               # Lógica reutilizável (Vue way)
│  # useAuth, useFetch, useTheme
│
├─ utils/                     # Helpers puros
│  # formatters, validators, storage
│
├─ constants/                 # Constantes e enums
│  # routes, roles, storageKeys
│
├─ styles/                    # Estilos globais
│  ├─ base.css
│  └─ utilities.css
│
├─ types/                     # Tipagens globais
│  # api, models, globals
│
├─ App.vue                    # Componente raiz
└─ main.ts                    # Bootstrap da aplicação


```

---

## 👥 Desenvolvedores

<p align="center">
  <a href="https://github.com/dwictor0">
    <img src="https://avatars.githubusercontent.com/dwictor0" width="120" alt="dwictor0" />
  </a>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://github.com/liviaaraujo-dev">
    <img src="https://avatars.githubusercontent.com/liviaaraujo-dev" width="120" alt="liviaaraujo-dev" />
  </a>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://github.com/aristotelesalves">
    <img src="https://avatars.githubusercontent.com/aristotelesalves" width="120" alt="aristotelesalves" />
  </a>
</p>

<p align="center">
  <strong>dwictor0</strong>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <strong>liviaaraujo-dev</strong>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <strong>aristotelesalves</strong>
</p>


---

## 🎯 Objetivos de Aprendizado

- Aprimorar conhecimentos em Vue.js 3 e TypeScript
- Utilizar Tailwind CSS para estilização moderna
- Aplicar boas práticas de arquitetura front end
- Trabalhar com componentização e roteamento
- Praticar Git e GitHub em ambiente colaborativo
- Simular um projeto real em equipe  

---

## 🚀 Como Rodar o Projeto

Este projeto utiliza pnpm como gerenciador de pacotes.

### Front end

```bash
pnpm install  
pnpm dev  
```

A aplicação estará disponível em:

http://localhost:5173

---

## 📄 Licença

Projeto desenvolvido para fins educacionais e colaborativos.

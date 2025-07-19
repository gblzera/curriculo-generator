# 🚀 Gerador de Currículos Profissionais

Um projeto Full-Stack completo que permite aos usuários criar, customizar e baixar currículos em formato PDF de forma rápida e intuitiva.

### ✨ [Link para acessar o gerador de currículos online](https://curriculo-generator-two.vercel.app/) ✨

---

## 📋 Descrição do Projeto

Esta aplicação foi construída do zero com o objetivo de solidificar conceitos de desenvolvimento web moderno, desde a criação de uma interface reativa com o React até a construção de uma API robusta com Node.js para lidar com a geração de documentos. O resultado é uma ferramenta funcional e com uma ótima experiência de usuário para a criação de currículos.

## ✅ Principais Funcionalidades

-   **Criação de Currículo:** Formulário completo e intuitivo dividido em seções (Dados Pessoais, Resumo, Experiência, Educação, Habilidades).
-   **Pré-visualização ao Vivo:** Todas as alterações feitas no formulário são refletidas instantaneamente na pré-visualização.
-   **Múltiplos Layouts:** O usuário pode escolher entre diferentes templates visuais (Moderno, Clássico, Minimalista).
-   **Customização Completa:**
    -   Modo Claro e Escuro (Dark/Light Mode) para a interface.
    -   Seletor de cor primária que afeta a aparência do currículo gerado.
    -   Edição e exclusão de itens de Experiência e Formação.
-   **Geração de PDF:** O backend utiliza Puppeteer para converter o currículo HTML em um arquivo PDF de alta qualidade para download.
-   **Persistência de Dados:** O formulário é salvo no `localStorage` do navegador, evitando que o usuário perca seu trabalho ao recarregar a página.
-   **Design Responsivo:** A interface se adapta perfeitamente a dispositivos móveis e tablets.
-   **Validação de Dados:** Validação no frontend e no backend para garantir a integridade dos dados.
-   **Testes Automatizados:** Testes básicos para o backend e frontend garantindo a estabilidade da aplicação.

## 🛠️ Tecnologias Utilizadas

#### **Frontend (Hospedado na Vercel)**
-   **React** (com Vite)
-   **React Context API** (para gerenciamento de estado global)
-   **Axios** (para requisições HTTP)
-   **Vitest** & **React Testing Library** (para testes de componentes)
-   **CSS** com Variáveis para Temas

#### **Backend (Hospedado na Render.com)**
-   **Node.js**
-   **Express.js** (para a criação da API RESTful)
-   **Puppeteer** (para a geração de PDFs a partir do Chromium)
-   **CORS** (para gerenciamento de permissões de origem)
-   **Jest** & **Supertest** (para testes de API)

## 📂 Estrutura do Projeto

```
/curriculo-generator
├── /backend        # Contém a API em Node.js/Express
│   ├── services/
│   ├── server.js
│   ├── package.json
│   └── README.md   # Documentação específica do backend
└── /frontend       # Contém a aplicação em React
    ├── src/
    │   ├── components/
    │   ├── context/
    │   └── App.jsx
    └── README.md   # Documentação específica do frontend
```

## 🚀 Como Executar o Projeto Localmente

**Pré-requisitos:** [Node.js](https://nodejs.org/en/) (versão 18 ou superior) instalado.

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/gblzera/curriculo-generator.git](https://github.com/gblzera/curriculo-generator.git)
    cd curriculo-generator
    ```

2.  **Inicie o Backend:**
    (Abra um terminal)
    ```bash
    cd backend
    npm install
    npm start
    ```
    *O servidor backend estará rodando em `http://localhost:3001`.*

3.  **Inicie o Frontend:**
    (Abra um **segundo** terminal)
    ```bash
    cd frontend
    npm install
    npm run dev
    ```
    *A aplicação frontend estará disponível em `http://localhost:5173` (ou outra porta indicada).*

## ✍️ Autor

Feito com dedicação por **Gabriel Henrique Kuhn Paz**.

-   GitHub: [@gblzera](https://github.com/gblzera)
-   LinkedIn: [Gabriel Kuhn](https://www.linkedin.com/in/gabriel-kuhn-347935324/)
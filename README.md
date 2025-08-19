# Meu Portfólio Interativo com Next.js

Este é um projeto de portfólio pessoal desenvolvido para demonstrar minhas habilidades em desenvolvimento front-end, com foco em React, Next.js e interatividade com a API de Canvas do HTML5. 

## 🚀 Descrição

O projeto consiste em duas páginas principais:

1.  **Página de Boas-Vindas (`/`)**: Uma tela de entrada interativa que simula um efeito de "raspadinha". O usuário é recebido com uma tela escura e um contador regressivo. Ele pode "raspar" a tela com o mouse ou o dedo (em dispositivos móveis) para revelar o conteúdo por baixo, ou simplesmente aguardar o contador chegar a zero para ser redirecionado automaticamente para a página do portfólio.

2.  **Página de Portfólio (`/portfolio`)**: A página principal que exibe meus projetos, habilidades e informações de contato. Foi desenhada com uma estética moderna e profissional, utilizando animações sutis para melhorar a experiência do usuário.

## ✨ Funcionalidades

- **Tela de Abertura Interativa**: Efeito de "raspadinha" implementado com a API de Canvas do HTML5.
- **Contador Regressivo e Redirecionamento Automático**: A página de boas-vindas redireciona para o portfólio após 5 segundos.
- **Design Responsivo**: A aplicação se adapta a diferentes tamanhos de tela, de desktops a dispositivos móveis.
- **Navegação Fixa**: Um cabeçalho de navegação fixo na página do portfólio permite fácil acesso às diferentes seções.
- **Seções do Portfólio**:
  - **Projetos**: Cards que destacam trabalhos e projetos realizados.
  - **Habilidades**: Uma grade que exibe minhas principais competências técnicas.
  - **Contato**: Um formulário para que os visitantes possam entrar em contato.
- **Animações de Entrada**: Efeitos de fade-in nos cards e seções para uma experiência de usuário mais fluida e agradável.

## 🛠️ Tecnologias Utilizadas

- **Next.js**: Framework React para produção, utilizado para renderização do lado do servidor (SSR) e geração de sites estáticos (SSG).
- **React**: Biblioteca JavaScript para construir interfaces de usuário.
- **TypeScript**: Superset do JavaScript que adiciona tipagem estática.
- **CSS Modules**: Para estilização local e componentizada, evitando conflitos de CSS.
- **HTML5 Canvas**: Utilizado para criar a interatividade da tela de "raspadinha".

## 🏃‍♂️ Como Executar o Projeto

Para executar este projeto localmente, siga os passos abaixo:

1.  **Clone o repositório:**

    ```bash
    git clone <URL_DO_REPOSITORIO>
    cd meu-projeto-genai
    ```

2.  **Instale as dependências:**

    ```bash
    npm install
    ```

3.  **Inicie o servidor de desenvolvimento:**

    ```bash
    npm run dev
    ```

4.  Abra http://localhost:3000 no seu navegador para ver a aplicação.

## 📂 Estrutura do Projeto

A estrutura de arquivos principal do projeto é a seguinte:

```
meu-projeto-genai/
├── pages/
│   ├── _app.tsx         # Componente principal da aplicação
│   ├── index.tsx        # Página de boas-vindas (raspadinha)
│   └── portfolio.tsx    # Página do portfólio
├── public/
│   └── images/          # Imagens estáticas usadas no projeto
└── styles/
    ├── globals.css      # Estilos globais
    ├── Welcome.module.css # Estilos para a página de boas-vindas
    └── Portfolio.module.css # Estilos para a página de portfólio
```

## 🎯 Objetivo

O principal objetivo deste projeto é servir como um cartão de visitas digital e interativo. Ele foi pensado para capturar a atenção de recrutadores, demonstrando não apenas competência no uso de LLMS para o desenvolvimento de projetos , mas também criatividade e atenção à experiência do usuário.

---

_Este projeto foi desenvolvido como parte de um processo de demonstração de habilidades para oportunidades de trabalho._

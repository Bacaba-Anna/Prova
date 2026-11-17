# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some Oxlint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Oxc](https://oxc.rs)
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/)

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the Oxlint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and Oxlint's TypeScript related rules in your project.

# Portal-Cursos

Aplicação web desenvolvida com React e Vite para a disciplina de Aplicativos Web (IFTO - Campus Palmas).

## Como executar o projeto

1. Instale as dependências do projeto:

```bash
npm install
Inicie o servidor local de desenvolvimento
Bash
npm run dev
Acesse no navegador o endereço exibido no terminal (geralmente http://localhost:5173).

A navegação entre as páginas Início e Cadastro foi implementada utilizando a biblioteca react-router, permitindo a troca de telas sem recarregar a página. Já a validação do formulário utiliza o hook useState para controlar os dados digitados e armazenar as mensagens de erro em tempo real. No envio do formulário, o preventDefault() bloqueia o recarregamento padrão enquanto a função validar() verifica o tamanho dos textos, o formato do e-mail, a seleção obrigatória do curso e a igualdade entre as senhas antes de exibir a confirmação.


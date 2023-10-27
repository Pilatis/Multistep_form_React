# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

- <h1 align="center">Entendendo o Código</h1>

- O código importa os componentes e bibliotecas necessários para criar o formulário, como GrFormNext, GrFormPrevious, FiSend, UserForm, ReviewForm, Thanks, Steps e useForm.
 
- O código usa duas variáveis de estado para armazenar os dados do formulário e o passo atual do formulário.

- Função updateFieldHandler: Esta função é usada para atualizar os dados do formulário quando o usuário digita algo em um campo.

- Array formComponents: Este array contém os componentes do formulário, um para cada passo.

- Hook useForm: Este hook é usado para gerenciar o estado do formulário, como o passo atual e se o formulário está no início ou no fim.

- Componente App: Este componente é o componente principal do formulário. Ele renderiza o cabeçalho do formulário, os passos do formulário, o componente do passo atual e as ações do formulário.

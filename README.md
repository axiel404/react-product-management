# Aero-Clean: Sistema de Gestão de Produtos

![Banner do Projeto](https://placehold.co/800x300/00cec9/FFFFFF?text=Aero-Clean&font=asap)

> Projeto Fullstack desenvolvido para o Módulo Intermediário do curso, focado na criação de um painel administrativo completo para gerenciamento de estoque, utilizando React e uma API externa.

---

### Sobre o Projeto

O **Aero-Clean** é um painel de controle (dashboard) que simula o sistema interno de uma loja online. Ele permite que um administrador gerencie o catálogo de produtos de forma simples e eficiente, realizando todas as operações essenciais de um e-commerce.

Este projeto foi construído em equipe, seguindo as melhores práticas de desenvolvimento, como o uso de Git/GitHub para versionamento, divisão de tarefas em branches e integração contínua através de Pull Requests.

---

### 🔧 Funcionalidades Implementadas

O sistema possui um **CRUD (Create, Read, Update, Delete)** completo para a gestão de produtos:

* **Listagem de Produtos (`Read`):** A página principal exibe todos os produtos cadastrados, buscando os dados em tempo real da API.
* **Cadastro de Produtos (`Create`):** Um formulário completo para adicionar novos itens ao catálogo, com validações e envio direto para a API.
* **Edição de Produtos (`Update`):** Uma página dinâmica que permite alterar as informações de um produto existente. O sistema identifica o produto pelo ID na URL.
* **Exclusão de Produtos (`Delete`):** Funcionalidade para remover produtos do estoque diretamente pela API.
* **Navegação Fluida (SPA):** Utiliza React Router para uma experiência de Single Page Application, onde a navegação entre as telas ocorre sem recarregar a página.

---

### 🛠️ Tecnologias Utilizadas

Este projeto foi construído com as seguintes tecnologias e ferramentas:

* **Front-End:**
    * [**React.js**](https://reactjs.org/) (com [**Vite**](https://vitejs.dev/))
    * [**Material-UI (MUI)**](https://mui.com/) para componentização e design
    * [**React Router DOM**](https://reactrouter.com/) para o sistema de rotas

* **Back-End (Simulado):**
    * [**MockAPI.io**](https://mockapi.io/) para criar e hospedar uma API RESTful para os dados dos produtos.
    * [**Axios**](https://axios-http.com/) para realizar as chamadas HTTP (requisições) para a API.

* **Ferramentas e Fluxo de Trabalho:**
    * **Git** e **GitHub** para controle de versão e trabalho em equipe.

---

### ⚙️ Como Rodar o Projeto Localmente

Para executar este projeto na sua máquina, siga os passos abaixo:

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/axiel404/react-product-management.git
    ```

2.  **Instale as dependências:**
    ```bash
    npm install
    ```

3.  **Inicie o servidor de desenvolvimento:**
    ```bash
    npm run dev
    ```

4.  Abra [http://localhost:5173](http://localhost:5173) no seu navegador para ver a aplicação.

---


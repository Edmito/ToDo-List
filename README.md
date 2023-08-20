# Lista de Tarefas em React - Projeto para Iniciantes

Este projeto é voltado para iniciantes que desejam aprender a construir uma aplicação web simples usando a biblioteca React. Neste projeto, você criará uma lista de tarefas interativa, permitindo adicionar, remover, filtrar, ordenar tarefas e completá-las.

## Pré-requisitos

Antes de começar, certifique-se de ter o Node.js instalado em sua máquina. Você pode baixá-lo e instalá-lo a partir do [site oficial do Node.js](https://nodejs.org/).

## Configuração do Projeto

1. Clone este repositório para o seu computador ou faça o download como arquivo ZIP.

2. Abra o terminal e navegue até o diretório do projeto.

3. Instale as dependências do projeto executando o seguinte comando:

```bash
npm install
```

## Estrutura do Projeto

O projeto possui a seguinte estrutura de diretórios e arquivos:

- `index.html`: Página HTML principal.
- `package-lock.json` e `package.json`: Arquivos de configuração do projeto.
- `src/`: Diretório contendo o código-fonte.
  - `App.css`: Estilos CSS para o componente App.
  - `App.jsx`: Componente principal da aplicação.
  - `components/`: Diretório contendo componentes reutilizáveis.
    - `Filter.jsx`: Componente de filtro de tarefas.
    - `Search.jsx`: Componente de busca de tarefas.
    - `Todo.jsx`: Componente para exibir tarefas individuais.
    - `TodoForm.jsx`: Componente para adicionar novas tarefas.
  - `img/`: Diretório contendo imagens.
    - `bg.jpg`: Imagem de fundo da página.
  - `main.jsx`: Arquivo de ponto de entrada da aplicação.

## Como Executar o Projeto

Após configurar o projeto e instalar as dependências, você pode executar a aplicação usando o seguinte comando:

```bash
npm run dev
```
Isso iniciará o servidor de desenvolvimento e abrirá a aplicação em seu navegador padrão. Agora você pode interagir com a lista de tarefas!

## Funcionalidades

- **Adicionar Tarefas:** Insira o nome da tarefa e clique no botão "Adicionar" para incluí-la na lista.
- **Remover Tarefas:** Clique no botão de X ao lado de uma tarefa para removê-la da lista.
- **Filtrar por Descrição:** Utilize o componente de filtro para exibir apenas as tarefas que contêm determinada descrição.
- **Ordenar Ascendente/Descendente:** Clique nos botões de ordenação para reorganizar as tarefas em ordem alfabética.
- **Completar Tarefas:** Clique no botão de Completar para Completar ou voltar ao estado de Incomplemta.

![111013025-bd4c2700-837c-11eb-96bd-e35dd94de39d](https://user-images.githubusercontent.com/70667966/118026267-00078c80-b337-11eb-9ff1-0ef3b2a55343.png)

<h1 align="center"> TaskList (to .do) </h1>
<p> Resolução do desafio do primeiro capítulo da trilha React JS no Ignite, pela Rocketseat. </p>

<h2 align="center"> Objetivo </h2>
  Aplicar os conceitos aprendidos no capítulo para construir uma aplicação de lista de tarefas. 
  <p></p>
  No projeto deve ser possível criar uma tarefa, marcar uma tarefa como concluída
  e também deletar a tarefa. Também é necessário incluir excessões, para não deixar o usuário criar tarefas sem título.
<p></p>

<h2 align="center"> Demonstração do projeto </h2>
<p align="center">
    <img width="70%" height="70%" src="https://user-images.githubusercontent.com/70667966/118030284-77d7b600-b33b-11eb-95ed-134ed7557f71.gif"/>
</p>
<p></p>

<p> A solução para este desafio está totalmente incorporada no componente TaskList.tsx, primeiro, foi preciso estabelecer a função que cria as tarefas, as adiciona
à um <em>array</em> de tarefas e atualiza o estado da aplicação. Para deletar uma tarefa, realiza-se um <em>filter()</em> no id, e atualiza-se o estado, para que as outras
tarefas não sejam perdidas, e para marcar a tarefa como concluída, construí uma função callback nas tarefas, e um <em> map()</em> que encontra o id da tarefa e retorna as outras
tarefas também atualizando o status da tarefa selecionada. </p>

<h2 align="center"> Para testar a aplicação </h2>
<p> Para testar a aplicação é necessários dois terminais, um para executar o projeto e o outro para a API </p>

<p> 1 - Para instalar as dependências </p>

>cd TaskList
>
> npm install

<p> 2 - Para rodar o projeto </p>

> yarn dev

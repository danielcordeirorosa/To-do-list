# To-do-list

<b>Lista de Tarefas</b>

<b>Lista de Tarefas</b> é um sistema web que utiliza API do <b>Google Task</b> para gerenciar as tarefas do Google Task.
É possível: 
<br>Criar, editar e excluir Listas.
<br>Adicionar Tarefas em Listas.
<br>Criar, editar, excluir as Tarefas cadastradas nas Listas de Tarefas.

Passos para instalação e configuração do sistema:

0 - Baixe os arquivos do repositório.
  -  <a href="https://github.com/danielcordeirorosa/To-do-list/archive/master.zip" target="_blank">Link.</a>

1 - Crie uma conta do Google ou utilize uma existente para ter acesso a API do <b>Google Tasks</b> e API do <b>Google People</b>.
  - <a href="https://accounts.google.com/SignUp" target="_blank">criação de Contas do Google.</a>
  - <a href="https://developers.google.com/people" target="_blank">Google People.</a>
  - <a href="https://developers.google.com/google-apps/tasks" target="_blank">Google Task.</a>
  
2 - Configure sua conta no <b>Google APIs Console</b> para obter credencias de acesso a APIs do Google.
  - <a href="https://console.developers.google.com" target="_blank">Google APIs Console.</a>

3 - Ative as APIs Google Task e Google People e de posse das chaves (<b>Cliente ID e API key</b>) insira as chaves no arquivo index.html nas variáveis apiKey e CLIENT_ID.

   <img src="https://firebasestorage.googleapis.com/v0/b/teste-lista-de-tarefas.appspot.com/o/selecionartaskapi.PNG?alt=media&token=7a9de262-ebc4-4740-834d-694ebd89690b" heigth='50%' width='50%'>
   <img src="https://firebasestorage.googleapis.com/v0/b/teste-lista-de-tarefas.appspot.com/o/adicionargooglepeople.PNG?alt=media&token=17b7e449-92c9-42ef-832f-3d52dad8e2c5" heigth='50%' width='50%'>
  <img src="https://firebasestorage.googleapis.com/v0/b/teste-lista-de-tarefas.appspot.com/o/credenciais.PNG?alt=media&token=2eeb83ab-5777-4ce8-9f19-ed3620d88208" heigth='50%' width='50%'>
    <img src="https://firebasestorage.googleapis.com/v0/b/teste-lista-de-tarefas.appspot.com/o/variaveisclientideapikey.PNG?alt=media&token=c15372de-0d14-4f3d-917a-7dc28835b03f" heigth='50%' width='50%'>

4 - De acordo com a política de segurança do Google para acesso as APIs é preciso ter um domínio e autorizar este domínio a utilizar as credencias das APIs ou utilizar http://localhost:8080.
  <img src="https://firebasestorage.googleapis.com/v0/b/teste-lista-de-tarefas.appspot.com/o/autorizardominio.PNG?alt=media&token=435f8b38-db3c-430f-a547-cca4c7d71897" heigth='50%' width='50%'>

5 - Após autorizar seu domínio a utilizar as credenciais basta fazer upload dos arquivos para seu Host no domínio autorizado.

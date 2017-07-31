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
  
2 - Registre sua conta no <b>Google APIs Console</b> para obter credencias de acesso a APIs do Google.
  - <a href="https://console.developers.google.com" target="_blank">Google APIs Console.</a>
  
3 - De posse das chaves (<b>Cliente ID e API key</b>) insira as chaves no arquivo index.html nas variáveis apiKey e CLIENT_ID.

4 - De acordo com a política de segurança do Google para acesso as APIs é preciso ter um domínio e autorizar este domínio a utilizar as credencias das APIs ou utilizar http://localhost:8080.

5 - Após autorizar seu domínio a utilizar as credenciais basta fazer upload dos arquivos para seu Host no domínio autorizado.

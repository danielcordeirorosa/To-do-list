# To-do-list

## <b>Lista de Tarefas</b>

<b>Lista de Tarefas</b> é um sistema web que utiliza API do <b>Google Task</b> para gerenciar as tarefas do Google Task.
É possível: 
<br>Criar, editar e excluir Listas.
<br>Adicionar Tarefas em Listas.
<br>Criar, editar, excluir as Tarefas cadastradas nas Listas de Tarefas.

Passos para instalação e configuração do sistema:

 0 - Baixe os arquivos do repositório.
  -  <a href="https://github.com/danielcordeirorosa/To-do-list/archive/master.zip" target="_blank">Link.</a>
  
Detalhamento da estrutura e organização dos arquivos do projeto.
````````````````````````````````````
To-do-list/
├── index.html
├── css/
│   ├── bootstrap-theme.css
│   ├── bootstrap-theme.min.css
│   ├── bootstrap.css
│   ├── bootstrap.min.css
│   ├── docs.css
│   └── fonts/
│   │   ├── fontawesome-webfont.eot
│   │   ├── fontawesome-webfont.svg
│   │   ├── fontawesome-webfont.ttf
│   │   ├── fontawesome-webfont.woff
│   │   ├── fontawesome-webfont.woff2
│   │   ├── FontAwesome.otf
│   │   ├── glyphicons-halflings-regular.woff2
│   │   └── glyphicons.less
│   ├── green.css
│   ├── header-nav.css
│   ├── index.animate.min.css
│   ├── responsive.min.css
│   ├── style.min.css
│   ├── bootstrap.css
│   ├── bootstrap.css.map
│   ├── bootstrap.min.css
│   └── bootstrap.min.css.map
└── js/
│   ├── bootstrap.js
│   ├── bootstrap.min.js
│   ├── bootstrapValidator.min.js
│   ├── carousel.min.js
│   ├── custom.min.js
│   ├── effect.min.js
│   ├── jquery.appear.js
│   ├── jquery.cookie.min.js
│   ├── jquery.easing.1.3.js
│   ├── jquery.flexisel.min.js
│   ├── jquery.min.js
│   ├── jquery.prettyPhoto.min.js
│   ├── jquery.sticky.js
│   └── modernizr.jsbootstrap.js
└── images/ 
│   ├── bg-jumbo.png
│   ├── calendar-banner.jpg
│   └── pattern.png
``````````````````````````````````````````

As pastas css, js, images contém  os arquivos da biblioteca Bootstrap que são necessários para formação do layout.
No arquivo index.html esta contido todo conteúdo de HTML e Javascript que são necessários para acessar as APIs do Google e exibir o conteúdo.

1 - Crie uma conta do Google ou utilize uma existente para ter acesso a API do <b>Google Tasks</b> e API do <b>Google People</b>.
  - <a href="https://accounts.google.com/SignUp" target="_blank">criação de Contas do Google.</a>
  - <a href="https://developers.google.com/people" target="_blank">Google People.</a>
  - <a href="https://developers.google.com/google-apps/tasks" target="_blank">Google Task.</a>
  
2 - Configure sua conta no <b>Google APIs Console</b> para obter credencias de acesso a APIs do Google.
  - <a href="https://console.developers.google.com" target="_blank">Google APIs Console.</a>

3 - Ative as APIs Google Task e Google People e de posse das chaves (<b>Cliente ID e API key</b>) insira as chaves no arquivo index.html nas variáveis apiKey e CLIENT_ID.

   <img src="https://firebasestorage.googleapis.com/v0/b/teste-lista-de-tarefas.appspot.com/o/selecionartaskapi.PNG?alt=media&token=7a9de262-ebc4-4740-834d-694ebd89690b" heigth='80%' width='80%'>
   <img src="https://firebasestorage.googleapis.com/v0/b/teste-lista-de-tarefas.appspot.com/o/adicionargooglepeople.PNG?alt=media&token=17b7e449-92c9-42ef-832f-3d52dad8e2c5" heigth='80%' width='80%'>
  <img src="https://firebasestorage.googleapis.com/v0/b/teste-lista-de-tarefas.appspot.com/o/credenciais.PNG?alt=media&token=2eeb83ab-5777-4ce8-9f19-ed3620d88208" heigth='50%' width='50%'>
    <img src="https://firebasestorage.googleapis.com/v0/b/teste-lista-de-tarefas.appspot.com/o/variaveisclientideapikey.PNG?alt=media&token=c15372de-0d14-4f3d-917a-7dc28835b03f" heigth='50%' width='80%'>

4 - De acordo com a política de segurança do Google para acesso as APIs é preciso ter um domínio e autorizar este domínio a utilizar as credencias das APIs ou utilizar http://localhost:8080.
  <img src="https://firebasestorage.googleapis.com/v0/b/teste-lista-de-tarefas.appspot.com/o/autorizardominio.PNG?alt=media&token=435f8b38-db3c-430f-a547-cca4c7d71897" heigth='80%' width='80%'>

5 - Após autorizar seu domínio a utilizar as credenciais basta fazer upload dos arquivos para seu Host no domínio autorizado.


Links para as bibliotecas e APIs utilizadas.
  - <a href="http://getbootstrap.com/" target="_blank">Bootstrap.</a>
  - <a href="https://developers.google.com/api-client-library/javascript/start/start-js" target="_blank">Google People.</a>
  - <a href="https://developers.google.com/google-apps/tasks/quickstart/js#step_1_turn_on_the_api_name" target="_blank">Google Task.</a>



###  <a href="https://teste-lista-de-tarefas.firebaseapp.com/To-do-list/" target="_blank">Visite o sistema link 1.</a>

###  <a href="https://danielcordeirorosa.github.io/To-do-list/" target="_blank">Visite o sistema link 2.</a>

# Reposit-rio-LP
<h1>Atividade Github</h1>
<h2>Alunos: Bruno Queiroz Plata e Hudson Araújo</h2>
<hr>
<h1>Instruções</h1>

<h2>Baixar o Git</h2>
<p>Deve-se instalar o installer do Git pelo site oficial na sua maquina</p>
<p>Após o download devemos iniciar a instalação do git, o installer ira perguntar se você deseja mudar alguma configuração ou se deseja deixar as configurações padrões, você pode deixar as configurações padrões e só clicar em continuar. Ao final desse processo o git estara instalado e pronto para uso na sua maquina</p>

<h2>Github</h2>

  <p>No github entre na sua conta e na pagina inicial do github crie um repositório <strong>clicando no botao com um simbolo de       mais</strong>e depois clicando em <strong>new repository</strong></p>

![WhatsApp Image 2024-03-25 at 4 34 27 PM](https://github.com/hudson12345/Reposit-rio-LP/assets/105759351/c3fd2066-5a0c-4dd7-a5b8-502a375f41c5)
  
   <p>Após isso abrira uma tela de configurações do seu novo repositório. Nessa tela você pode escolher o nome do repositório, 
   colocar uma descrição, deixar o repositório público ou privado e o mais importante Adicionar um arquivo README.md, README é       um arquivo onde você informa a outras pessoas por que o seu projeto é útil, o que elas podem fazer com o projeto e como elas      podem usá-lo. é importante sempre adicionar um arquivo README marcando a caixinha "add a README file", em seguida você pode       clicar em <strong>create a new repository</strong> </p>

   ![WhatsApp Image 2024-03-25 at 4 34 25 PM (1)](https://github.com/hudson12345/Reposit-rio-LP/assets/105759351/bfd6c13c-03e0-4d2d-8640-25dfd3772c6c)

  <p>Agora já com o repositório criado, como mostra a imagem a baixo, podemos mandar um arquivo para o seu novo repositório</p>

![WhatsApp Image 2024-03-25 at 4 34 26 PM (1)](https://github.com/hudson12345/Reposit-rio-LP/assets/105759351/c78032dc-17d7-431c-aa34-7e7eed532925)

<h2>Enviando um arquivo para o seu repositório</h2>
  <h3>Criando uma pasta local</h3>
   <p>Crie uma pasta contendo o arquivo que você deseja mandar para o github, no meu caso estou usando um arquivo de texto</p>

![WhatsApp Image 2024-03-25 at 4 34 25 PM](https://github.com/hudson12345/Reposit-rio-LP/assets/105759351/f4647fc8-2f24-419c-9a8e-6f62c7cfd32d)

![WhatsApp Image 2024-03-25 at 4 34 27 PM (1)](https://github.com/hudson12345/Reposit-rio-LP/assets/105759351/ee4102fc-b9ab-4227-92e0-23b816f32c07)

  <p> <strong>Clique com o botão direito do mouse na pasta e vá em "Open Git Bash here"</strong> essa opção abrira o git na sua pasta selecionada</p>

![WhatsApp Image 2024-03-25 at 4 34 25 PM (2)](https://github.com/hudson12345/Reposit-rio-LP/assets/105759351/6e97e8f2-bfb7-4673-9ab7-3219306308ff)

<h3>Comandos iniciais</h3>
  <p>Assim sera aberto o cmd do git que aparecerá para você começar a mandar o arquivo por meio de códigos.
   A primeira coisa que você precisa fazer é logar o seu usuário, com o comando <stong>(git config --global user.name "nome do usuário)</stong> você conseguira falar ao git o seu nome de usuário da sua conta no github e por meio do comando <strong>(git config --global user.email "email do usuário")</strong> você informara ao git qual o seu email de usuário da sua conta no github.
 </p>

 ![WhatsApp Image 2024-03-25 at 4 34 26 PM (3)](https://github.com/hudson12345/Reposit-rio-LP/assets/105759351/228e8701-81e2-4a00-a689-88a52f38ace7)

 <h4>git Init</h4>
  <p>Agora após informar seu nome e email vamos realmente começar pelo comando <strong>git init</strong> esse comando é usado na configuração inicial e serve para criar um novo repositório no git e também para inicializar um novo repositório vazio</p>

![WhatsApp Image 2024-03-25 at 4 34 26 PM (2)](https://github.com/hudson12345/Reposit-rio-LP/assets/105759351/0b6961f9-1c2b-4bc9-acbd-33bdb04e00f5)

<h4>git remote add origin</h4>
  <p>Vamos usar agora o comando <strong>git remote add origin 'link do seu repositório' </strong> com esse comando você informa onde está o seu repositório por meio de um link do github</p>

  
  <br>
  <p>importante falar que para conseguir o link do seu repositório é necessario ir no github clicar em no botão verde escrito "code" e copiar o link em https.</p>

![WhatsApp Image 2024-03-25 at 4 34 29 PM](https://github.com/hudson12345/Reposit-rio-LP/assets/105759351/e57acdcb-9d6e-43e4-9269-a021a4726294)
  
  <br>
<h4>git pull --allow-unrelated-histories 'link do repositório'</h4>
 <p>Com esse comando você recupera arquivos já existentes no servidor e mescla com os arquivos locais que estiverem nos diretórios</p>

![WhatsApp Image 2024-03-25 at 4 34 29 PM (3)](https://github.com/hudson12345/Reposit-rio-LP/assets/105759351/2afe7fff-93ee-4231-8cc8-8e816ead58c6)

<h4>git add .</h4>
 <p>O comando <strong>git add .</strong> adiciona e prepara para enviou ao github os arquivos que você tem localmente</p>

<h4>git status</h4>
  <p>Ele fala o status do diretório de trabalho, ele permite com que você veja as alterações preparadas e despreparadas, quais arquivos não estão sendo monitorados pelo git e quais estão sendo monitorados</p>  

![WhatsApp Image 2024-03-25 at 4 34 30 PM](https://github.com/hudson12345/Reposit-rio-LP/assets/105759351/8917b37e-47a9-4bc4-be3c-805f8d3893b7)

<h4>git commit -m</h4>
  <p>O comando <strong>git commit -m 'mensagem'</strong> leva as mudanças do ambiente local até o repositório do git, permitindo a inserção de uma mensagem que descreva oque a sua mudança faz</p>

![WhatsApp Image 2024-03-25 at 4 34 27 PM (3)](https://github.com/hudson12345/Reposit-rio-LP/assets/105759351/b2361570-f6bb-4d48-8f81-f17cc14ba994)

<h3>Ultimas etapas</h3>
  <p>Como é a primeira vez que você faz isso o git ira abrir uma tela para que você se conecte a sua conta do github, isso só ira acontecer na primeira vez que você faz</p>

  ![WhatsApp Image 2024-03-25 at 4 34 29 PM (2)](https://github.com/hudson12345/Reposit-rio-LP/assets/105759351/67ba7f05-431c-4cf5-8d2c-d9bf2c8d424a)

 <h4>git push origin master</h4>
   <p>Esse comando <strong>git push origin master</strong> empurra os arquivos/alterações para o seu repositório no github </p>

![WhatsApp Image 2024-03-25 at 4 34 28 PM](https://github.com/hudson12345/Reposit-rio-LP/assets/105759351/2de92f72-c20b-434a-bd52-b3d99035ef93)

<h3>Adicionando um membro ao repositório</h3>
  <p>após tudo isso você deve ter conseguido mandar o arquivo ao github mas agora vamos adicionar um membro ao seu repositório</p>

![WhatsApp Image 2024-03-25 at 4 34 28 PM (3)](https://github.com/hudson12345/Reposit-rio-LP/assets/105759351/2d68448e-e3bc-4123-aa0f-d3baa02d14a3)

  <p>cliclando nas settings/confugurações você deve ir em general/geral e ir na opção "add people"</p>

![WhatsApp Image 2024-03-25 at 4 34 28 PM (1)](https://github.com/hudson12345/Reposit-rio-LP/assets/105759351/f90279fe-f098-4ba4-8091-ac4a9d671667)

  ![WhatsApp Image 2024-03-25 at 4 34 29 PM (1)](https://github.com/hudson12345/Reposit-rio-LP/assets/105759351/9e9d1e1d-b61f-4d45-a67d-1a7d69b5b16d)

  <p>o github ira pedir o nome de usuario ou email da pessoa que você deseja adicionar, você precisa saber algum desses dados corretamente</p>

  ![WhatsApp Image 2024-03-25 at 4 34 27 PM (2)](https://github.com/hudson12345/Reposit-rio-LP/assets/105759351/54df3379-94eb-4fb8-8b28-b01008c0fa55)

  <p>em seguida o pedido para colaboração sera enviado a pessoa e ela tera que aceitar para poder ver e alterar seu repositório</p>

![WhatsApp Image 2024-03-25 at 4 34 28 PM (2)](https://github.com/hudson12345/Reposit-rio-LP/assets/105759351/026c1bd3-3bb4-49d8-93af-034ffac0d5b7)
  

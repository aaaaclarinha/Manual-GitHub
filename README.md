# Manual-GitHub
Primeiro e único manual para iniciantes no GitHub sobre o GitHub


Vamos lá, o que é o GitHub?

GitHub é uma plataforma de hospedagem de código-fonte e arquivos com controle de versão usando o Git, ele permite que programadores ou qualquer usuário da plataforma produza códigos abertos, ou não, e contribuam em projetos de outros usuários.

Como usar o GitHub?

Se você está aqui, tu já criaste uma conta nesse site e vamos lá.

<h2> Sumário </h2>
<li> Criando e editando meu primeiro repositóri; </li>
<li> Baixando um  repositório de outro usuário  para colaborador; </li>
<li> Baixando o repositório para sua máquina, editando e enviando de volta para o servidor do GitHub; </li>


## Criando e editando meu primeiro Repositório;
Passo 1 - Inicio: Vá no seu perfil e clique que "Repositories".

Passo 2 - Criando um repositório: clique em "New" e de um nome para o repositório em "Repository name", se você quiser tu podes falar um pouco sobre o repositório em "Description".

Passo 2.1 - Especifidades do meu repositório Em baixo da descrição existe a opção de escolher se seu repositório vai ser publico "Public" ou privado "Private".

Passo 2.2 - Para iniciar seu repositório você pode escolher começar com uma pasta base clicando em "Add a README file".

Passo 2.3 - Se você quiser pode adicionar alguma linguagem de programação no "Add .gitignore" e essa linguagem vai ter as bibliotecas e adicionais excluídos para não atrapalhar seu código.

Passo 2.4 - Em "Chosse a license" tu deves escolher se seu código vai ser apenas seu e quem quiser usar terá que entrar em contato contigo e se tu permitires a pessoa deve te dar os direitos autorais ou você apenas vai liberar seu código para livre uso com direitos autorais, existem alguns termos e responsabilidades dependendo do tipo de "License" escolhido.

Passo 3 - Seu repositório foi criado, agora vai começar a editar: Após clicar em "Create", abrirá uma nova aba automaticamente, nessa aba tu terás diversas outras informações, mas vamos focar no início, clique em "<> code" ali tu terás a pasta "README.md" criada anteriormente e podemos editar essa pasta

Passo 4 - Edição de uma pasta ou documento dentro do repositório e seus commits: Vamos editar a pasta "README.md", clique na imagem de lápis e a aba vai se modificar e dividir em duas "<> Edit file" e "Preview", na primeira tu podes escrever um texto ou adicionar seu código e na segunda você terá uma prévia de como vai ficar quando tu terminares de editar

Passo 4.1 - Um adendo importante, sempre que você editar uma pasta, texto ou um misero ponto na linha de código tu deves criar um "commit", tu deve encontrar a caixa "commit" rolando um pouco para baixo na página

Passo 4.2 - O que é o "Commit"? É um comentário da edição que você para tu não se perder conforme o documento/pasta evolui, ali temos duas caixas de texto, na primeira você deve dar um título para a edição e na segunda tu descreves o que foi feito ou os motivos da modificação.

Passo 4.2.1 - Para confirmar sua edição e commit tu deves clicar em "Commit changes" ai o seu comentário e edição vão ser adicionados no histórico.

Passo 4.3 - Extra do "Commit": ele também serve como uma máquina do tempo, clicando no símbolo do relógio com uma seta no sentido anti-horário (o histórico) tu podes ver a antes e depois da sua edição.

Passo 5 - Criando uma nova aba/pasta/"File" ou como você quiser chamar: clique em "Add file", esse bloco fica em baixo de "Insights" no começo da página

Passo 5.1 - Clique em "Create new file" para criar e a página irá atualizar e tu devera dar um nome para a nova pasta e tu pode usar como pretender essa nova "file"

## Baixando um repositório de outro usuário para colaborar;

Passo 1 - primeiro escolha um repositório ou tenha um link de repositório.

Passo 2 - Abra o link ou o repositório

Passo 3 - Clique em "Fork" e a pagina irá atualizar, tu pode alterar o nome do repositório e adicionar uma descrição, depois disso clique em "Create fork"

Passo 4 - Ai vai abrir o "Fork" feito, esse Frok é semelhante a uma cópia do repositório original, para colaborar escolha alguma das pastas ou file e edite algo dentro delas.

Passo 5 - Após editar faça o "Commit changes" ou "Propose changes" para confirmar sua alteração, clique a aba "Pull requests" que séria a edição feita por você para o arquivo, ali você pode criar e enviar o seu comentário sobre algo clicando em "New pull request" ou comparar com outros comentários e enviar o seu comentario clicando em "Compare e pull request"

Passo 6 - Agora basta o dono do arquivo aceitar as mudanças feitas na sua aba do "pull request"

Passo 6.1 - Adendo: o dono não vai conseguir aceitar arquivos que deem conflito na hora de atualizar o repositório original, então sempre se lembre de editar o repositório mais recente

## Baixando o repositório para a sua máquina, editando e enviando de volta para o servidor do GitHub:

Para baixar algum repositório em uma máquina precisamos criar uma pasta chamada "GitHub" e ter o software Git Bash

Passo 1 - Na pasta criada clique com o botão direito do mouse e clique em "Git Bash Here" isso deve abrir um painel do Git

Passo 2 - Escreva "git status" e clique em enter para confirmar que o painel não tem nenhum trabalho rodando

Passo 3 - Escreva "git clone link" e clique em enter, mas você não vai colocar literalmente "link"

Passo 3.1 - O link que tu deve colocar tu vai achar clicando em "Code", que está ao lado de "Add file", e clicar para copiar o link em HTTPS

Passo 3.3 - Para colar o link segure o botão shift e depois o Insert e depois de enter, tu deve notar que aparecera um documento na pasta "GitHub", não se preocupe ele só vai ficar lá enquanto estivermos usando ele

Passo 4 - agora com algum software de sua preferência tu pode abrir e editar o repositório, eu recomendo o Visual Studio Code, e tambem é importante dar um "cd nome_do_repositório" para indicar o painel que os comandos a seguir devem ser dados em função do seu repositório (nome_do_repositório é pessoal seu)

Passo 4.1 - Lembre-se que você está editando na sua máquina, logo se você não fizer nada o repositório online não será modificado

Passo 5 - Após editar temos que fazer o mesmo passo que online, o passo de dar um "Commit", só que no Git Bash você deve escrever "git commit -m "titulo da edição"" (-m = permite tu criar uma mensagem para o commit)

Passo 5.1 - Para salvar suas modificações no Visual Studio Code apenas de um ctrl+S

Passo 5.2 - o titulo da edição é pessoal, após dar enter no passo commit, tu deve dar "git status" para ver se o painel terminou de rodar os seus pedidos

Passo 5.3 - Se tu modificou algum documento o "git status" vai retornar "modified: nome_do_repositório" na cor vermelha, isso significa que ele identificou uma moficação nesse repositorio

Passo 6 - Para mandar o painel adicional a modificação feita tu deve escrever "git add ."(que vai adicionar todas as modificações aos seus respectivos documentos)

Passo 6.1 - Para verificar se tudo está ocorrendo de forma certa, dê um "git status" e ele deve retornar "modified: nome_do_repositório" na cor verde, isso significa que tudo ocorreu com sucesso

Passo 6.2 - Para confirmar a modificação é necessário dar um "git commit -m"titulo da edição""

Passo 6.3 - E por fim um "git push" para mandar o documento atualizado para o servidor da GitHub

Passo 7 - Agora você pode verificar no GitHub online que o documento foi atualizado com sucesso

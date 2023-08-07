Para adquirir conhecimento fundamental do GitHub, incluindo habilidades como criação de repositório, edição de código e modificação de dados, um tutorial foi desenvolvido. Notavelmente, o tutorial é baseado nas diretrizes do W3 Schools, com a intenção de documentar cada etapa realizada em um arquivo Markdown no GitHub. Além disso, explicações perspicazes e capturas de tela serão fornecidas para destacar as realizações alcançadas durante o abrangente processo de 7 etapas. Vale ressaltar que diversos commits serão utilizados para construir material bem documentado, com preferência para utilização de interface de linha de comando.


# Usando o Git como linha de comando:

Para Windows, você podemos usar o Git bash, que vem incluído no Git para Windows, que é o meu caso.

1: A primeira coisa que precisamos fazer é verificar se o Git está instalado corretamente:

2: Através do Prompt de Comando (cmd), podemos conferir com o comando "git --version".

abra o Prompt de Comando no seu notebook:
![image](https://github.com/renanribeir0/relatoriotecnico2/assets/110369271/3878facd-3bbd-4f45-8ace-060ec5f26c8b)

Digite o comando "git --version"
![image](https://github.com/renanribeir0/relatoriotecnico2/assets/110369271/b3259c9e-b476-4736-b1bd-1d932f7c76e2)

Ou seja, "git version X.Y", significa que o git já esta instalado no meu pc.

Caso não esteja instalado, acesse o link: https://git-scm.com/downloads

# Configurar o Git

Adicionando suas informações ao git:

1: Use o comando: git config --global user.name "seu nome", para adicionar seu nome ao git.
<img width="960" alt="image" src="https://github.com/renanribeir0/relatoriotecnico2/assets/110369271/03d5c4d0-8310-4cdb-baed-236300d971e1">

2: Use o comando: git config --global user.email "seu email", para adicionar seu nome ao git.
<img width="960" alt="image" src="https://github.com/renanribeir0/relatoriotecnico2/assets/110369271/3b26e42a-079f-4448-a80d-68c5473460cc">

# Criando Pasta Git
Use o comando: mkdir myproject.
<img width="960" alt="image" src="https://github.com/renanribeir0/relatoriotecnico2/assets/110369271/1ad1eaed-c3d5-423f-8052-b72de574b889">

# Inicializar o Git
Use o comando: git init.
<img width="960" alt="image" src="https://github.com/renanribeir0/relatoriotecnico2/assets/110369271/d543a330-b1d4-49b6-9465-e601c645b8b0">


# Edição de código no Git GitHub

O GitHub possui um editor de código.

Para editar o README.md arquivo no GitHub. Basta clicar no botão "codi", no lado esquedo superior do github e em seguido no simbolo de lápis que fica ao lado esquerdo:
<img width="960" alt="image" src="https://github.com/renanribeir0/relatoriotecnico2/assets/110369271/a3ae2567-4f57-44f3-a1c2-33bb0cf32967">

Após realizar as alretações, clique no canto superior direito "Commit Changes..."
<img width="960" alt="image" src="https://github.com/renanribeir0/relatoriotecnico2/assets/110369271/dfeaab44-902c-4976-99f7-dba3f2c105f8">

Por fim, adicione uma descrição e clique em commit changes para salvar.
<img width="960" alt="image" src="https://github.com/renanribeir0/relatoriotecnico2/assets/110369271/481f4094-3b5e-45cf-93a7-a01b6cf8ecca">


# Git Pull do GitHub

Git Busca
Serve para obter todo o histórico de alterações de um branch/repo rastreado.

Então, no seu Git local, fetch atualize para ver o que mudou no GitHub:

Podemos realizar através do comando git fetch origin.
<img width="960" alt="image" src="https://github.com/renanribeir0/relatoriotecnico2/assets/110369271/deec508d-251c-4f0d-b15c-1821a960bf76">

Para verificar seu status:
<img width="960" alt="image" src="https://github.com/renanribeir0/relatoriotecnico2/assets/110369271/8559d649-0e1a-4451-9b39-ba5f41f3fd4f">

Estamos atrás do origin/masterpor 1 commit. Isso deve ser atualizado README.md, mas vamos verificar visualizando o log:
<img width="960" alt="image" src="https://github.com/renanribeir0/relatoriotecnico2/assets/110369271/87e6f50d-214b-4318-954f-5b07b073cf2d">

Isso parece esperado, mas também podemos verificar mostrando as diferenças entre nosso local mastere origin/master:
<img width="960" alt="image" src="https://github.com/renanribeir0/relatoriotecnico2/assets/110369271/9316e2e7-feff-43b0-bbb6-7a3532b05449">

# Git Mesclar
mergecombina o ramo atual, com um ramo especificado.

Confirmamos que as atualizações são as esperadas e podemos mesclar nossa ramificação atual ( master) com origin/master:
<img width="960" alt="image" src="https://github.com/renanribeir0/relatoriotecnico2/assets/110369271/133b24e8-1538-488b-92d5-e745eab5bc18">

Verifique statusnovamente para confirmar se estamos atualizados:
<img width="960" alt="image" src="https://github.com/renanribeir0/relatoriotecnico2/assets/110369271/b63e1e20-1e89-4e0d-b569-a0508f4ff515">

# Git Pull
Mas e se você quiser apenas atualizar seu repositório local, sem passar por todas essas etapas?

pullé uma combinação de fetche merge. Ele é usado para extrair todas as alterações de um repositório remoto para a ramificação em que você está trabalhando.

Faça outra alteração no arquivo Readme.md no GitHub.
<img width="960" alt="image" src="https://github.com/renanribeir0/relatoriotecnico2/assets/110369271/f967daad-eab0-459c-9f80-449c89310d55">

No terminal. E assim que você mantém seu Git local atualizado a partir de um repositório remoto. No próximo capítulo, veremos mais de perto como pushfunciona no GitHub.:
<img width="960" alt="image" src="https://github.com/renanribeir0/relatoriotecnico2/assets/110369271/57a4ec5b-6e48-4d93-ad8b-ec32d7ad094c">


# Git Push para o GitHub
Enviar alterações para o GitHub
Vamos tentar fazer algumas alterações em nosso git local e enviá-las para o GitHub.

atualizações feitas no vscode e irei eviar para o github através dos comandos: git commit -m "comentario" e git push origin
<img width="960" alt="image" src="https://github.com/renanribeir0/relatoriotecnico2/assets/110369271/7c96fc56-df69-4dc2-b178-21b03ecebffc">

assim ficou:
<img width="960" alt="image" src="https://github.com/renanribeir0/relatoriotecnico2/assets/110369271/d8834be0-5152-4f13-b2af-b09c87636e62">



# Ramificação do Git GitHub
No GitHub, acesse seu repositório e clique no botão branch "mestre".

Lá você pode criar uma nova Filial. Digite um nome descritivo e clique em Criar ramificação:

Clicando em main e main default
<img width="960" alt="image" src="https://github.com/renanribeir0/relatoriotecnico2/assets/110369271/83af280f-ac4d-4c9f-939a-f25a1a4e1b69">

Selecione uma das ramificações:
<img width="960" alt="image" src="https://github.com/renanribeir0/relatoriotecnico2/assets/110369271/809111b6-c079-4d06-a1d7-37453a18724d">

assim voce poderá editar, verificar ultimas atualizacoes e comiitar:
<img width="960" alt="image" src="https://github.com/renanribeir0/relatoriotecnico2/assets/110369271/4771e714-08b6-4f05-b587-303c342a350a">


# Ramificação do Git Push para o GitHub
Enviar uma ramificação para o GitHub
Criando uma nova ramificação local e enviá-la para o GitHub.

Comece criando um branch, como fizemos anteriormente, usando o comando: git checkout -b update-readme

<img width="960" alt="image" src="https://github.com/renanribeir0/relatoriotecnico2/assets/110369271/5a3e6ca9-eb32-46ef-9fe9-5e583a74ecd6">

Verifica o status novamento usando o comando: git status
<img width="960" alt="image" src="https://github.com/renanribeir0/relatoriotecnico2/assets/110369271/2c1e3970-acc9-4c5e-85b1-7200caf7dd54">

Vemos que README.mdfoi modificado, mas não adicionado ao Staging Environment: git add README.md
<img width="960" alt="image" src="https://github.com/renanribeir0/relatoriotecnico2/assets/110369271/85a8f272-7505-44e3-bcac-5d0ff994579f">

Então, vamos commitcolocá-los em branch: git commit -m "seu comentario"
<img width="960" alt="image" src="https://github.com/renanribeir0/relatoriotecnico2/assets/110369271/80eb4f53-82d3-4793-8b5c-d1a73ac009d4">

gora push, do branchnosso repositório Git local, para o GitHub, onde todos podem ver as alterações:
<img width="960" alt="image" src="https://github.com/renanribeir0/relatoriotecnico2/assets/110369271/11c2271d-adf0-4608-a663-5fe08a6e82b8">

Acesse o GitHub e confirme se o repositório tem um novo branch: no canto superior direito mostra 2 branches
<img width="960" alt="image" src="https://github.com/renanribeir0/relatoriotecnico2/assets/110369271/a59e6a33-efa7-4c13-97dd-e0df4b551000">

No GitHub, agora podemos ver as alterações e mergecolocá-las no mestre branch, se o aprovarmos.
Se você clicar em "Compare & pull request", poderá ver as alterações feitas e os novos arquivos adicionados:
<img width="960" alt="image" src="https://github.com/renanribeir0/relatoriotecnico2/assets/110369271/d684e74f-de01-4242-9ae9-a6ce78a5c113">


Um pull request é como você propõe mudanças. Você pode pedir a alguém para revisar suas alterações ou extrair sua contribuição e mesclá-la em seu ramo.
Como este é seu próprio repositório, você  merge mesmo pode fazer sua solicitação pull:
<img width="960" alt="image" src="https://github.com/renanribeir0/relatoriotecnico2/assets/110369271/1e7d4c40-f4cc-46c9-917f-e652e59ba27c">

<img width="960" alt="image" src="https://github.com/renanribeir0/relatoriotecnico2/assets/110369271/5e1a5d6c-4cbe-4dd4-a639-e55184dc9b9a">

A solicitação pull registrará as alterações, o que significa que você pode analisá-las posteriormente para descobrir as alterações feitas.
O resultado deve ser algo assim:
<img width="960" alt="image" src="https://github.com/renanribeir0/relatoriotecnico2/assets/110369271/8fb9a91c-82ca-461e-9618-019bae70181a">

Depois de confirmar que as alterações da ramificação anterior foram incluídas, exclua-as também:
<img width="960" alt="image" src="https://github.com/renanribeir0/relatoriotecnico2/assets/110369271/1dbbb61f-df8a-4cdc-acbe-6742f075eed0">


# Git Pull Branch do GitHub
Puxando um branch do GitHub
Agora continue trabalhando em nosso novo branchGit local.

Vamos pulldo nosso repositório GitHub novamente para que nosso código esteja atualizado, usando o comando: git pull
<img width="960" alt="image" src="https://github.com/renanribeir0/relatoriotecnico2/assets/110369271/c4fcfc62-1c56-4cbf-bef2-206131956924">

E confirme quais filiais temos e onde estamos trabalhando no momento, usando o comando: git branch
<img width="960" alt="image" src="https://github.com/renanribeir0/relatoriotecnico2/assets/110369271/5df0304b-0c24-4674-b97e-d7b7a3199be3">

Portanto, não temos o novo branchem nosso Git local. Mas sabemos que está disponível no GitHub. Assim, podemos usar a -aopção de ver todas as ramificações locais e remotas. Use o comando: git branch -a
<img width="960" alt="image" src="https://github.com/renanribeir0/relatoriotecnico2/assets/110369271/b48461a5-0883-48f6-8c7f-d0af9a8dfc8a">

git checkout html-skeleton:
<img width="960" alt="image" src="https://github.com/renanribeir0/relatoriotecnico2/assets/110369271/e5c9deea-ad84-48dc-a6da-5b78efd76b34">

Adicionando uma breve descrição do projeto, fizemos a primeira alteração no arquivo README.md no repositório clonado. Para enviar as alterações para o repositório remoto no GitHub, usamos os comandos git status, git add, git commit e git push.

Desta vez, fizemos outra rodada de alterações no arquivo README.md no GitHub. Essas alterações incluem a incorporação de detalhes detalhados sobre a meta do projeto, os resultados previstos e o guia planejado para o tutorial.

Usando a interface do GitHub, fizemos uma alteração no arquivo README.md do repositório remoto. Para sincronizar as alterações com o repositório local, usamos o comando git pull em nosso ambiente local.

Usando git commit, confirmamos as alterações que fizemos no arquivo README.md. Depois disso, enviamos as alterações para o repositório remoto no GitHub usando o comando git push.

GitHub Branch - Usamos o comando git Branch para criar um novo branch chamado "feature-branch" e usamos git checkout para mudar para esse novo branch. Fizemos alterações no arquivo README.md na nova ramificação.

Puxe a ramificação do GitHub - No GitHub, criamos um novo arquivo chamado "new-file.txt" diretamente na ramificação "feature-branch". Em nosso ambiente local, usamos git pull origin feature-branch para efetuar pull das alterações para o branch correspondente em nosso repositório local.

Envie a ramificação para o GitHub - criamos outro arquivo localmente chamado "another-file.txt" e usamos os comandos git add e git commit para preparar as alterações. Em seguida, usamos git push origin feature-branch para enviar o novo branch contendo as alterações para o repositório remoto no GitHub.


Conclusão:
Ao longo deste guia, adquirimos conhecimento sobre os fundamentos do GitHub, que abrangem a inicialização de um repositório, a confirmação de alterações, a colaboração por meio de branches e, especificamente, o pull e push de branches únicos. Seguindo a orientação apresentada pelo W3 Schools e anotando cada fase em um documento no GitHub, adquirimos uma compreensão completa do fluxo de trabalho do GitHub e do método para participar efetivamente de empreendimentos de código aberto. Além disso, a implementação de vários commits para registrar etapas sequenciais no arquivo README.md nos permitiu monitorar perfeitamente a progressão das modificações ao longo deste guia informativo.



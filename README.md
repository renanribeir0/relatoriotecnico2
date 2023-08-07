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










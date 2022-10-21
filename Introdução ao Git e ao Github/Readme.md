#Link para download do Git: https://git-scm.com/downloads#
O Git Bash é um terminal extendido para otimizar o uso do Git.

#Como criar um projeto novo:

- Criar uma nova pasta no PC pra isso chamada Git Tutorial
- Abrir o VSCode nessa pasta
- Criar um novo arquivo README.md
- Escrever dentro dele Olá, nesse projeto você aprenderá alguns comandos do Git
- Salva o arquivo

#Agora então é hora de usarmos o Git#

- Abre o Git Bash que foi instalado na máquina (pode ser pelo terminal do VSCode mesmo)
- git init para inicializar o repositório

Foi criada uma pastinha .git e é ali que toda a mágica acontece, então não apague

- git add README.md para colocar o arquivo na área de stagging

Esse add é necessário antes de darmos o commit de fato, mas por que isso? No final do vídeo explico para vocês

- git commit -m "primeiro commit" para de fato dar o commit no repositório
- git branch -M "main" para alterar o nome da branch principal de master para main (isso é uma boa prática atualmente recomendada)

#Repositório no Github:# 

- Depois de você ter criado a sua conta na plataforma, você irá em Criar novo repositório
Você vai preencher com as informações do projeto, então dar o nome do repositório, colocar uma breve descrição e criar

Logo depois vai aparecer essa página um pouco cinza e confusa e com vários comandos (pode até perceber que alguns deles jpa usamos), mas o que você tem que fazer é bem simples, apenas copie o link que aparecer para você

Lembra do conceito de remote que eu expliquei pra vocês no último vídeo? Nós iremos utilizá-lo agora

- Para passar o commit do meu repositório local (da minha máquina) para um repositório na plataforma do Github, usamos o git remote add origin <link do repositório>
- origin é o nome utilizado para referenciar o nosso repositório

Agora já temos o nosso repositório local conectado com o respositório do Github, porém o commit que damos na máquina não sobe automaticamente para a plataforma

- Para isso precisaremos empurrar, enviar para lá com o git push -u origin main
Agora se recarregarmos a página iremos ver o nosso arquivo aqui na plataforma!
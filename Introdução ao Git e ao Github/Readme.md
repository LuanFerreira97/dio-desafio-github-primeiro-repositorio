#Link para download do Git: https://git-scm.com/downloads#
O Git Bash � um terminal extendido para otimizar o uso do Git.

#Como criar um projeto novo:

- Criar uma nova pasta no PC pra isso chamada Git Tutorial
- Abrir o VSCode nessa pasta
- Criar um novo arquivo README.md
- Escrever dentro dele Ol�, nesse projeto voc� aprender� alguns comandos do Git
- Salva o arquivo

#Agora ent�o � hora de usarmos o Git#

- Abre o Git Bash que foi instalado na m�quina (pode ser pelo terminal do VSCode mesmo)
- git init para inicializar o reposit�rio

Foi criada uma pastinha .git e � ali que toda a m�gica acontece, ent�o n�o apague

- git add README.md para colocar o arquivo na �rea de stagging

Esse add � necess�rio antes de darmos o commit de fato, mas por que isso? No final do v�deo explico para voc�s

- git commit -m "primeiro commit" para de fato dar o commit no reposit�rio
- git branch -M "main" para alterar o nome da branch principal de master para main (isso � uma boa pr�tica atualmente recomendada)

#Reposit�rio no Github:# 

- Depois de voc� ter criado a sua conta na plataforma, voc� ir� em Criar novo reposit�rio
Voc� vai preencher com as informa��es do projeto, ent�o dar o nome do reposit�rio, colocar uma breve descri��o e criar

Logo depois vai aparecer essa p�gina um pouco cinza e confusa e com v�rios comandos (pode at� perceber que alguns deles jpa usamos), mas o que voc� tem que fazer � bem simples, apenas copie o link que aparecer para voc�

Lembra do conceito de remote que eu expliquei pra voc�s no �ltimo v�deo? N�s iremos utiliz�-lo agora

- Para passar o commit do meu reposit�rio local (da minha m�quina) para um reposit�rio na plataforma do Github, usamos o git remote add origin <link do reposit�rio>
- origin � o nome utilizado para referenciar o nosso reposit�rio

Agora j� temos o nosso reposit�rio local conectado com o resposit�rio do Github, por�m o commit que damos na m�quina n�o sobe automaticamente para a plataforma

- Para isso precisaremos empurrar, enviar para l� com o git push -u origin main
Agora se recarregarmos a p�gina iremos ver o nosso arquivo aqui na plataforma!
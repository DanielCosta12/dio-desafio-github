# DIO - BOOTCAMP(GIT/GITHUB)

- Por que?
- Facilitar as organizações do documentos dev
- Software - não é feito sozinho precisa de uma equipe colaborativa.
- GIT - Software de monitoramento de código de diferentes versões
- GIT NÃO É IGUAL GITHUB
- Apenas complementares mas diferentes
- Github - Repositório online para armazenar nossos códigos
1. Controle de versão
2. Armazenamento em nuvem
3. Trabalho em equipe
4. Melhorar seu código
5. Reconhecimento
- Comandos básicos terminal :
- Mudar de pastas - -cd
- Listar as pastas  -dir  / ls (linux_
- Criar pastar/arquivos -mkdir
- Deletar pastas/arquivos -del / rmdir  / -rm -rf
- cd .. volta
- cls - limpar / clear
- TAB - complementa oq está pesquisando com o nome do arquivo/pasta
- echo escreve no terminal
- echo hello >hello.txt(vai verificar se existe esse arquivo se não tiver ele irá criar e colocar a informação)
- del - deleta os arquivos dentro da pasta e não o repositório
- rmdir NOME DA PASTA /S /Q
- $ openssl sha1 lorem.txt
- Algoritmo de encriptação inteligente, ele gera um algoritmo de caractere quando você cria um documento e se você alterar ele altera e se você voltar com a versão anterior ele volta com o mesmo caractere (SHA1) 40-caracter
- -a mostra arquivos ocultos

## Objetos internos do Git

- Blobs - Guarda a encriptação e armazena metadados tipo do objeto, tamanho do arquivo \0 e o conteúdo.

![Untitled](DIO%20-%20BOOTCAMP(GIT%20GITHUB)%206b5f5e980e914321a7e32a08985088cc/Untitled.png)

![Untitled](DIO%20-%20BOOTCAMP(GIT%20GITHUB)%206b5f5e980e914321a7e32a08985088cc/Untitled%201.png)

![Untitled](DIO%20-%20BOOTCAMP(GIT%20GITHUB)%206b5f5e980e914321a7e32a08985088cc/Untitled%202.png)

- Trees - Armazenam blob também te metadados tbm tem o sha1 e guarda o nome do arquivo. Monta a estrutura de onde está montado como diretórios. Uma coisa está relacionada a outra.(encriptação)

![Untitled](DIO%20-%20BOOTCAMP(GIT%20GITHUB)%206b5f5e980e914321a7e32a08985088cc/Untitled%203.png)

![Untitled](DIO%20-%20BOOTCAMP(GIT%20GITHUB)%206b5f5e980e914321a7e32a08985088cc/Untitled%204.png)

- Commits - É o objeto que vai juntar tudo e dar sentido no que estamos fazendo, aponta para a tree, parente(ultimo commit), autor, mensagem.

![Untitled](DIO%20-%20BOOTCAMP(GIT%20GITHUB)%206b5f5e980e914321a7e32a08985088cc/Untitled%205.png)

- Commit também gera um SHA1
- Se eu alterar o arquivo, altera toda a estrutura do commit.
- 

![Untitled](DIO%20-%20BOOTCAMP(GIT%20GITHUB)%206b5f5e980e914321a7e32a08985088cc/Untitled%206.png)

## Chave SSH e TOKEN

- Conectar com servidor do github com nosso pc

- git init - iniciar o repositório
- git add - mover arquivos e dar inicio no processo do commit
- git commit - e fazer o commit
- git add *
- git commit -m “”
- git status
- git push origin main - mandar para o github nuvem
- git pull origin
- git clone (https do github)

![Untitled](DIO%20-%20BOOTCAMP(GIT%20GITHUB)%206b5f5e980e914321a7e32a08985088cc/Untitled%207.png)
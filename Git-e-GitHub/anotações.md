## Introdução ao Git e GitHub

**GitHub** é um servidor remoto para armazanamento de código, onde se tem acesso de forma gráfica ao trabalho e versionamento do código de forma segura

**Git GUI** - Permite o uso das ferramentas de gerenciamento de controle, como committing, adding, pushing, etc via GUI.

**GUI** - Graphical User Interface

**Git Bash** - Aplicação Windows que emula o terminal Unix para utilização via terminal dos comandos do Git através de uma interface CLI

**CLI** - Command Line Interface

### Navegação Windows

+ **CD** - Change Directory - Muda de diretório 
+ **DIR** - Directory - Mostra todos os arquivos do diretório selecionado
+ **MKDIR** - Make Directory - Cria um novo diretório
+ **DEL** - Delete - Deleta os arquivos
+ **RMDIR** - ReMove Directory - Apaga o diretório
+ **CLS** - Clear Screen - Limpa a tela
+ **>** - Redirecionador de fluxo, salva em um txt

### Funcionamento do Git

**Objetos Fundamentais**
+ **Blobs** - Objeto que armazena o conteúdo do arquivo, onde é gerado uma hash via SHA-1
+ **Tree** - Armazena Blobs, no caso de arquivos no mesmo diretório é representado como uma Tree
+ **Commit** - Aponta para uma Tree, um parente (ultimo commit), um autor, uma mensagem e um timestamp(carimbo de data e tempo)

**SHA-1** - Secure Hash Algorithm - Usado para identificar os arquivos

![Funcionamento Git](https://git-scm.com/figures/18333fig0901-tn.png)

git . ou git -A irá adicionar todo o conteúdo untracked no controle de versão local

git commit -m esse -m é o comando para adicionar um comentário após o git commit o conteúdo ficará preparado para ser enviado para nuvem com o git push

git push origin main irá enviar todos os commits locais para a nuvem

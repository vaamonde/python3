#Autor: Robson Vaamonde<br>
#Procedimentos em TI: http://procedimentosemti.com.br<br>
#Bora para Prática: http://boraparapratica.com.br<br>
#Robson Vaamonde: http://vaamonde.com.br<br>
#Facebook Procedimentos em TI: https://www.facebook.com/ProcedimentosEmTi<br>
#Facebook Bora para Prática: https://www.facebook.com/BoraParaPratica<br>
#Instagram Procedimentos em TI: https://www.instagram.com/procedimentoem<br>
#YouTUBE Bora Para Prática: https://www.youtube.com/boraparapratica<br>
#Data de criação: 02/09/2024<br>
#Data de atualização: 01/10/2024<br>
#Versão: 0.05<br>

Conteúdo estudado nessa configuração:<br>
#01_ Verificando a Versão do Git instalado no Linux Mint<br>
#02_ Configurações Básicas do Git Localmente no Linux Mint<br>
#03_ Criando uma conta de acesso ao Github (CASO VOCÊ AINDA NÃO TENHA UMA)<br>
#04_ Criando nosso Repositório Remoto do Python3 no Github<br>
#05_ Personalizando o nosso primeiro Repositório Remoto no Github<br>
#06_ Clonando o Repositório Remoto do Python3 no Linux Mint<br>
#07_ Abrindo nosso Repositório Local do Python3 com o VSCode no Linux Mint<br>
#08_ Integrando o VSCode com o Github no Linux Mint<br>
#09_ Instalando o Git Bash no Microsoft Windows 10<br>
#10_ Clonando o Repositório Remoto do Python 3 no Windows 10<br>
#11_ Abrindo nosso Repositório Local do Python 3 com o VSCode no Windows 10<br>

Site Oficial do Python: https://www.python.org/<br>
Site Oficial do PIP: https://pypi.org/<br>
Site Oficial do VSCode: https://code.visualstudio.com/<br>
Site Oficial do Git: https://git-scm.com/<br>
Site Oficial do Github: https://github.com/

Python é uma linguagem de programação de alto nível, interpretada de script, imperativa, orientada a objetos, funcional, de tipagem dinâmica e forte. Foi lançada por Guido van Rossum em 1991.

PIP (Package Installation for Python) é um sistema de gerenciamento de pacotes padrão de facto usado para instalar e gerenciar pacotes de software escritos em Python. Muitos pacotes podem ser encontrados na fonte padrão para pacotes e suas dependências - Python Package Index. A maioria das distribuições do Python vem com o pip pré-instalado.

O Visual Studio Code é um editor de código-fonte desenvolvido pela Microsoft para Windows, Linux e macOS. Ele inclui suporte para depuração, controle de versionamento Git incorporado, realce de sintaxe, complementação inteligente de código, snippets e refatoração de código.

O Git (ou em inglês britânico) é um sistema de controle de versões distribuído, usado principalmente no desenvolvimento de software, mas pode ser usado para registrar o histórico de edições de qualquer tipo de arquivo. 

O GitHub é uma plataforma de hospedagem de código-fonte e arquivos com controle de versão usando o Git. Ele permite que programadores, utilitários ou qualquer usuário cadastrado na plataforma contribuam em projetos privados e/ou Open Source de qualquer lugar do mundo.

#01_ Verificando a Versão do Git instalado no Linux Mint<br>
```bash
#opção do comando git: --version (version)
git --version
```

#02_ Configurações Básicas do Git Localmente no Linux Mint<br>
```bash
#OBSERVAÇÃO IMPORTANTE: Essas informações são obrigatórias para os comandos: git add e
#git commint que serão utilizadas antes de enviar os arquivos para o Github com o comando
#git pull

#Seu nome completo que vai ser utilizado em qualquer commit (confirmação) recém-criado.
git config --global user.name "Robson Vaamonde"

#Seu endereço de e-mail que vai ser utilizado em qualquer commit (confirmação) recém-criado.
#DICA: recomendo você usar o seu endereço de email utilizado na autenticação do Github
git config --global user.email seu_email@seu_domínio.com

#Seu editor de texto padrão para todos os commit (confirmação) e tags.
git config --global core.editor vim

#Seu software de mesclagem que vai ser utilizado pelo git-mergetool para comparar arquivos.
git config --global merge.tool vimdiff

#Habilitando o uso de cores do comando git.
git config --global color.ui true

#Listando todas as variáveis definidas no arquivo de configuração do Git, junto com seus valores.
git config --list
  Q (quit) para sair

#Localização do arquivo de configuração do Git no Linux Mint.
#opção do comando ls: -l (long listing), -h (human-readable), -a (all), ~ (directory home)
ls -lha ~/.gitconfig

#listando o conteúdo do arquivo gitconfig
cat ~/.gitconfig
```

#03_ Criando uma conta de acesso ao Github (CASO VOCÊ AINDA NÃO TENHA UMA)<br>
```bash
Link Oficial do Projeto do Github: https://github.com

01) no canto superior do site clique em: Sing up;
02) no campo: Enter your email - digite o seu email para o cadastro e clique em: <Continue>
03) no campo: Create a password - digite a sua senha e clique em: <Continue>
04) no campo: Enter a username - digite o nome do seu usuário do Github <Continue>

#OBSERVAÇÃO IMPORTANTE: o nome de usuário no Github será utilizado como Repositório Base, 
#por exemplo o Repositório Base do Projeto Bora para Prática é: https://github.com/vaamonde
#(vaamonde), recomendo sempre criar o seu usuário tudo em minúscula, sem acentuação, sem
#espaço, nome que seja legível, fácil entendimento pois esse usuário será utilizado como 
#referência para o seu projeto.

05) no campo: Would you like to receive product updates and announcements via emails? - digite n e clique em? <Continue>
06) na tela de: Verify your account: clique em: <Verificar>
07) selecione depois nos quadros os dois objetivos idênticos e clique em: <Create account>
08) no campo: You are almost done! digite no campo: Enter code o código enviado para o seu email.
09) na tela de: Welcome to Github clique em: <Skip personalization>
```

#04_ Criando nosso Repositório Remoto do Python 3 no Github<br>
```bash
New Repository
  Owner: rsvaamonde
  Repository name: python3
  Description: Básico de Python3 no Linux Mint
  Check: Public
  Initialize this repository with:
    Check: Add a README file
    Add .gitignore: None
  Choose a license
    Add a license: MIT License
<Create repository>
```

#05_ Personalizando o nosso primeiro Repositório Remoto no Github<br>
```bash
About
  Edit repository details
    Description: (Emoji https://gist.github.com/rxaviers/7360908) 
    Website: http://www.boraparapratica.com.br
    Topics: git github bash shell linux linux-mint python python3
    Include in the home page
      Check: Releases
      Check: Packages
      Check: Environments
<Save changes>
```

#06_ Clonando o Repositório Remoto do Python 3 no Linux Mint<br>
```bash
#OBSERVAÇÃO IMPORTANTE: Sempre que você pressiona: Ctrl+Alt+T você abre o Bash/Shel (Terminal)
#na Raiz do Perfil do seu usuário, exemplo: /home/vaamonde, caso queria clonar o diretório em
#outro local utiliza o comando: cd ou dentro do Gerenciador de Arquivos, acesse o diretório
#desejado, por exemplo: Documentos clique com o botão direito do mouse e selecione: Abrir no
#Terminal.

#clonando o Repositório Remoto do Github Localmente
git clone https://github.com/rsvaamonde/python3

#listando o conteúdo clonado
#opção do comando ls: -l (list), -h (human-readable)
ls -lh

#acessando o diretório python3 clonado
cd python3/
```

#07_ Abrindo nosso Repositório Local do Python 3 com o VSCode no Linux Mint<br>
```bash
#abrindo o VSCode no repositório local do Python3
code .

#OBSERVAÇÃO IMPORTANTE: Você também pode abrir o projeto utilizando o Gerenciador de
#arquivos Nemo clicando com o botão direito do mouse no diretório de projeto do python
#e escolhendo a opção: Abrir com o VSCode na lista de opções.
Selecionar o diretório: python3
  Clicar com o botão direito do mouse
    Selecionar: Abrir Com depois: Visual Studio Code
```

#08_ Integrando o VSCode com o Github no Linux Mint<br>
```bash
#OBSERVAÇÃO IMPORTANTE: Dessa forma não existe a necessidade da criação do Token de
#autenticação do Github com o VSCode, facilitando a integração do Repositório Local
#com o Repositório Remoto.

#OBSERVAÇÃO IMPORTANTE: Para que a integração seja feita de forma correto é necessário
#que no seu navegador padrão do seu sistema operacional esteja autenticado no Github.

Pressionar Ctrl + J para abrir o Terminal

#verificando atualizações no repositório remoto do Github
#Documentação oficial do Git: https://git-scm.com/docs/git-pull
git pull

#verificando o status do repositório local
#Documentação oficial do Git: https://git-scm.com/docs/git-status
git status

#adicionando as atualizações dos arquivos no repositório local
#Documentação oficial do Git: https://git-scm.com/docs/git-add
git add .

#comitando as mudanças do arquivos no repositório local
#Documentação oficial do Git: https://git-scm.com/docs/git-commit
git commit -m "Meu primeiro commit"

#enviando as mudanças do repositório local para o repositório remoto no Github
#Documentação oficial do Git: https://git-scm.com/docs/git-push
git push
```

#09_ Instalando o Git Bash no Microsoft Windows 10<br>
```bash
#download do Git para Microsoft Windows
Link de download do Git: https://git-scm.com/download/win
  Standalone Installer: 64-bit Git for Windows Setup.

Abrir a Pasta de Download
  Clicar duas vezes no executável: Git-*-64-bit.exe

  Deseja permitir que este aplicativo faça alterações no seu dispositivo? <Sim>
  Information
    <Next>
  Select Destination Location
    Caminho padrão
    <Next>
  Select Components
    (ON) On the Desktop (ENABLE)
    (ON) Check daily for Git for Windows Update (ENABLE)
    (ON) (NEW!) Add a Git Bash Profile to Windows Terminal (ENABLE)
    <Next>
  Select Start Menu Folder
    Caminho padrão
    <Next>
  Choosing the default editor used by Git
    Use Visual Studio Code as Gits default editor (ENABLE)
    <Next>
  Adjusting the name of the initial branch in new repositories
    (ON) Let Git decide (DEFAULT)
    <Next>
  Adjusting your PATH environment
    (ON) Git from the command line and also from 3rd-party software (DEFAULT)
    <Next>
  Choosing the SSH executable
    (ON) Use bundled OpenSSH (DEFAULT)
    <Next>
  Choosing HTTPS transport backend
    (ON) Use the OpenSSL Library (DEFAULT)
    <Next>
  Configuring the line ending conversions?
    (ON) Checkout Windows-style, commint Unix-style line endings (DEFAULT)
    <Next>
  Configuring the terminal emulator to use Git Bash
    (ON) Use MinTTY (the default terminal of MSYS2) (DEFAULT)
    <Next>
  Choose the default behavior for 'git pull'
    (ON) Fast-forward or merge (DEFAULT)
    <Next>
  Choose a credencial helper
    (ON) Git Credential Manager (DEFAULT)
    <Next>
  Configuring extra options
    (ON) Enable file system caching
    <Next>
  Configuring experimental options
    <Install>
  Completing the Git Setup Wizard
    (ON) Launch Git Bash
    <Finish>
```

#10_ Clonando o Repositório Remoto do Python 3 no Windows 10<br>
```bash
#clonando o Repositório Remoto do Github Localmente
git clone https://github.com/rsvaamonde/python3

#listando o conteúdo clonado
#opção do comando ls: -l (list), -h (human-readable)
ls -lh
```

#11_ Abrindo nosso Repositório Local do Python 3 com o VSCode no Windows 10<br>
```bash
Selecionar o diretório: python3
  Clicar com o botão direito do mouse
    Selecionar: Abrir Com depois: Visual Studio Code
```
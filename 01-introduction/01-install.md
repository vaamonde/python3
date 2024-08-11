#Autor: Robson Vaamonde<br>
#Procedimentos em TI: http://procedimentosemti.com.br<br>
#Bora para Prática: http://boraparapratica.com.br<br>
#Robson Vaamonde: http://vaamonde.com.br<br>
#Facebook Procedimentos em TI: https://www.facebook.com/ProcedimentosEmTi<br>
#Facebook Bora para Prática: https://www.facebook.com/BoraParaPratica<br>
#Instagram Procedimentos em TI: https://www.instagram.com/procedimentoem<br>
#YouTUBE Bora Para Prática: https://www.youtube.com/boraparapratica<br>
#Data de criação: 15/07/2024<br>
#Data de atualização: 11/08/2024<br>
#Versão: 0.07<br>

Conteúdo estudado nessa aula:<br>
#01_ Instalando o Python 3 no Linux Mint (VÁRIAS VERSÕES DE GNU/LINUX)<br>
#02_ Verificando a Versão o Python 3 e PIP instalado no Linux Mint<br>
#03_ Testando o Shell (Prompt) Padrão do Python 3 no Linux Mint<br>
#04_ Testando o Shell (Prompt) do IPython do Python 3 no Linux<br>
#05_ Testando o Shell (Prompt) do BPython do Python 3 no Linux<br>
#06_ Testando o IDLE (Integrated Development Environment for Python) do Python 3 no Linux Mint<br>
#07_ Baixando o Microsoft Visual Studio Code VSCode para o Linux Mint<br>
#08_ Instalando o Microsoft Visual Studio Code VSCode utilizando o Gdebi-Gtk no Linux Mint<br>
#09_ Instalando e Configurando as Principais Extensões Microsoft Visual Studio Code VSCode<br>
#10_ Configurações do VSCode para funcionar perfeitamente no Linux Mint<br>
#11_ Instalando as Extensões do Python 3 no VSCode (Visual Studio Code)<br>

Site Oficial do Python: https://www.python.org/<br>
Site Oficial do PIP: https://pypi.org/<br>
Site Oficial do IPython: https://ipython.org/<br>
Site Oficial do BPython: https://bpython-interpreter.org/<br>
Site Oficial do VSCode: https://code.visualstudio.com/<br>
Site Oficial do Marketing Place do VSCode: https://marketplace.visualstudio.com/vscode<br>
Extensão Oficial do Python para VSCode: https://marketplace.visualstudio.com/items?itemName=ms-python.python

Python é uma linguagem de programação de alto nível, interpretada de script, imperativa, orientada a objetos, funcional, de tipagem dinâmica e forte. Foi lançada por Guido van Rossum em 1991.

IPython é um console interativo avançado para Python. Ele oferece recursos como: Autocompletar, Sintaxe aprimorada, Execução de comandos do sistema, Ferramentas de depuração e Integração com Jupyter Notebook.

BPython é um intérprete interativo para Python, similar ao IPython, mas com foco em simplicidade e usabilidade. Algumas características incluem: Autocompletar avançado, Destacar erros de sintaxe, Histórico de comandos e Inserção de argumentos.

IDE (Integrated Development Environment) é um ambiente de desenvolvimento integrado de software para criar aplicações que combina ferramentas comuns de desenvolvedor em uma única interface de usuário gráfica (GUI - Graphical User Interface).

IDLE (Integrated Development and Learning Environment) é um ambiente de desenvolvimento integrado para Python, que é fornecido com a linguagem desde a versão 2.3. É completamente escrito em Python usando o kit de interface gráfica Tkinter. É uma IDE multiplataforma: Windows, Unix e, MacOS. Ele não é incluso no pacote Python presente em muitas distribuições Linux.

PIP (Package Installation for Python) é um sistema de gerenciamento de pacotes padrão de facto usado para instalar e gerenciar pacotes de software escritos em Python. Muitos pacotes podem ser encontrados na fonte padrão para pacotes e suas dependências - Python Package Index. A maioria das distribuições do Python vem com o pip pré-instalado.

#01_ Instalando o Python 3 no Linux Mint (VÁRIAS VERSÕES DE GNU/LINUX)<br>
```bash
Link de download do Python 3: https://www.python.org/downloads/

#Atualizando as listas do Apt
sudo apt update

#Instalando o Python na versão 3
#OBSERVAÇÃO IMPORTANTE: a opção do IDLE do Python 3 no Linux Mint sempre sofre atualização,
#antes de fazer a sua instalação, verifique a versão com o comando: sudo apt instal idle-python 
#(TAB duas vezes) para ver a última versão ou o comando: sudo apt search idle-python3 que
#lista todas as possibilidades de versões do IDLE do Python 3.
sudo apt install python3 python3-pip idle-python3.12 ipython3 bpython git vim cloc
```

#02_ Verificando a Versão o Python 3 e do PIP instalado no Linux Mint<br>
```bash
#Verificando a versão do Python 3
sudo python3 --version

#Verificando a versão do PIP3 (Package Installer for Python)
sudo pip3 --version
```

#03_ Testando o Shell (Prompt) Padrão do Python 3 no Linux Mint<br>
```bash
#Utilizando o Shell Prompt Padrão Python 3 padrão
python3
```
```python
#Prompt Shell padrão do Python 3 no Linux Mint
#Para sair do Prompt Shell do Python 3 pressione: Ctrl + D
Python 3.10.12 (main, Mar 22 2024, 16:50:05) [GCC 11.4.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>>
```

#04_ Testando o Shell (Prompt) do IPython 3 do Python 3 no Linux<br>
```bash
#Utilizando o Shell Prompt do IPython 3 (Interactive Python)
ipython3
```
```python
#Prompt Shell do IPython 3 no Linux Mint
#Para sair do Prompt Shell do IPython 3 pressione: Ctrl + D ou digite: exit ou quit
Python 3.10.12 (main, Mar 22 2024, 16:50:05) [GCC 11.4.0]
Type 'copyright', 'credits' or 'license' for more information
IPython 7.31.1 -- An enhanced Interactive Python. Type '?' for help.

In [1]:
```

#05_ Testando o Shell (Prompt) do BPython do Python 3 no Linux<br>
```bash
#Utilizando o Shell Prompt do BPython
bpython
```
```python
#Prompt Shell do BPython no Linux Mint
#Para sair do Prompt Shell do BPython pressione: Ctrl + D ou digite: exit() ou quit()
bpython version 0.22.1 on top of Python 3.10.12 /usr/bin/python3
>>>
```

#06_ Testando o IDLE (Integrated Development Environment for Python) do Python 3 no Linux Mint<br>
```bash
#Utilizando o IDLE padrão do Python 3
idle-python3.12
```

#07_ Baixando o Microsoft Visual Studio Code VSCode para o Linux Mint<br>
```bash
Link download: https://code.visualstudio.com/download
  Versão: .deb (Debian, Ubuntu 64 Bits) <Salvar aquivo>
```

#08_ Instalando o Microsoft Visual Studio Code VSCode utilizando o Gdebi-Gtk no Linux Mint<br>
```bash
#instalando em modo gráfico (mais fácil)
Arquivos
  Download
    code_1.*_amd64
      Instalar Pacote
    <Fechar>
```

#09_ Instalando e Configurando as Principais Extensões Microsoft Visual Studio Code VSCode<br>
```bash
#instalação da extensão PT-BR do VSCode
Portuguese (Brazil) Language Pack for Visual Studio Code
  (Sem necessidade de configuração)

#instalação da extensão do Corretor Ortográfico PT-BR e US
Brazilian Portuguese - Code Spell Checker (Corretor Ortográfico de Código)
Manter selecionado a extensão: Brazilian Portuguese - Code Spell Checker
  Pressionar F1
    Show Spell Checker Configuration Info
      User
        Language
          English (en_us)
          Portuguese (pt_br)
          Portuguese - Brazil (pt-br)
            File Types and Programming Languages
              shellscript, python, markdown, etc...
```

#10_ Configurações básicas do Microsoft Visual Studio Code VSCode para funcionar perfeitamente no Linux Mint<br>
```bash
#configuração básica do VSCode para suportar o Python 3
Gerenciar
  Configurações
    Code Spell Checker
      C Spell: Enabled Language Ids: 
        Adicionar Item: shellscript
      C Spell: Language: en,en-US,pt,pt-BR
      C Spell: Max Duplicate Problems: 500000
      C Spell: Max Number Of Problems: 500000
    Editor
      Editor: Tab Size: 2
      Editor: Detect Indentation: False (Off)
      Editor: Insert Spaces: True (On)
      Render Whitespace: All
    Files
      Files: Eol: \n (LF)
```

#11_ Instalando as Extensões do Python 3 no VSCode (Visual Studio Code)<br>
```bash
#A melhor extensão para Python no VSCode é a Python Extension da Microsoft. Ela oferece:
#Autocompletar e IntelliSense, Depurador, Linting, Execução de testes e Jupyter Notebooks.

#Instalando as Extensões do Python 3 no VSCode
VSCode
  Extensões
    Pesquisar:
     Python (Microsoft) <Instalar>
     Python Debugger (Microsoft) <Instalar>
```
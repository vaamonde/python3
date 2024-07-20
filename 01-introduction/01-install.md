#Autor: Robson Vaamonde<br>
#Procedimentos em TI: http://procedimentosemti.com.br<br>
#Bora para Prática: http://boraparapratica.com.br<br>
#Robson Vaamonde: http://vaamonde.com.br<br>
#Facebook Procedimentos em TI: https://www.facebook.com/ProcedimentosEmTi<br>
#Facebook Bora para Prática: https://www.facebook.com/BoraParaPratica<br>
#Instagram Procedimentos em TI: https://www.instagram.com/procedimentoem<br>
#YouTUBE Bora Para Prática: https://www.youtube.com/boraparapratica<br>
#Data de criação: 15/07/2024<br>
#Data de atualização: 17/07/2024<br>
#Versão: 0.03<br>

Conteúdo estudado nessa aula:<br>
#01_ Instalando o Python 3 no Linux Mint (VÁRIAS VERSÕES DE GNU/LINUX)<br>
#02_ Verificando a Versão o Python 3 e PIP instalado no Linux Mint<br>
#03_ Testando o Shell (Prompt) Padrão do Python 3 no Linux Mint<br>
#04_ Testando o Shell (Prompt) do IPython do Python 3 no Linux<br>
#05_ Testando o Shell (Prompt) do BPython do Python 3 no Linux<br>
#06_ Testando o IDLE (Integrated Development Environment for Python) do Python 3 no Linux Mint<br>
#07_ Instalando as Extensões do Python no VSCode (Visual Studio Code)<br>

Site Oficial do Python: https://www.python.org/<br>
Site Oficial do PIP: https://pypi.org/<br>
Site Oficial do IPython: https://ipython.org/<br>
Site Oficial do BPython: https://bpython-interpreter.org/<br>
Site Oficial do VSCode: https://code.visualstudio.com/<br>
Site Oficial do Marketing Place do VSCode: https://marketplace.visualstudio.com/vscode<br>
Extensão Oficial do Python para VSCode: https://marketplace.visualstudio.com/items?itemName=ms-python.python

Python é uma linguagem de programação de alto nível, interpretada de script, imperativa,<br>
orientada a objetos, funcional, de tipagem dinâmica e forte. Foi lançada por Guido van <br>
Rossum em 1991.

IPython é um console interativo avançado para Python. Ele oferece recursos como: Autocompletar,<br>
Sintaxe aprimorada, Execução de comandos do sistema, Ferramentas de depuração e Integração com<br>
Jupyter Notebook.

BPython é um intérprete interativo para Python, similar ao IPython, mas com foco em simplicidade<br>
e usabilidade. Algumas características incluem: Autocompletar avançado, Destacar erros de sintaxe,<br>
Histórico de comandos e Inserção de argumentos.

IDLE é um ambiente de desenvolvimento integrado para Python, que é fornecido com a linguagem desde<br>
a versão 2.3. É completamente escrito em Python usando o kit de interface gráfica Tkinter. É uma IDE<br>
multiplataforma: Windows, Unix e, MacOS. Ele não é incluso no pacote Python presente em muitas<br>
distribuições Linux.

#01_ Instalando o Python 3 no Linux Mint (VÁRIAS VERSÕES DE GNU/LINUX)<br>
```bash
#Atualizando as listas do Apt
sudo apt update

#Instalando o Python na versão 3
sudo apt install python3 idle-python3.10 ipython3 bpython git vim pip
```

#02_ Verificando a Versão o Python 3 e do PIP instalado no Linux Mint<br>
```bash
#Verificando a versão do Python 3
sudo python3 --version

#Verificando a versão do PIP (Package Installer for Python)
sudo pip --version
```

#03_ Testando o Shell (Prompt) Padrão do Python 3 no Linux Mint<br>
```bash
#Utilizando o Shell Python3 padrão
python3
```
```python
#Prompt Shell padrão do Python 3 no Linux Mint
#Para sair do Prompt Shell do Python pressione: Ctrl + D
Python 3.10.12 (main, Mar 22 2024, 16:50:05) [GCC 11.4.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>>
```

#04_ Testando o Shell (Prompt) do IPython do Python 3 no Linux<br>
```bash
#Utilizando o Shell IPython (Interactive Python)
ipython3
```
```python
#Prompt Shell do IPython3 no Linux Mint
#Para sair do Prompt Shell do IPython3 pressione: Ctrl + D ou digite: exit ou quit
Python 3.10.12 (main, Mar 22 2024, 16:50:05) [GCC 11.4.0]
Type 'copyright', 'credits' or 'license' for more information
IPython 7.31.1 -- An enhanced Interactive Python. Type '?' for help.

In [1]:
```

#05_ Testando o Shell (Prompt) do BPython do Python 3 no Linux<br>
```bash
#Utilizando o Shell BPython
bpython
```
```python
#Prompt Shell do BPython no Linux Mint
#Para sair do Prompt Shell do IPython3 pressione: Ctrl + D ou digite: exit() ou quit()
bpython version 0.22.1 on top of Python 3.10.12 /usr/bin/python3
>>>
```

#06_ Testando o IDLE (Integrated Development Environment for Python) do Python 3 no Linux Mint<br>
```bash
#Utilizando o IDLE padrão do Python 3
idle-python3.10
```

#07_ Instalando as Extensões do Python no VSCode (Visual Studio Code)<br>

A melhor extensão para Python no VSCode é a Python Extension da Microsoft. Ela oferece:<br>
Autocompletar e IntelliSense, Depurador, Linting, Execução de testes e Jupyter Notebooks.

```bash
#Instalando a Extensões do Python no VSCode
VSCode
  Extensões
    Pesquisar:
	  Python (Microsoft) <Instalar>
	  Python Debugger (Microsoft) <Instalar>
```
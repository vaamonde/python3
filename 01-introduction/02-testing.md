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
#01_ Testando o Shell (Prompt) Padrão (Default) do Python 3 no Linux Mint<br>
#02_ Testando o Shell (Prompt) IPython do Python 3 no Linux Mint<br>
#03_ Testando o Shell (Prompt) BPython do Python 3 no Linux Mint<br>
#04_ Testando um arquivo Python com Extensão .py no VSCode (Visual Studio Code)<br>
#05_ Testando um arquivo Python com Extensão .py no Terminal<br>

#01_ Testando o Shell (Prompt) Padrão (Default) do Python 3 no Linux Mint<br>
```bash
#Utilizando o Shell Python 3 padrão
python3
```
```python
#Prompt Shell padrão do Python 3 no Linux Mint
#Para sair do Prompt Shell do Python pressione: Ctrl + D
Python 3.10.12 (main, Mar 22 2024, 16:50:05) [GCC 11.4.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>>
```
```python
#Pressionar Ctrl + L limpa o Shell do Python facilitando a digitação

#Primeiro exemplo: enviando dados do valor exato
>>> 10   #Enviando dados na saída padrão da Representação de valor exato
10
>>>

#Segundo exemplo: função de aritmética
>>> 3 + 4   #Função Aritmética simples de adição (símbolo + mais)
7           #Resultado da adição
>>> 

#Terceiro exemplo: digitando strings de texto
>>> "Robson Vaamonde"   #Enviando os dados na saída padrão do valor da String de Texto 
'Robson Vaamonde'
>>>

#Quarto exemplo: criando variáveis estáticas
>>> vaamonde="Robson Vaamonde"   #Declarando o Valor de uma Variável Estática
>>> vaamonde                     #Enviando os dados na saída padrão do valor da variável estática
'Robson Vaamonde'
>>>

#Quint exemplo: concatenando string com variável
>>> "Eu sou: " + vaamonde   #Enviando os dados na saída padrão do valor da String de Texto
'Eu sou: Robson Vaamonde'   #e concatenando com o valor da variável estática vaamonde
>>>

#Sexto exemplo: utilizando o função print()
>>> print("Robson Vaamonde")   #Imprimindo os dados na saída padrão do valor da função PRINT()
Robson Vaamonde
>>>

#Sétimo exemplo: utilizando o função print() com duas opções
>>> print("Eu sou:", vaamonde)   #Imprimindo os dados na saída padrão do valor do função PRINT()
Eu sou: Robson Vaamonde          #mais o valor da variável estática vaamonde
>>> 
```

#02_ Testando o Shell (Prompt) IPython do Python 3 no Linux Mint<br>
```bash
#Utilizando o Shell IPython 3 
ipython3
```
```python
#Prompt Shell padrão do IPython 3 no Linux Mint
#Para sair do Prompt Shell do Python pressione: Ctrl + D ou digite: quit ou exit
Python 3.10.12 (main, Mar 22 2024, 16:50:05) [GCC 11.4.0]
Type 'copyright', 'credits' or 'license' for more information
IPython 7.31.1 -- An enhanced Interactive Python. Type '?' for help.

In [1]:
```
```python
#Pressionar Ctrl + L limpa o Shell do Python facilitando a digitação

#Primeiro exemplo: enviando dados do valor exato
In [1]: 10
Out[1]: 10
In [2]:

#Segundo exemplo: função de aritmética
In [2]: 3 + 4
Out[2]: 7
In [3]:

#Terceiro exemplo: digitando strings de texto
In [3]: "Robson Vaamonde"
Out[3]: 'Robson Vaamonde'
In [4]:

#Quarto exemplo: criando variáveis estáticas
In [4]: vaamonde="Robson Vaamonde"
In [5]: vaamonde
Out[5]: 'Robson Vaamonde'
In [6]:

#Quint exemplo: concatenando string com variável
In [6]: "Eu sou: " + vaamonde
Out[6]: 'Eu sou: Robson Vaamonde'
In [7]:

#Sexto exemplo: utilizando o função print()
In [7]: print("Robson Vaamonde")
Robson Vaamonde
In [8]:

#Sétimo exemplo: utilizando o função print() com duas opções
In [8]: print("Eu sou:", vaamonde)
Eu sou: Robson Vaamonde
In [9]:
```

#03_ Testando o Shell (Prompt) BPython do Python 3 no Linux Mint<br>
```bash
#Utilizando o Shell BPython 
bpython
```
```python
#Prompt Shell padrão do BPython no Linux Mint
#Para sair do Prompt Shell do Python pressione: Ctrl + D ou digite: quit() ou exit()
bpython version 0.22.1 on top of Python 3.10.12 /usr/bin/python3
>>>
```
```python
#Pressionar Ctrl + L limpa o Shell do Python facilitando a digitação

#Primeiro exemplo: enviando dados do valor exato
>>> 10
10
>>>

#Segundo exemplo: função de aritmética
>>> 3 + 4
7
>>>

#Terceiro exemplo: digitando strings de texto
>>> "Robson Vaamonde"
'Robson Vaamonde'
>>>

#Quarto exemplo: criando variáveis estáticas
>>> vaamonde="Robson Vaamonde"
>>> vaamonde 
'Robson Vaamonde'
>>>

#Quint exemplo: concatenando string com variável
>>> "Eu sou: " + vaamonde
'Eu sou: Robson Vaamonde'
>>>

#Sexto exemplo: utilizando o função print()
>>> print("Robson Vaamonde")
Robson Vaamonde
>>>

#Sétimo exemplo: utilizando o função print() com duas opções
>>> print("Eu sou:", vaamonde)
Eu sou: Robson Vaamonde
>>>
```

#04_ Testando um arquivo Python com Extensão .py no VSCode (Visual Studio Code)<br>

A extensão .py indica um arquivo de script Python. Esses arquivos contêm código-fonte<br>
escrito na linguagem Python e podem ser executados pelo interpretador Python para<br>
realizar tarefas.

```python
#Criando um novo arquivo (Ctrl+N) no VSCode chamado: teste.py
#Código simples do Python utilizando a função PRINT()
print("Robson Vaamonde")

#Depurar/Debugar (Erros) processo de encontrar e corrigir erros ou bugs no código
#No VSCode utilizamos a opção F5 para Depurar/Debugar código em Python
F5
  Selecionar o Depurador: Python Debugger (sugerido)
  Configuração da Depuração: Arquivo Python

#Você pode executar o código sem Depurar utilizando a Tecla Ctrl
Ctrl+F5
```

#05_ Testando um arquivo Python com Extensão .py no Terminal<br>
```python
#Criando o arquivo de script em Python no VSCode (mais simples): Ctrl+N
#Cálculo simples de área de um retângulo utilizando as funções INT(), INPUT() e PRINT()
largura = int(input("Digite a largura: "))
altura = int(input("Digite a altura: "))
area = largura * altura
print("A área é", area, "unidades quadradas")

#Salvando o arquivo de script em Python no VSCode: Ctrl+S
#Nome do arquivo do script em Python: arearetangulo.py
#Localização do arquivo de script em Python: ScriptsPython
```
```bash
#Testando o arquivo de script em Python no Terminal: Ctrl_Alt+T
#Diretório dos scripts em Python: /home/vaamonde/Documentos/ScriptsPython
#Acessado o diretório dos script em Python
cd /home/vaamonde/Documentos/ScriptsPython

#Executando o arquivo de script em Python no Terminal
python3 arearetangulo.py
ipython3 arearetangulo.py
bpython arearetangulo.py
```
#Autor: Robson Vaamonde<br>
#Procedimentos em TI: http://procedimentosemti.com.br<br>
#Bora para Prática: http://boraparapratica.com.br<br>
#Robson Vaamonde: http://vaamonde.com.br<br>
#Facebook Procedimentos em TI: https://www.facebook.com/ProcedimentosEmTi<br>
#Facebook Bora para Prática: https://www.facebook.com/BoraParaPratica<br>
#Instagram Procedimentos em TI: https://www.instagram.com/procedimentoem<br>
#YouTUBE Bora Para Prática: https://www.youtube.com/boraparapratica<br>
#Data de criação: 15/07/2024<br>
#Data de atualização: 20/07/2024<br>
#Versão: 0.04<br>

Conteúdo estudado nessa aula:<br>
#01_ Testando o Shell (Prompt) Padrão (Default) do Python 3 no Linux Mint<br>
#02_ Testando o Shell (Prompt) IPython do Python 3 no Linux Mint<br>
#03_ Testando o Shell (Prompt) BPython do Python 3 no Linux Mint<br>
#04_ Testando um arquivo Python com Extensão .py no VSCode (Visual Studio Code)<br>
#05_ Testando um arquivo Python com Extensão .py no Terminal<br>

#01_ Testando o Shell (Prompt) Padrão (Default) do Python 3 no Linux Mint<br>
```bash
#Utilizando o Shell Prompt Padrão do Python 3
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
#Pressionar Ctrl + L limpa o Shell do Python 3 facilitando a digitação

#Primeiro exemplo: enviando dados do valor exato
>>> 10   #Enviando dados na saída padrão da Representação de valor exato
10
>>>

#Segundo exemplo: cálculo de aritmética
>>> 3 + 4   #Cálculo de Aritmética simples de adição (símbolo + mais)
7           #Resultado da adição
>>> 

#Terceiro exemplo: digitando strings de texto
>>> "Robson Vaamonde"   #Enviando dados na saída padrão do valor da String de Texto 
'Robson Vaamonde'
>>>

#Quarto exemplo: criando variáveis estáticas (constantes)
>>> vaamonde="Robson Vaamonde"   #Atribuindo o Valor de uma Variável Estática (constantes)
>>> vaamonde                     #Enviando os dados na saída padrão do valor da variável estática
'Robson Vaamonde'
>>>

#Quinto exemplo: concatenando string com variáveis estáticas (constantes)
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

#02_ Testando o Shell (Prompt) IPython 3 do Python 3 no Linux Mint<br>
```bash
#Utilizando o Shell Prompt do IPython 3 
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

#Segundo exemplo: cálculo de aritmética
In [2]: 3 + 4
Out[2]: 7
In [3]:

#Terceiro exemplo: digitando strings de texto
In [3]: "Robson Vaamonde"
Out[3]: 'Robson Vaamonde'
In [4]:

#Quarto exemplo: criando variáveis estáticas (constantes)
In [4]: vaamonde="Robson Vaamonde"
In [5]: vaamonde
Out[5]: 'Robson Vaamonde'
In [6]:

#Quinto exemplo: concatenando string com variáveis estáticas (constantes)
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
#Utilizando o Shell Prompt do BPython 
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

#Segundo exemplo: cálculo de aritmética
>>> 3 + 4
7
>>>

#Terceiro exemplo: digitando strings de texto
>>> "Robson Vaamonde"
'Robson Vaamonde'
>>>

#Quarto exemplo: criando variáveis estáticas (constantes)
>>> vaamonde="Robson Vaamonde"
>>> vaamonde 
'Robson Vaamonde'
>>>

#Quinto exemplo: concatenando string com variáveis estáticas (constantes)
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

#04_ Testando um arquivo Python 3 com Extensão .py no VSCode (Visual Studio Code)<br>

A extensão .py indica um arquivo de script Python. Esses arquivos contêm código-fonte<br>
escrito na linguagem Python e podem ser executados pelo interpretador Python para<br>
realizar tarefas.

```python
#Criando o arquivo de script em Python 3 no VSCode (mais simples): Ctrl+N
#Código simples do Python utilizando a função PRINT()
print("Robson Vaamonde")

#Depurar/Debugar (Erros) processo de encontrar e corrigir erros ou bugs no código
#No VSCode utilizamos a opção F5 para Depurar/Debugar código em Python
F5
  Selecionar o Depurador: Python Debugger (sugerido)
  Configuração da Depuração: Arquivo Python

#Você pode executar o código sem Depurar utilizando a Tecla Ctrl+F5
Ctrl+F5

#Salvando o arquivo de script em Python 3 no VSCode: Ctrl+S
#Nome do arquivo de script em Python: 01-teste.py
#Localização do arquivo de script em Python: ScriptsPython
```

#05_ Testando um arquivo Python 3 com Extensão .py no Terminal<br>
```python
#Criando o arquivo de script em Python 3 no VSCode (mais simples): Ctrl+N
#Cálculo simples da área de um retângulo utilizando as funções INT(), INPUT() e PRINT()
largura = int(input("Digite a largura: "))          #Obtendo o valor da largura e atribuindo a variável largura
altura = int(input("Digite a altura: "))            #Obtendo o valor da altura e atribuindo a variável altura
area = largura * altura                             #Calculando a área do retângulo e atribuindo a variável area
print("A área é", area, "unidades quadradas")       #Imprimindo o valor na area na saída padrão

#Salvando o arquivo de script em Python 3 no VSCode: Ctrl+S
#Nome do arquivo de script em Python: 02-area_retangulo.py
#Localização do arquivo de script em Python: ScriptsPython
```
```bash
#Testando o arquivo de script em Python 3 no Terminal: Ctrl+Alt+T
#Diretório dos scripts em Python: /home/vaamonde/Documentos/ScriptsPython
#Acessando o diretório dos script em Python 3 no Linux Mint
cd /home/vaamonde/Documentos/ScriptsPython

#Executando o arquivo de script em Python 3 no Terminal
python3 02-area_retangulo.py
ipython3 02-area_retangulo.pyy
bpython 02-area_retangulo.py
```

#06_ Utilizando o Shebang no arquivo Python 3 com Extensão .py no Terminal<br>
```python
#Criando o arquivo de script em Python 3 no VSCode (mais simples): Ctrl+N
#Cálculo simples de idade utilizando as funções INT(), INPUT() e PRINT()

#!/usr/bin/python3
ano_atual=int(input("Digite o Ano Atual: "))
ano_nasc=int(input("Digite o Ano do seu Nascimento: "))
idade=int(ano_atual - ano_nasc)
print()
print("Sua idade é:", idade, "anos")

#Salvando o arquivo de script em Python 3 no VSCode: Ctrl+S
#Nome do arquivo de script em Python: 03-idade_simples.py
#Localização do arquivo de script em Python: ScriptsPython
```
```bash
#Testando o arquivo de script em Python 3 no Terminal: Ctrl+Alt+T
#Diretório dos scripts em Python: /home/vaamonde/Documentos/ScriptsPython
#Acessando o diretório dos script em Python 3 no Linux Mint
cd /home/vaamonde/Documentos/ScriptsPython

#Executando o arquivo de script em Python 3 no Terminal
bash 03-idade_simples.py

#Alterando as permissões do arquivo de script em Python 3 no Terminal
#opção do comando chmod: + (added operator), x (execute)
chmod +x 03-idade_simples.py

#Executando o arquivo de script em Python 3 no Terminal
./03-idade_simples.py
```
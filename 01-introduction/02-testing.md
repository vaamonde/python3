#Autor: Robson Vaamonde<br>
#Procedimentos em TI: http://procedimentosemti.com.br<br>
#Bora para Prática: http://boraparapratica.com.br<br>
#Robson Vaamonde: http://vaamonde.com.br<br>
#Facebook Procedimentos em TI: https://www.facebook.com/ProcedimentosEmTi<br>
#Facebook Bora para Prática: https://www.facebook.com/BoraParaPratica<br>
#Instagram Procedimentos em TI: https://www.instagram.com/procedimentoem<br>
#YouTUBE Bora Para Prática: https://www.youtube.com/boraparapratica<br>
#Data de criação: 15/07/2024<br>
#Data de atualização: 18/08/2024<br>
#Versão: 0.07<br>

Python3 é o interpretador padrão Python geralmente é instalado em: /usr/local/bin/python3.x nas máquinas onde está disponível. Os recursos de edição de linha do interpretador incluem edição interativa, substituição de histórico e conclusão de código em sistemas que suportam a biblioteca GNU Readline.

IPython é um console interativo avançado para Python. Ele oferece recursos como: Autocompletar, Sintaxe aprimorada, Execução de comandos do sistema, Ferramentas de depuração e Integração com Jupyter Notebook.

BPython é um intérprete interativo para Python, similar ao IPython, mas com foco em simplicidade e usabilidade. Algumas características incluem: Autocompletar avançado, Destacar erros de sintaxe, Histórico de comandos e Inserção de argumentos.

IDLE (Integrated Development and Learning Environment) é um ambiente de desenvolvimento integrado para Python, que é fornecido com a linguagem desde a versão 2.3. É completamente escrito em Python usando o kit de interface gráfica Tkinter. É uma IDE multiplataforma: Windows, Unix e, MacOS. Ele não é incluso no pacote Python presente em muitas distribuições Linux.

O Visual Studio Code é um editor de código-fonte desenvolvido pela Microsoft para Windows, Linux e macOS. Ele inclui suporte para depuração, controle de versionamento Git incorporado, realce de sintaxe, complementação inteligente de código, snippets e refatoração de código.

Conteúdo estudado nessa aula:<br>
#01_ Testando o Shell (Prompt) Padrão (Default) do Python 3 no Linux Mint<br>
#02_ Testando o Shell (Prompt) IPython do Python 3 no Linux Mint<br>
#03_ Testando o Shell (Prompt) BPython do Python 3 no Linux Mint<br>
#04_ Testando IDLE do Python 3 no Linux Mint<br>
#05_ Testando um arquivo Python com Extensão .py no VSCode (Visual Studio Code)<br>
#06_ Testando um arquivo Python com Extensão .py no Terminal<br>
#07_ Utilizando o Shebang no arquivo Python 3 com Extensão .py no Terminal<br>

#01_ Testando o Shell (Prompt) Padrão (Default) do Python 3 no Linux Mint<br>
```bash
#Utilizando o Prompt Shell Padrão do Python 3
python3
```
```python
#Prompt Shell padrão do Python 3 no Linux Mint
#Para sair do Prompt Shell do Python 3 pressione: Ctrl + D
Python 3.10.12 (main, Mar 22 2024, 16:50:05) [GCC 11.4.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>>
```
```python
#Pressione: Ctrl + L para limpar o Shell do Python 3 facilitando a digitação

#Primeiro exemplo: enviando dados do valor exato
>>> 10   #Enviando dados na saída padrão da Representação de valor exato
10
>>>

#Segundo exemplo: cálculo de aritmética
>>> 3 + 4   #Cálculo de Aritmética simples de adição (símbolo + mais)
7           #Resultado da adição
>>> 

#Terceiro exemplo: digitando strings de texto
#OBSERVAÇÃO IMPORTANTE: VOCÊ PODE USAR ASPAS SIMPLES ' ' (CONHECIDO COMO APÓSTROFO) OU
#ASPAS DUPLAS " " (NÃO CONFUNDIR COM DUAS ASPAS SIMPLES) PARA DEFINIR STRINGS NO PYTHON,
#VARIÁVEIS SIMPLES, IDENTIFICADORES OU ATRIBUTOS É INDICADO USAR AS SIMPLES, PARA TEXTOS 
#LONGOS ASPAS DUPLAS QUE PERMITI O USO DE ASPAS SIMPLES DENTRO DO TEXTO.
>>> "Robson Vaamonde"   #Enviando dados na saída padrão do valor da String de Texto 
'Robson Vaamonde'
>>>

#Quarto exemplo: criando variáveis estáticas (constantes)
>>> vaamonde='Robson Vaamonde'   #Atribuindo o Valor de uma Variável Estática (constantes)
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
#Utilizando o Prompt Shell do IPython 3 
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
In [4]: vaamonde='Robson Vaamonde'
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
#Utilizando o Prompt Shell do BPython 
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
>>> vaamonde='Robson Vaamonde'
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

#04_ Testando IDLE do Python 3 no Linux Mint<br>
```bash
#Utilizando IDLE do Python 3
idle-python3.12
```
```python
Python 3.9.5 (default, Nov 23 2021, 15:27:38) 
[GCC 9.3.0] on linux
Type "help", "copyright", "credits" or "license()" for more information.
>>>
```
```python
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
>>> vaamonde='Robson Vaamonde'   #Atribuindo o Valor de uma Variável Estática (constantes)
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
```python
File
  New File (Ctrl+N)

#Oitavo exemplo: utilizando a função print() com duas variáveis
valor01 = 10   #Atribuindo o Valor de uma Variável Estática (constantes)
valor02 = 20   #Atribuindo o Valor de uma Variável Estática (constantes)
print(valor01 + valor02)   #Imprimindo os dados na saída padrão do valor do função PRINT()

#Salvando o arquivo de script em Python 3 no IDLE: Ctrl+S
#Nome do arquivo de script em Python: 00-teste.py
#Localização do arquivo de script em Python: ScriptsPython
File
  Save (Ctrl+S)
    00-teste.py
      <Save>

#Executando o script no IDLE do Python 3
Run
  Run Module (F5)
```

#05_ Testando um arquivo Python 3 com Extensão .py no VSCode (Visual Studio Code)<br>
```bash
#A extensão .py indica um arquivo de script Python. Esses arquivos contêm código-fonte
#escrito na linguagem Python e podem ser executados pelo interpretador Python para
#realizar tarefas.
```
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

#Você também pode executar o código Python direto via Run Python File
<Run Python File>

#Salvando o arquivo de script em Python 3 no VSCode: Ctrl+S
#Nome do arquivo de script em Python: 01-teste.py
#Localização do arquivo de script em Python: ScriptsPython
```

#06_ Testando um arquivo Python 3 com Extensão .py no Terminal<br>
```python
#Criando o arquivo de script em Python 3 no VSCode (mais simples): Ctrl+N
#Cálculo simples da área de um retângulo utilizando as funções INT(), INPUT() e PRINT()

#Atribuindo os valores nas variáveis dinâmicas
base = int(input("Digite o valor da base: "))
largura = int(input("Digite o valor da largura: "))

#Calculando a área do retângulo e atribuindo o valor a variável area
area = base * largura

#Imprimindo o valor da area na saída padrão
print("A área do retângulo é", area, "unidades quadradas")   

#Salvando o arquivo de script em Python 3 no VSCode: Ctrl+S
#Nome do arquivo de script em Python: 02-area_retangulo.py
#Localização do arquivo de script em Python: ScriptsPython
```
```bash
#Testando o arquivo de script em Python 3 no Terminal: Ctrl+Alt+T
#Diretório dos scripts em Python: /home/vaamonde/Documentos/python3/ScriptsPython
#Acessando o diretório dos script em Python 3 no Linux Mint
cd /home/vaamonde/Documentos/python3/ScriptsPython

#Executando o arquivo de script em Python 3 no Terminal
python3 02-area_retangulo.py
ipython3 02-area_retangulo.pyy
bpython 02-area_retangulo.py
```

#07_ Utilizando o Shebang no arquivo Python 3 com Extensão .py no Terminal<br>
```bash
#Mais precisamente, uma linha shebang consiste de um cerquilha e um ponto de exclamação
#("#!"), em seguida, opcionalmente, qualquer quantidade de espaços em branco, seguidos 
#pelo endereço (absoluto) para o interpretador.
```
```python
#Criando o arquivo de script em Python 3 no VSCode (mais simples): Ctrl + N (New)
#Cálculo simples de idade utilizando as funções INT(), INPUT() e PRINT()

#!/usr/bin/python3
ano_atual=int(input("Digite o Ano Atual: "))
ano_nasc=int(input("Digite o Ano do seu Nascimento: "))
idade=int(ano_atual - ano_nasc)
print()
print("Sua idade é:", idade, "anos")

#Salvando o arquivo de script em Python 3 no VSCode: Ctrl + S (Save)
#Nome do arquivo de script em Python: 03-idade_simples.py
#Localização do arquivo de script em Python: ScriptsPython
```
```bash
#Testando o arquivo de script em Python 3 no Terminal: Ctrl + Alt + T (Terminal)
#Diretório dos scripts em Python: /home/vaamonde/Documentos/python3/ScriptsPython
#Acessando o diretório dos script em Python 3 no Linux Mint
cd /home/vaamonde/Documentos/python3/ScriptsPython

#Executando o arquivo de script em Python 3 no Terminal
bash 03-idade_simples.py

#Alterando as permissões do arquivo de script em Python 3 no Terminal
#opção do comando chmod: + (added operator), x (execute)
chmod +x 03-idade_simples.py

#Executando o arquivo de script em Python 3 no Terminal
#opção dos caracteres ./ (dot slash): serve para indicar o caminho do executável; 
#o ponto significa diretório atual; a barra serve para separar o diretório do 
#nome do arquivo
./03-idade_simples.py
```
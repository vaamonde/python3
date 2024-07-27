#Autor: Robson Vaamonde<br>
#Procedimentos em TI: http://procedimentosemti.com.br<br>
#Bora para Prática: http://boraparapratica.com.br<br>
#Robson Vaamonde: http://vaamonde.com.br<br>
#Facebook Procedimentos em TI: https://www.facebook.com/ProcedimentosEmTi<br>
#Facebook Bora para Prática: https://www.facebook.com/BoraParaPratica<br>
#Instagram Procedimentos em TI: https://www.instagram.com/procedimentoem<br>
#YouTUBE Bora Para Prática: https://www.youtube.com/boraparapratica<br>
#Data de criação: 16/07/2024<br>
#Data de atualização: 27/07/2024<br>
#Versão: 0.04<br>

Conteúdo estudado nessa aula:<br>
#01_ Analisando Erros em Variáveis no Python 3 no Linux Mint<br>
#02_ Analisando Erros de Nome de Variáveis no Python 3 no Linux Mint<br>
#03_ Analisando Erros de Falta de Argumento no Python 3 no Linux Mint<br>
#04_ Analisando Erros de Conversão no Python 3 no Linux Mint<br>
#05_ Analisando Erros de Case-Sensitive no Python 3 no Linux Mint<br>
#06_ Analisando Erros de Aspas no Python 3 no Linux Mint<br>
#07_ Analisando Erros de Concatenação de String do Python 3 no Linux Mint<br>
#08_ Analisado Erros de Algebra Aritmética com Cálculos de Divisão do Python 3 no Linux Mint<br>

#01_ Analisando Erros de Recuo Inesperado do Python 3 no Linux Mint<br>
```python
#Primeiro exemplo: recuo/alinhamento errado (utilizar o VSCode mais simples)
#Salvar o arquivo de script com o nome: 04-erro_variavel.py no diretório: ScriptsPython
#Executar o script com a opção: F5 ou Ctrl+F5 ou clicar no ícone: Run Python File
comprimento = int(input("Digite o comprimento: "))
 print(conprimento)

#Analisando a Primeira Mensagem do Erro do script em Python
  File "/home/vaamonde/Documentos/ScriptsPython/04-erro_variavel.py", line 2   #Indica onde encontrou o erro e parou o script
    print(conprimento)
IndentationError: unexpected indent   #Indica um erro de recuo inesperado
```

#02_ Analisando Erros de Nome de Variáveis do Python 3 no Linux Mint<br>
```python
#Analisando a Segunda Mensagem do Erro do script em Python
Traceback (most recent call last):
  File "/home/vaamonde/Documentos/ScriptsPython/04-erro_variavel.py", line 2, in <module>   #Indica onde encontrou o erro e parou o script
    print(conprimento)
NameError: name 'conprimento' is not defined. Did you mean: 'comprimento'?   #Indica que o nome da variável não está definido
```
#03_ Analisando Erros de Sintaxe Inválida do Python 3 no Linux Mint<br>
```python
#Segundo exemplo: sintaxe inválida (utilizar o VSCode mais simples)
#Salvar o arquivo de script com o nome: 05-erro_argumento.py no diretório: ScriptsPython
#Executar o script com a opção: F5 ou Ctrl+F5 ou clicar no ícone: Run Python File
somatoria = 3 +
print(somatoria)

#Analisando a Mensagem de Erro do script em Python
  File "/home/vaamonde/Documentos/ScriptsPython/05-erro_argumento.py", line 1   #Indica onde encontrou o erro e parou o script
    somatoria = 3 +
                   ^
SyntaxError: invalid syntax   #Indica que a sintaxe é inválida mostrando onde está o erro no simbolo de ^ (circunflexo)
```

#04_ Analisando Erros de Conversão do Python 3 no Linux Mint<br>
```python
#Terceiro exemplo: valor literal inválido (utilizar o VSCode mais simples)
#Salvar o arquivo de script com o nome: 06-erro_inteiro.py no diretório: ScriptsPython
#Executar o script com a opção: F5 ou Ctrl+F5 ou clicar no ícone: Run Python File
suaidade = int(input("Digite a sua idade: ")) 
print("Sua idade é:", suaidade)

#Analisando a Mensagem de Erro do script em Python
Traceback (most recent call last):
  File "/home/vaamonde/Documentos/ScriptsPython/06-erro_inteiro.py", line 1, in <module>   #Indica onde encontrou o erro e parou o script
    suaidade = int(input("Digite a sua idade: ")) 
ValueError: invalid literal for int() with base 10: '45.5'   #Indica que é um valor inválida literal para base 10
```

#05_ Analisando Erros de Case-Sensitive do Python 3 no Linux Mint<br>
```python
#Quarto exemplo: erro de digitação de Case-Sensitive (utilizar o VSCode mais simples)
#Salvar o arquivo de script com o nome: 07-erro_case.py no diretório: ScriptsPython
#Executar o script com a opção: F5 ou Ctrl+F5 ou clicar no ícone: Run Python File
import sys
Print("Versão do Python é:", sys.version)

#Analisando a Mensagem de Erro do script em Python
Traceback (most recent call last):
  File "/home/vaamonde/Documentos/ScriptsPython/07-erro_variavel.py", line 2, in <module>   #Indica onde encontrou o erro e parou o script
    Print("Versão do Python é:", sys.version)
NameError: name 'Print' is not defined. Did you mean: 'print'?   #Indica que o nome da função não é definida
```

#06_ Analisando Erros de Aspas do Python 3 no Linux Mint<br>
```python
#Quinto exemplo: abrir e fechar Aspas (utilizar o VSCode mais simples)
#Salvar o arquivo de script com o nome: 08-erro_aspas.py no diretório: ScriptsPython
#Executar o script com a opção: F5 ou Ctrl+F5 ou clicar no ícone: Run Python File
suaidade = int(input(Digite a sua idade: )) 
print("Sua idade é:", suaidade)

#Analisando a Mensagem de Erro do script em Python
  File "/home/vaamonde/Documentos/ScriptsPython/08-erro_variavel.py", line 1   #Indica onde encontrou o erro e parou o script
    suaidade = int(input(Digite a sua idade: )) 
                         ^^^^^^^^
SyntaxError: invalid syntax. Perhaps you forgot a comma?   #Indica que a sintaxe é inválida mostrando onde está o erro no simbolo de ^ (circunflexo)
```

#07_ Analisando Erros de Concatenação de String do Python 3 no Linux Mint<br>
```python
#Sexto exemplo: concatenar string do números (utilizar o VSCode mais simples)
#Salvar o arquivo de script com o nome: 09-erro_concatenar.py no diretório: ScriptPython
#Executar o script com a opção: F5 ou Ctrl+F5 ou clicar no ícone: Run Python File
seu_nome = "Robson Vaamonde"
sua_idade = 45
print("Seu nome e sua idade é: ", seu_nome+sua_idade)

#Analisando a Mensagem de Erro do script em Python
Traceback (most recent call last):
  File "/home/vaamonde/Documentos/ScriptsPython/logical_expressions.py", line 3, in <module>   #Indica onde encontrou o erro e parou o script
    print("Seu nome e sua idade é: ", seu_nome+sua_idade)
TypeError: can only concatenate str (not "int") to str   #Indica que a opção só pode concatenar com string
```

#08_ Analisado Erros de Algebra Aritmética com Cálculos de Divisão do Python 3 no Linux Mint<br>
```python
#Sétimo exemplo: cálculo de divisão por 0 (zero) (utilizar o VSCode mais simples)
#Salvar o arquivo de script com o nome: 10-erro_calculo.py no diretório: ScriptPython
#Executar o script com a opção: F5 ou Ctrl+F5 ou clicar no ícone: Run Python File
salario = 1000
prestacao = 0
print("Seu salário é de: ", salario, "Você vai dividir em: ", prestacao, "vezes o valor de: ", (salario / prestacao))

#Analisando a Mensagem de Erro do script em Python
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>   #Indica onde encontrou o erro e parou o script
ZeroDivisionError: division by zero   #Indica que não pode dividir por zero
>>>
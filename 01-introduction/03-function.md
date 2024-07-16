#Autor: Robson Vaamonde<br>
#Procedimentos em TI: http://procedimentosemti.com.br<br>
#Bora para Prática: http://boraparapratica.com.br<br>
#Robson Vaamonde: http://vaamonde.com.br<br>
#Facebook Procedimentos em TI: https://www.facebook.com/ProcedimentosEmTi<br>
#Facebook Bora para Prática: https://www.facebook.com/BoraParaPratica<br>
#Instagram Procedimentos em TI: https://www.instagram.com/procedimentoem<br>
#YouTUBE Bora Para Prática: https://www.youtube.com/boraparapratica<br>
#Data de criação: 16/07/2024<br>
#Data de atualização: 16/07/2024<br>
#Versão: 0.01<br>

Conteúdo estudado nessa aula:<br>

Site Oficial do Python: https://www.python.org/

Python é uma linguagem de programação de alto nível, interpretada de script, imperativa,<br>
orientada a objetos, funcional, de tipagem dinâmica e forte. Foi lançada por Guido van <br>
Rossum em 1991.

#03_ Função Print() do Python 3 no Linux Mint<br>
```python
#Pressionar Ctrl + L limpa o Shell do Python facilitando a digitação

#Primeiro exemplo: utilizando o função print()
>>> print("Robson Vaamonde")   #Enviando os dados na saída padrão do valor da função PRINT()
Robson Vaamonde                #e criando uma nova linha
>>>

#Segundo exemplo: utilizando a função print() junto com end
>>> print("Robson Vaamonde", end = "")  #Enviado os dados na saída padrão do valor da função PRINT()
Robson Vaamonde>>>                      #e continuando na mesma linha com a expressão END

#Terceiro exemplo: utilizando variável estática e a função input()
>>> nome = input("Digite o seu nome: ")   #Criando a variável estática e recebendo o argumento da função INPUT()
Digite o seu nome: Robson Vaamonde        #Processamento da função INPUT() e digitando o valor a ser atribuído na variável
>>> nome                                  #Enviando os dados na saída padrão do valor da variável estática
'Robson Vaamonde'

#Quarto exemplo: utilizando variável estática junto com as funções input() e print()
>>> cidade = input("Qual a sua Cidade? ")   #Criando a variável estática e recebendo o argumento da função INPUT()
Qual a sua Cidade: São Paulo                #Processamento da função INPUT() digitando o valor a ser atribuído na variável
>>> print(cidade)                           #Enviando os dados na saída padrão do valor da função PRINT()
São Paulo
>>>

#Quinto exemplo: utilizando variáveis estáticas junto com as funções int(), input() e print() para cálculo de aritmética
>>> anoatual = 2024   #Criando a variável estática e recebendo o valor inteiro/numérico
>>> suaidade = int(input("Qual ano você nasceu? "))  #Criando a variável estática e recebendo o argumento da função INPUT() convertendo para Inteiro com a função INT()
Qual ano você nasceu? 1979   #Processamento da função INPUT() digitando o valor a ser convertido para inteiro INT() e atribuído na variável
>>> print("Sua idade é:", anoatual - suaidade, "anos")  #Enviando os dados na saída padrão da função PRINT()
Sua idade é: 45 anos
>>>

#Sexto exemplo: utilizando variáveis estáticas junto com as funções float(), input e print para cálculo de aritmética
>>> produto = 10.50   #Criando a variável estática e recebendo o valor numérico de ponto flutuante (decimal)
>>> recebido = float(input("Qual valor for recebido? "))   #Criando a variável estática e recebendo o argumento da função INPUT() convertendo para Decimal com a função FLOAT()
Qual valor for recebido? 20.00   #Processamento da função INPUT() digitando o valor a ser convertido para decimal FLOAT() e atribuído na variável
>>> print("Troco: ", produto - recebido)   #Enviando os dados na saída padrão da função PRINT()
Troco:  -9.5
>>>
```

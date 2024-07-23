#Autor: Robson Vaamonde<br>
#Procedimentos em TI: http://procedimentosemti.com.br<br>
#Bora para Prática: http://boraparapratica.com.br<br>
#Robson Vaamonde: http://vaamonde.com.br<br>
#Facebook Procedimentos em TI: https://www.facebook.com/ProcedimentosEmTi<br>
#Facebook Bora para Prática: https://www.facebook.com/BoraParaPratica<br>
#Instagram Procedimentos em TI: https://www.instagram.com/procedimentoem<br>
#YouTUBE Bora Para Prática: https://www.youtube.com/boraparapratica<br>
#Data de criação: 16/07/2024<br>
#Data de atualização: 20/07/2024<br>
#Versão: 0.02<br>

Conteúdo estudado nessa aula:<br>
#01_ Função Print() do Python 3 no Linux Mint<br>
#02_ Função Input() do Python 3 no Linux Mint<br>
#03_ Funções Int() e Float() do Python 3 no Linux Mint<br>
#04_ Funções ROUND() e STR() do Python 3 no Linux Mint<br>

#01_ Função Print() do Python 3 no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/ref_func_print.asp
```python
#Pressionar Ctrl + L limpa o Shell do Python 3 facilitando a digitação
#Você pode utilizar o TAB (Tabulador) para facilitar a digitação das funções

#Primeiro exemplo: utilizando o função print()
>>> print("Robson Vaamonde")   #Imprimindo os dados na saída padrão do valor da função PRINT()
Robson Vaamonde                #e criando uma nova linha
>>>

#Segundo exemplo: utilizando a função print() junto com end
>>> print("Robson Vaamonde", end = "")  #Imprimindo os dados na saída padrão do valor da função PRINT()
Robson Vaamonde>>>                      #e continuando na mesma linha com a expressão END
```

#02_ Função Input() do Python 3 no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/ref_func_input.asp
```python
#Terceiro exemplo: utilizando variável dinâmica e a função input()
>>> nome = input("Digite o seu nome: ")   #Criando a variável dinâmica e recebendo o argumento da função INPUT()
Digite o seu nome: Robson Vaamonde        #Processamento da função INPUT() e digitando do valor a ser atribuído na variável nome
>>> nome                                  #Enviando os dados na saída padrão do valor da variável dinâmica
'Robson Vaamonde'

#Quarto exemplo: utilizando variável dinâmica junto com as funções input() e print()
>>> cidade = input("Qual a sua Cidade? ")   #Criando a variável dinâmica e recebendo o argumento da função INPUT()
Qual a sua Cidade: São Paulo                #Processamento da função INPUT() e digitando o valor a ser atribuído na variável cidade
>>> print(cidade)                           #Imprimindo os dados na saída padrão do valor da função PRINT()
São Paulo
>>>
```

#03_ Funções Int() e Float() do Python 3 no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/ref_func_int.asp<br>
Link de apoio: https://www.w3schools.com/python/ref_func_float.asp
```python
#Quinto exemplo: utilizando variáveis dinâmica junto com as funções int(), input() e print() para cálculo de aritmética
>>> anoatual = 2024                                     #Criando a variável dinâmica e atribuindo o valor inteiro/numérico
>>> suaidade = int(input("Qual ano você nasceu? "))     #Criando a variável dinâmica e recebendo o argumento da função INPUT() convertendo para Inteiro com a função INT()
Qual ano você nasceu? 1979                              #Processamento da função INPUT() e digitando o valor a ser convertido para inteiro INT() e atribuído na variável suaidade
>>> print("Sua idade é:", anoatual - suaidade, "anos")  #Imprimindo os dados na saída padrão da função PRINT() e subtraindo as variáveis anoatual - suaidade
Sua idade é: 45 anos
>>>

#Sexto exemplo: utilizando variáveis dinâmica junto com as funções float(), input() e print() para cálculo de aritmética
>>> produto = 10.50                                        #Criando a variável dinâmica e atribuindo o valor numérico de ponto flutuante (decimal)
>>> recebido = float(input("Qual valor foi recebido? "))   #Criando a variável dinâmica e recebendo o argumento da função INPUT() convertendo para Decimal com a função FLOAT()
Qual valor foi recebido? 20.00                             #Processamento da função INPUT() e digitando o valor a ser convertido para decimal FLOAT() e atribuído na variável recebido
>>> print("Troco: ", produto - recebido)                   #Imprimindo os dados na saída padrão da função PRINT() e subtraindo as variáveis produto - recebido
Troco:  -9.5
>>>
```

#04_ Funções ROUND() e STR() do Python 3 no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/ref_func_round.asp<br>
Link de apoio: https://www.w3schools.com/python/ref_func_str.asp
```python
#Sétimo exemplo: utilizando variáveis constante e dinâmica junto com as funções float(), input(), print(), str(), round() e int() para cálculo de aritmética
>>> saldo_inicial = 35.45                                          #Criando a variável constante e atribuindo o valor numérico de ponto flutuante (decimal)
>>> deposito = float(input("Digite o valor a ser depositado: "))   #Criando a variável dinâmica e atribuindo o valor numérico de ponto flutuante (decimal)
Digite o valor a ser depositado: 33.33                             #Processamento da função INPUT() e digitando o valor a ser convertido para decimal (FLOAT) e atribuído a variável deposito
>>> saldo_final = (saldo_inicial + deposito)                       #Criando a variável dinâmica e atribuindo o cálculo aritmético de substração das variáveis
>>> saldo_final                                                    #Processamento da variável e impressão do valores na tela
68.78                                                              #Valor da variável dinâmica saldo_final
#Imprimindo os dados na saída padrão da função PRINT() e convertendo para String com a função STR(), arredondado para maior com a função ROUND() e Inteiro com a função INT()
>>> print("Seu saldo é:", "R$: " + str(saldo_final), "Arredondando para maior:", round(saldo_final), "Seu inteiro é:", int(saldo_final))
Seu saldo é: R$: 68.78 Arredondado para maior: 69 Seu inteiro é: 68
>>> 
```
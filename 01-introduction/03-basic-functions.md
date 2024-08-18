#Autor: Robson Vaamonde<br>
#Procedimentos em TI: http://procedimentosemti.com.br<br>
#Bora para Prática: http://boraparapratica.com.br<br>
#Robson Vaamonde: http://vaamonde.com.br<br>
#Facebook Procedimentos em TI: https://www.facebook.com/ProcedimentosEmTi<br>
#Facebook Bora para Prática: https://www.facebook.com/BoraParaPratica<br>
#Instagram Procedimentos em TI: https://www.instagram.com/procedimentoem<br>
#YouTUBE Bora Para Prática: https://www.youtube.com/boraparapratica<br>
#Data de criação: 16/07/2024<br>
#Data de atualização: 18/08/2024<br>
#Versão: 0.05<br>

A) Strings em Python são colocadas entre aspas simples ou duplas, exemplo: 'olá' é o mesmo que "olá".<br>
B) A função print() imprime a mensagem especificada na tela ou em outro dispositivo de saída padrão.<br>
C) A função input() permite a entrada de dados pelo usuário.<br>
D) A função int() converte o valor especificado em um número inteiro.<br>
E) A função float() converte o valor especificado em um número de ponto flutuante.<br>
F) A função round() retorna um número de ponto flutuante que é uma versão arredondada do número especificado, com o número especificado de decimais. O número padrão de decimais é 0, o que significa que a função retornará o número inteiro mais próximo.<br>
G) A função str() converte o valor especificado em uma string (Texto).<br>

Conteúdo estudado nessa aula:<br>
#01_ Função Print() do Python 3 no Linux Mint<br>
#02_ Função Input() do Python 3 no Linux Mint<br>
#03_ Funções Int() e Float() do Python 3 no Linux Mint<br>
#04_ Funções ROUND() e STR() do Python 3 no Linux Mint<br>

#01_ Função Print() do Python 3 no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/python_strings.asp<br>
Link de apoio: https://www.w3schools.com/python/ref_func_print.asp
```python
#Pressione: Ctrl + L para limpar o Shell do Python 3 facilitando a digitação
#Você pode utilizar o TAB (Tabulador) para facilitar a digitação das funções

#Primeiro exemplo: utilizando o função print()
#Imprimindo os dados na saída padrão do valor da função PRINT() e criando uma nova linha
>>> print("Robson Vaamonde")
Robson Vaamonde
>>>

#Segundo exemplo: utilizando a função print() junto com o Parâmetro end
#Imprimindo os dados na saída padrão do valor da função PRINT() e continuando na mesma linha
>>> print("Robson Vaamonde", end = "")
Robson Vaamonde>>>
```

#02_ Função Input() do Python 3 no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/ref_func_print.asp<br>
Link de apoio: https://www.w3schools.com/python/ref_func_input.asp<br>
Link de apoio: https://www.w3schools.com/python/python_strings.asp
```python
#Terceiro exemplo: utilizando variável dinâmica e a função input()
#Criando a variável dinâmica e recebendo o argumento da função INPUT()
>>> nome = input("Digite o seu nome: ")

#Processamento da função INPUT() e atribuir o valor na variável nome
Digite o seu nome: Robson Vaamonde

#Enviando os dados na saída padrão do valor da variável dinâmica
>>> nome
'Robson Vaamonde'

#Quarto exemplo: utilizando variável dinâmica junto com as funções input() e print()
#Criando a variável dinâmica e recebendo o argumento da função INPUT()
>>> cidade = input("Qual a sua Cidade? ")

#Processamento da função INPUT() e atribuir o valor na variável cidade
Qual a sua Cidade: São Paulo

#Imprimindo os dados na saída padrão do valor da função PRINT()
>>> print(cidade)
São Paulo
>>>
```

#03_ Funções Int() e Float() do Python 3 no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/ref_func_print.asp<br>
Link de apoio: https://www.w3schools.com/python/ref_func_input.asp<br>
Link de apoio: https://www.w3schools.com/python/python_strings.asp<br>
Link de apoio: https://www.w3schools.com/python/ref_func_int.asp<br>
Link de apoio: https://www.w3schools.com/python/ref_func_float.asp
```python
#Quinto exemplo: utilizando variáveis dinâmica junto com as funções int(), input() e print()
#Atribuindo o valor inteiro/numérico na variável anoatual
>>> anoatual = 2024

#Atribuindo o valor na variável dinâmica com a função INPUT() convertendo para Inteiro com a
#função INT()
>>> suaidade = int(input("Qual ano você nasceu? "))

#Processamento da função INPUT(), digitação do valor e conversão para inteiro INT()
Qual ano você nasceu? 1979

#Imprimindo os dados na saída padrão da função PRINT() e subtraindo os valores das variáveis
>>> print("Sua idade é:", anoatual - suaidade, "anos")
Sua idade é: 45 anos
>>>

#Sexto exemplo: utilizando variáveis dinâmica junto com as funções float(), input() e print()
#Atribuindo o valor numérico de ponto flutuante (decimal)
>>> produto = 10.50

#Atribuindo o valor de ponto flutuante com função INPUT() convertendo para Decimal com a função
#FLOAT()
>>> recebido = float(input("Qual valor foi recebido? "))

#Processamento da função INPUT(), digitação do valor e conversão para decimal FLOAT()
Qual valor foi recebido? 20.00

#Imprimindo os dados na saída padrão da função PRINT() e subtraindo os valores das variáveis
>>> print("Troco: ", produto - recebido)
Troco:  -9.5
>>>
```

#04_ Funções ROUND() e STR() do Python 3 no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/ref_func_print.asp<br>
Link de apoio: https://www.w3schools.com/python/ref_func_input.asp<br>
Link de apoio: https://www.w3schools.com/python/python_strings.asp<br>
Link de apoio: https://www.w3schools.com/python/ref_func_int.asp<br>
Link de apoio: https://www.w3schools.com/python/ref_func_float.asp<br>
Link de apoio: https://www.w3schools.com/python/ref_func_round.asp<br>
Link de apoio: https://www.w3schools.com/python/ref_func_str.asp
```python
#Sétimo exemplo: utilizando variáveis constante/dinâmica com as funções float(), input(), 
#print(), str(), round() e int()
#Atribuindo o valor numérico de ponto flutuante (decimal)
>>> saldo_inicial = 35.45

#Atribuindo o valor de ponto flutuante com função INPUT() convertendo para Decimal com a
#função FLOAT()
>>> deposito = float(input("Digite o valor a ser depositado: "))

#Processamento da função INPUT(), digitação do valor e conversão para decimal FLOAT
Digite o valor a ser depositado: 33.33

#Atribuindo o cálculo aritmético de substração das variáveis
>>> saldo_final = (saldo_inicial + deposito)

#Processamento da variável e impressão do valores na tela
>>> saldo_final
68.78   #Valor da variável dinâmica saldo_final

#Imprimindo na saída com a função PRINT() e convertendo para String com a função STR(), 
#arredondado para maior com a função ROUND() e Inteiro com a função INT().
>>> print("Seu saldo é:", "R$: " + str(saldo_final), "Arredondando para maior:", round(saldo_final), "Seu inteiro é:", int(saldo_final))
Seu saldo é: R$: 68.78 Arredondado para maior: 69 Seu inteiro é: 68
>>> 
```
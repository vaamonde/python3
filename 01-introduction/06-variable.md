#Autor: Robson Vaamonde<br>
#Procedimentos em TI: http://procedimentosemti.com.br<br>
#Bora para Prática: http://boraparapratica.com.br<br>
#Robson Vaamonde: http://vaamonde.com.br<br>
#Facebook Procedimentos em TI: https://www.facebook.com/ProcedimentosEmTi<br>
#Facebook Bora para Prática: https://www.facebook.com/BoraParaPratica<br>
#Instagram Procedimentos em TI: https://www.instagram.com/procedimentoem<br>
#YouTUBE Bora Para Prática: https://www.youtube.com/boraparapratica<br>
#Data de criação: 16/07/2024<br>
#Data de atualização: 17/07/2024<br>
#Versão: 0.01<br>

Conteúdo estudado nessa aula:<br>
#01_ Trabalhando com Variáveis Simples/Estáticas do Python 3 no Linux Mint<br>
#02_ Trabalhando com Variáveis Simples/Estáticas com Nomes no Python 3 no Linux Mint<br>
#03_ Trabalhando com Variáveis, Conversão INT() e Entradas INPUT() do Python 3 no Linux Mint<br>
#04_ Trabalhando com Variáveis, Entradas INPUT(), Concatenando e Separando Linhas com o Parâmetro SEP do Python 3 no Linux Mint<br>
#05_ Trabalhando com Variáveis Lógicas/Booleanas do Python no Linux Mint<br>

#01_ Trabalhando com Variáveis Simples/Estáticas do Python 3 no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/python_variables.asp
```python
#Criando variáveis Simples/Estáticas e atribuindo valores
a = 5          #Atribuindo o valor 5 a variável a
b = 3          #Atribuindo o valor 3 a variável b
print(a + b)   #Imprimindo na saída padrão o resultado da adição de A + B com a função PRINT()
```

#02_ Trabalhando com Variáveis Simples/Estáticas com Nomes no Python 3 no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/python_variables.asp
```python
#Criando variáveis Simples/Estáticas com Nomes Fácies e atribuindo valores
salario = 1500   #Atribuindo o valor 1500 a variável salario
aumento = 5      #Atribuindo o valor 5 a variável aumento
#Imprimindo na tela o valor do salário atual e calculando o valor do salário com aumento
print("Salário atual:", salario, "Salário com aumento:", (salario + (salario * (aumento / 100))))
```

#03_ Trabalhando com Variáveis, Conversão INT() e Entradas INPUT() do Python 3 no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/python_variables.asp
```python
#Criando variáveis e atribuindo valores com a função INPUT()
salario = int(input("Digite o seu salário: "))            #Atribuindo o valor inteiro da entrada na variável salario
aumento = int(input("Digite o percentual de aumento: "))  #Atribuindo o valor inteiro da entrada na variável aumento
novosalario = (salario + (salario * (aumento / 100)))     #Calculando o percentual de aumento na variável novosalario
print("Seu novo salário é: ", novosalario)                #Imprimindo na tela o valor do aumento do novo salário
```

#04_ Trabalhando com Variáveis, Entradas INPUT(), Concatenando e Separando Linhas com o Parâmetro SEP do Python 3 no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/python_variables.asp
```python
#Criando um formulário simples e atribuindo valores com a função INPUT()
nome = input("Qual o seu Nome: ")             #Atribuindo o valor da entrada na variável nome
endereco = input("Qual o seu Endereço: ")     #Atribuindo o valor da entrada na variável endereco 
bairro = input("Qual o seu Bairro: ")         #Atribuindo o valor da entrada na variável bairro
cidade = input("Qual a sua Cidade: ")         #Atribuindo o valor da entrada na variável cidade
print()                                       #Imprimindo na saída padrão uma linha em branco
print("Informações cadastrais de: " + nome)   #Imprimindo na saída padrão o valor da variável nome concatenado com a String de Texto
print("Endereço: " + endereco,                #Imprimindo na saída padrão os valores das variável conectadas com as Strings de Texto
      "Bairro: " + bairro,                    #cada uma nova linha separada (quebra de linha) utilizando a expressão SEP
      "Cidade: " + cidade, sep="\n")
```

#05_ Trabalhando com Variáveis Lógicas/Booleanas do Python no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/python_variables.asp
```python
#Criando variáveis booleanas no Python
aprovado = True                            #Atribuindo o valor booleano True (Verdadeiro) na variável aprovado
recuperacao = False                        #Atribuindo o valor booleano False (Falso) na variável recuperacao
resultado = aprovado == recuperacao        #Atribuindo o valor da comparação lógica na variável resultado
print("Status do Resultado: ", resultado)  #Imprimindo na tela o Teste Lógico de Comparação de Igualdade
```

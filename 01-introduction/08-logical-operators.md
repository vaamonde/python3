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
#01_ Trabalhando com Operador Lógico NOT (NEGAÇÃO) do Python 3 no Linux Mint<br>
#02_ Trabalhando com Operador Lógico AND (CONJUNÇÃO) do Python 3 no Linux Mint<br>
#03_ Trabalhando com Operador Lógico OR (DISJUNÇÃO) do Python 3 no Linux Mint<br>

#01_ Trabalhando com Operador Lógico NOT (NEGAÇÃO) do Python 3 no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/python_operators.asp
```bash
#Utilizando o Shell Prompt Padrão do Python 3
python3
```
```python
#Criando variáveis Simples/Estáticas e trabalhando com operadores lógicos
>>> nota01 = 5                              #Atribuindo o valor 5 a variável nota01
>>> nota02 = 3                              #Atribuindo o valor 3 a variável nota02
>>> resultado = not(nota01 > nota02)        #Comparando Logicamente os Valores e alterado seu valor Lógico
>>> print("Resultado do NOT ", resultado)   #Imprimindo na saída padrão o resultado da operação lógica NOT
Resultado do NOT  False
>>>
```

#02_ Trabalhando com Operador Lógico AND (CONJUNÇÃO) do Python 3 no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/python_operators.asp
```python
#Criando variáveis Simples/Estáticas e trabalhando com operadores lógicos
>>> nota01 = 5                                #Atribuindo o valor 5 a variável nota01
>>> nota02 = 3                                #Atribuindo o valor 3 a variável nota02
>>> resultado = (nota01 > 7 and nota02 > 5)   #Comparando Logicamente os Valores e mantendo o valor Lógico
>>> print("Resultado do AND ", resultado)     #Imprimindo na saída padrão o resultado da operação lógica AND
Resultado do AND  False
>>>
```

#03_ Trabalhando com Operador Lógico OR (DISJUNÇÃO) do Python 3 no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/python_operators.asp
```python
#Criando variáveis Simples/Estáticas e trabalhando com operadores lógicos
>>> nota01 = 5                               #Atribuindo o valor 5 a variável nota01
>>> nota02 = 3                               #Atribuindo o valor 3 a variável nota02
>>> resultado = (nota01 > 7 or nota02 > 5)   #Comparando Logicamente os Valores e mantendo o valor Lógico
>>> print("Resultado do OR ", resultado)     #Imprimindo na saída padrão o resultado da operação lógica OR
Resultado do OR  False
>>> 
```

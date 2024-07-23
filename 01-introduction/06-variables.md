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
#01_ Trabalhando com Variáveis Simples/Estáticas (Constantes) do Python 3 no Linux Mint<br>
#02_ Trabalhando com Variáveis Simples/Estáticas com Nomes no Python 3 no Linux Mint<br>
#03_ Trabalhando com Variáveis, Conversão INT() e Entradas INPUT() do Python 3 no Linux Mint<br>
#04_ Trabalhando com Variáveis, Entradas INPUT(), Concatenando e Separando Linhas com o Parâmetro SEP do Python 3 no Linux Mint<br>
#05_ Trabalhando com Variáveis Lógicas/Booleanas do Python no Linux Mint<br>
#06_ Trabalhando com Variáveis de String do Python no Linux Mint<br>
#07_ Trabalhando com Variáveis de String e Índices do Python no Linux Mint<br>

#01_ Trabalhando com Variáveis Simples/Estáticas Numéricas do Python 3 no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/python_variables.asp
```bash
#Utilizando o Shell Prompt Padrão do Python 3
python3
```
```python
#Criando variáveis Simples/Estáticas (Constantes) e atribuindo valores numéricos
>>> a = 5          #Atribuindo o valor 5 a variável a
>>> b = 3          #Atribuindo o valor 3 a variável b
>>> print(a + b)   #Imprimindo na saída padrão o resultado da adição de A + B com a função PRINT()
8
>>>
```

#02_ Trabalhando com Variáveis Estáticas (Constantes) de Nomes Numéricas no Python 3 no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/python_variables.asp
```python
#Salvar o arquivo de script com o nome: 11-var_numerica.py no diretório: ScriptsPython
#Executar o script com a opção: F5 ou Ctrl+F5 ou clicar o ícone: Run Python File
#Criando variáveis com Nomes de Fácil Entendimento e atribuindo valores numéricos
salario = 1500   #Atribuindo o valor 1500 a variável salario
aumento = 5      #Atribuindo o valor 5 a variável aumento
#Imprimindo na tela o valor do salário atual e calculando o valor do salário com aumento
print("Salário atual:", salario, "Salário com aumento:", (salario + (salario * (aumento / 100))))
```

#03_ Trabalhando com Variáveis Dinâmicas, Conversão INT() e Entradas INPUT() do Python 3 no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/python_variables.asp
```python
#Salvar o arquivo de script com o nome: 12-var_int.py no diretório: ScriptsPython
#Executar o script com a opção: F5 ou Ctrl+F5 ou clicar o ícone: Run Python File
#Criando variáveis e atribuindo valores numéricos com a função INPUT()
salario = int(input("Digite o seu salário: "))            #Atribuindo o valor inteiro da entrada na variável salario
aumento = int(input("Digite o percentual de aumento: "))  #Atribuindo o valor inteiro da entrada na variável aumento
novosalario = (salario + (salario * (aumento / 100)))     #Calculando o percentual de aumento na variável novosalario
print("Seu novo salário é: ", novosalario)                #Imprimindo na tela o valor do aumento do novo salário
```

#04_ Trabalhando com Variáveis Dinâmicas, Entradas INPUT(), Concatenando e Separando Linhas com o Parâmetro SEP do Python 3 no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/python_variables.asp
```python
#Salvar o arquivo de script com o nome: 13-var_string.py no diretório: ScriptsPython
#Executar o script com a opção: F5 ou Ctrl+F5 ou clicar o ícone: Run Python File
#Criando um formulário simples e atribuindo valores as variáveis de String com a função INPUT()
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

#05_ Trabalhando com Variáveis Estáticas (Constantes) de Lógicas/Booleanas do Python no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/python_variables.asp
```python
#Salvar o arquivo de script com o nome: 14-var_booleana.py no diretório: ScriptsPython
#Executar o script com a opção: F5 ou Ctrl+F5 ou clicar o ícone: Run Python File
#Criando variáveis booleanas no Python
aprovado = True                            #Atribuindo o valor booleano True (Verdadeiro) na variável aprovado
recuperacao = False                        #Atribuindo o valor booleano False (Falso) na variável recuperacao
resultado = aprovado == recuperacao        #Atribuindo o valor da comparação lógica na variável resultado
print("Status do Resultado: ", resultado)  #Imprimindo na tela o Teste Lógico de Comparação de Igualdade
```

#06_ Trabalhando com Variáveis Dinâmicas de String do Python no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/python_variables.asp<br>
Link de apoio: https://www.w3schools.com/python/ref_func_len.asp
```python
#Salvar o arquivo de script com o nome: 15-var_len.py no diretório: ScriptsPython
#Executar o script com a opção: F5 ou Ctrl+F5 ou clicar o ícone: Run Python File
#Criando variáveis de String e calculando a quantidade de caracteres no Python
nome = input("Digite o seu Nome e Sobrenome: ")                         #Atribuindo o valor de String com a Função INPUT() na variável nome
caracteres = len(nome)                                                  #Atribuindo o valor numérico inteiro com a Função LEN() na variável caracteres
print("Total de caracteres do seu nome é:", caracteres, "com espaço")   #Imprimindo na tela a contagem de caracteres
```

#07_ Trabalhando com Variáveis Dinâmicas de String e Índices do Python no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/python_variables.asp<br>
Link de apoio: https://www.w3schools.com/python/python_strings.asp<br>
Link de apoio: https://www.w3schools.com/python/python_strings_slicing.asp
```python
#Salvar o arquivo de script com o nome: 16-var_indice.py no diretório: ScriptsPython
#Executar o script com a opção: F5 ou Ctrl+F5 ou clicar o ícone: Run Python File
#Criando variáveis de String e imprimindo o valor do Índices no Python
nome = input("Digite o seu Nome e Sobrenome: ")                         #Atribuindo o valor de String com a Função INPUT() na variável nome
caracteres = len(nome)                                                  #Atribuindo o valor numérico inteiro com a Função LEN() na variável caracteres
print("Total de caracteres do seu nome é:", caracteres, "com espaço")   #Imprimindo na tela a contagem de caracteres
#Imprimindo na tela a subtração da quantidade de caracteres para o número correto do Índice
print("Total de Índices do seu nome é:", caracteres -1, "começando sempre com 0 (zero)")
#Imprimindo na tela as letras correspondente aos números do índices de cada carácter
print("Primeira letra do seu nome é:", nome[0], "Primeira letra do seu sobrenome é:", nome[7])
```
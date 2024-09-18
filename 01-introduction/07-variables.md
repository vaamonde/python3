#Autor: Robson Vaamonde<br>
#Procedimentos em TI: http://procedimentosemti.com.br<br>
#Bora para Prática: http://boraparapratica.com.br<br>
#Robson Vaamonde: http://vaamonde.com.br<br>
#Facebook Procedimentos em TI: https://www.facebook.com/ProcedimentosEmTi<br>
#Facebook Bora para Prática: https://www.facebook.com/BoraParaPratica<br>
#Instagram Procedimentos em TI: https://www.instagram.com/procedimentoem<br>
#YouTUBE Bora Para Prática: https://www.youtube.com/boraparapratica<br>
#Data de criação: 16/07/2024<br>
#Data de atualização: 19/08/2024<br>
#Versão: 0.04<br>

Conteúdo estudado nessa aula:<br>
#01_ Trabalhando com Variáveis Simples/Estáticas (Constantes) do Python 3 no Linux Mint<br>
#02_ Trabalhando com Variáveis Simples/Estáticas com Nomes no Python 3 no Linux Mint<br>
#03_ Trabalhando com Variáveis, Conversão INT() e Entradas INPUT() do Python 3 no Linux Mint<br>
#04_ Trabalhando com Variáveis, Entradas INPUT(), Concatenando e Separando Linhas com o Parâmetro SEP do Python 3 no Linux Mint<br>
#05_ Trabalhando com Variáveis Lógicas/Booleanas do Python no Linux Mint<br>
#06_ Trabalhando com Variáveis de String do Python no Linux Mint<br>
#07_ Trabalhando com Variáveis de String e Índices do Python no Linux Mint<br>

A) Variáveis: ​são contêineres para armazenar valores de dados. Python não possui comando para declarar uma variável. Uma variável é criada no momento em que você atribui um valor a ela pela primeira vez.

B) A função len() retorna o número de itens em um objeto. Quando o objeto é uma string, a função len() retorna o número de caracteres da string.

C) Strings em python são colocadas entre aspas simples ou duplas.

D) Você pode retornar um intervalo de caracteres usando a sintaxe de Índice. Especifique o índice inicial e o índice final, separados por dois pontos, para retornar uma parte da string.

#01_ Trabalhando com Variáveis Simples/Estáticas Numéricas do Python 3 no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/python_variables.asp
```bash
#Utilizando o Shell Prompt Padrão do Python 3
python3
```
```python
#Criando variáveis Simples/Estáticas (Constantes) e atribuindo valores numéricos
#Atribuindo o valor 5 a variável a
>>> a = 5

#Atribuindo o valor 3 a variável b
>>> b = 3

#Imprimindo na saída padrão o resultado da adição de A + B com a função PRINT()
>>> print(a + b)
8
>>>
```

#02_ Trabalhando com Variáveis Estáticas (Constantes) de Nomes Numéricas no Python 3 no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/python_variables.asp
```python
#Salvar o arquivo de script com o nome: 11-var_numerica.py no diretório: ScriptsPython
#Executar o script com a opção: F5 ou Ctrl+F5 ou clicar o ícone: Run Python File
#Criando variáveis com Nomes de Fácil Entendimento e atribuindo valores numéricos

#Atribuindo os valores inteiros nas variáveis constante
salario = 1500
aumento = 5

#Imprimindo na tela o valor do salário atual e calculando o valor do salário com aumento
print("Salário atual:", salario, "Salário com aumento:", (salario + (salario * (aumento / 100))))
```

#03_ Trabalhando com Variáveis Dinâmicas, Conversão INT() e Entradas INPUT() do Python 3 no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/python_variables.asp
```python
#Salvar o arquivo de script com o nome: 12-var_int.py no diretório: ScriptsPython
#Executar o script com a opção: F5 ou Ctrl+F5 ou clicar o ícone: Run Python File
#Criando variáveis e atribuindo valores numéricos com a função INPUT()

#Atribuindo o valor inteiro nas variáveis
salario = int(input("Digite o seu salário: "))
aumento = int(input("Digite o percentual de aumento: "))

#Calculando o percentual de aumento na variável novosalario
novosalario = (salario + (salario * (aumento / 100)))

#Imprimindo na tela o valor do aumento do novo salário
print("Seu novo salário é: ", novosalario)
```

#04_ Trabalhando com Variáveis Dinâmicas, Entradas INPUT(), Concatenando e Separando Linhas com o Parâmetro SEP do Python 3 no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/python_variables.asp<br>
Link de apoio: https://www.w3schools.com/python/ref_func_print.asp
```python
#Salvar o arquivo de script com o nome: 13-var_string.py no diretório: ScriptsPython
#Executar o script com a opção: F5 ou Ctrl+F5 ou clicar o ícone: Run Python File
#Criando um formulário simples e atribuindo valores as variáveis de String com a função INPUT()

#Atribuindo o valor string nas variáveis
nome = input("Qual o seu Nome: ")
endereco = input("Qual o seu Endereço: ")
bairro = input("Qual o seu Bairro: ")
cidade = input("Qual a sua Cidade: ")

#Imprimindo na saída padrão uma linha em branco
print()

#Imprimindo na saída padrão o valor das variáveis concatenando com a descrição
#e quebrando a saída em uma nova linha separada com o parâmetro SEP
print("Informações cadastrais de: " + nome)
print("Endereço: " + endereco,
      "Bairro: " + bairro,
      "Cidade: " + cidade, sep="\n")
```

#05_ Trabalhando com Variáveis Estáticas (Constantes) de Lógicas/Booleanas do Python no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/python_variables.asp
```python
#Salvar o arquivo de script com o nome: 14-var_booleana.py no diretório: ScriptsPython
#Executar o script com a opção: F5 ou Ctrl+F5 ou clicar o ícone: Run Python File
#Criando variáveis booleanas no Python

#Atribuindo o valor booleano True (Verdadeiro) ou False (Falso) nas variáveis
aprovado = True
recuperacao = False

#Atribuindo o valor da comparação lógica na variável
resultado = aprovado == recuperacao

#Imprimindo na tela o Teste Lógico de Comparação de Igualdade
print("Status do Resultado: ", resultado)
```

#06_ Trabalhando com Variáveis Dinâmicas de String do Python no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/python_variables.asp<br>
Link de apoio: https://www.w3schools.com/python/ref_func_len.asp
```python
#Salvar o arquivo de script com o nome: 15-var_len.py no diretório: ScriptsPython
#Executar o script com a opção: F5 ou Ctrl+F5 ou clicar o ícone: Run Python File
#Criando variáveis de String e calculando a quantidade de caracteres no Python

#Atribuindo o valor de String com a Função INPUT() na variável
nome = input("Digite o seu Nome e Sobrenome: ")

#Atribuindo o valor numérico inteiro com a Função LEN() na variável
caracteres = len(nome)

#Imprimindo na tela a contagem de caracteres
print("Total de caracteres do seu nome é:", caracteres, "com espaço")
```

#07_ Trabalhando com Variáveis Dinâmicas de String e Índices do Python no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/python_variables.asp<br>
Link de apoio: https://www.w3schools.com/python/python_strings.asp<br>
Link de apoio: https://www.w3schools.com/python/python_strings_slicing.asp
```python
#Salvar o arquivo de script com o nome: 16-var_indice.py no diretório: ScriptsPython
#Executar o script com a opção: F5 ou Ctrl+F5 ou clicar o ícone: Run Python File
#Criando variáveis de String e imprimindo o valor do Índices no Python

#Atribuindo o valor de String com a Função INPUT() na variável
nome = input("Digite o seu Nome e Sobrenome: ")

#Atribuindo o valor numérico inteiro com a Função LEN() na variável
caracteres = len(nome)

#Imprimindo na tela a contagem de caracteres
print("Total de caracteres do seu nome é:", caracteres, "com espaço")

#Imprimindo na tela a subtração da quantidade de caracteres para o número correto do Índice
print("Total de Índices do seu nome é:", caracteres -1, "começando sempre com 0 (zero)")

#Imprimindo na tela as letras correspondente aos números do índices de cada carácter
print("Primeira letra do seu nome é:", nome[0], "Primeira letra do seu sobrenome é:", nome[7])
```
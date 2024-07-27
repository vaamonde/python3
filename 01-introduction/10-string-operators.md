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
#Versão: 0.03<br>

Conteúdo estudado nessa aula:<br>
#01_ Trabalhando com Concatenação de Adição (+) de String do Python 3 no Linux Mint<br>
#02_ Trabalhando com Concatenação de Multiplicação (*) de String do Python 3 no Linux Mint<br>
#03_ Trabalhando com Composição de String do Python 3 no Linux Mint<br>
#04_ Trabalhando com Composição de String com a Função FORMAT() do Python 3 no Linux Mint<br>
#05_ Trabalhando com Composição de String e Formatação F-STRING do Python 3 no Linux Mint<br>
#06_ Trabalhando com Fatiamento de String do Python 3 no Linux Mint<br>
#07_ Trabalhando com Parágrafos de String do Python 3 no Linux Mint<br>
#08_ Utilizando Conjuntos de Caracteres do Python 3 no Linux Mint<br>
#09_ Conferindo o Tipo TYPE() de Valores das Variáveis do Python 3 no Linux Mint<br>

#01_ Trabalhando com Concatenação de Adição (+) de String do Python 3 no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/python_strings_concatenate.asp
```python
#Salvar o arquivo de script com o nome: 20-string.py no diretório: ScriptsPython
#Executar o script com a opção: F5 ou Ctrl+F5 ou clicar o ícone: Run Python File

#Atribuindo os valores de string nas variáveis
seu_nome = "robson"
seu_dominio = "boraparapratica.com.br"

#Imprimindo na tela a concatenação das variáveis e a string @ (arroba)
print("Seu e-mail é: ", seu_nome+"@"+seu_dominio)
```

#02_ Trabalhando com Concatenação de Multiplicação (*) de String do Python 3 no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/python_strings_concatenate.asp
```python
#Salvar o arquivo de script com o nome: 21-upper-lower.py no diretório: ScriptsPython
#Executar o script com a opção: F5 ou Ctrl+F5 ou clicar o ícone: Run Python File

#Atribuindo os valores de string nas variáveis
seu_nome = "Robson"
seu_sobrenome = "Vaamonde"
seu_domínio = "BORAPARAPRATICA"
descritivo = "Parabéns"

#Imprimindo na tela a concatenação das variáveis e convertendo tudo para maiúscula e minúscula
#os valores atribuídos com o parâmetro .UPPER() e .LOWER() das variáveis
print(descritivo.upper()+"!"*6,
     "Seu e-mail é: ", 
     seu_nome.lower()+"."+seu_sobrenome.lower()+"@"+seu_domínio.lower()+".com.br")
```

#03_ Trabalhando com Composição de String do Python 3 no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/python_strings.asp
```python
#Salvar o arquivo de script com o nome: 22-composition.py no diretório: ScriptsPython
#Executar o script com a opção: F5 ou Ctrl+F5 ou clicar o ícone: Run Python File

#Atribuindo os valores de string, inteiro e ponto flutuante (decimal) nas variáveis
seu_nome = "Robson Vaamonde"
sua_idade = 45
seu_saldo = 135.45

#Imprimindo na tela a composição das variáveis String %s, Números Inteiros %d e Números Decimais
#%f com a opção de 5.2 que indica que vamos reservar 5 (cinco) caracteres para o número inteiro 
#e 2 (dois) caracteres de casas decimais.
print("%s tem %d anos e R$%5.2f no Banco." % (seu_nome, sua_idade, seu_saldo))
```

#04_ Trabalhando com Composição de String com a Função FORMAT() do Python 3 no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/ref_func_format.asp<br>
Link de apoio: https://www.w3schools.com/python/python_string_formatting.asp
```python
#Salvar o arquivo de script com o nome: 23-format.py no diretório: ScriptsPython
#Executar o script com a opção: F5 ou Ctrl+F5 ou clicar o ícone: Run Python File

#Atribuindo os valores de string, inteiro e ponto flutuante (decimal) nas variáveis
seu_nome = "Robson Vaamonde"
sua_idade = 45
seu_saldo = 135.45

#Imprimindo na tela a composição das variáveis String {}, Números Inteiros {} e Números Decimais
#{} com a opção de :5.2f que indica que vamos reservar 5 (cinco) caracteres para o número inteiro 
#e 2 (dois) caracteres de casas decimais e utilizar a função FORMAT() para os valores.
print("{} tem {} anos e R${:5.2f} no Banco.".format(seu_nome, sua_idade, seu_saldo))
```

#05_ Trabalhando com Composição de String e Formatação F-STRING do Python 3 no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/ref_func_format.asp<br>
Link de apoio: https://www.w3schools.com/python/python_string_formatting.asp
```python
#Salvar o arquivo de script com o nome: 24-fstring.py no diretório: ScriptsPython
#Executar o script com a opção: F5 ou Ctrl+F5 ou clicar o ícone: Run Python File

#Atribuindo os valores de string, inteiro e ponto flutuante (decimal) nas variáveis
seu_nome = "Robson Vaamonde"
sua_idade = 45
seu_saldo = 135.45

#Imprimindo na tela a composição das variáveis String {}, Números Inteiros {} e Números Decimais
#{} com a opção de :5.2f que indica que vamos reservar 5 (cinco) caracteres para o número inteiro 
#e 2 (dois) caracteres de casas decimais e utilizando a formatação F-STRING.
print(f"{seu_nome} tem {sua_idade} anos e R${seu_saldo:5.2f} no Banco.")
```

#06_ Trabalhando com Fatiamento de String do Python 3 no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/ref_func_format.asp<br>
Link de apoio: https://www.w3schools.com/python/python_string_formatting.asp
```python
#Salvar o arquivo de script com o nome: 25-slicing.py no diretório: ScriptsPython
#Executar o script com a opção: F5 ou Ctrl+F5 ou clicar o ícone: Run Python File

#Atribuindo os valores de string nas variáveis
seu_nome = "Robson Vaamonde"
total_caracteres = len(seu_nome)

#Imprimindo na tela a composição das variáveis String{} com as opções [0:6] e [7:15] que indica 
#o início e fim dos caracteres que serão mostrados na saída padrão do comando PRINT().
print(f"Total de caracteres do seu nome+espaço é: {total_caracteres}")
print(f"Seu nome é: {seu_nome[0:6]} e Seu sobrenome é: {seu_nome[7:15]}")
```

#07_ Trabalhando com Parágrafos de String do Python 3 no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/python_string_formatting.asp
```python
#Salvar o arquivo de script com o nome: 26-paragraphs.py no diretório: ScriptsPython
#Executar o script com a opção: F5 ou Ctrl+F5 ou clicar o ícone: Run Python File

#Imprimindo na tela um parágrafo utilizando 03 (três) Aspas Duplas e sequências de escape
#como a Contra Barrar para permitir utilizar Aspas Duplas e Simples no Texto e \n para
#criar uma nova linha ou utilizar Tabulação \t.
print("""Ao escrever um literal de string no código Python que será exibido na tela como saída,
você precisa determinar se quer gerar a saída da string como uma única linha ou como um parágrafo
de várias linhas. Utilizar \"ASPAS DUPLAS\" em String e Melhor pois você consegue usar \'ASPAS
SIMPLES\' sem se preocupar.\nCriando um nova linha também é fácil.\n\tOu tabulando""")
```

#08_ Utilizando Conjuntos de Caracteres do Python 3 no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/ref_func_chr.asp<br>
Link de apoio: https://www.w3schools.com/python/ref_func_ord.asp
```python
#Salvar o arquivo de script com o nome: 27-ascii.py no diretório: ScriptsPython
#Executar o script com a opção: F5 ou Ctrl+F5 ou clicar o ícone: Run Python File

#Atribuindo os valores de string e inteiro nas variáveis
numero_unicode = "@"
unicode_numero = 64

#Imprimindo na tela o texto junto com as variáveis, fazer a conversão do caractere @ (arroba)
#para o código decimal da Tabela ASCII com a Função ORD() e o processo inverso com a Função
#CHR(), utilizando a Função STR() para converter números Inteiros para String.
print("Você quer saber o número Decimal da Tabela ASCII do caractere: " + numero_unicode,
      "Você pode usar a Função ORD(): " + str(ord(numero_unicode)),
	  "Você pode fazer o processo reverso, sabendo o número Decimal da Tabela ASCII do caractere: " + str(unicode_numero),
	  "Você pode saber qual é o caractere com a Função CHR(): " + chr(unicode_numero), 
	  sep="\n")
```

#09_ Conferindo o Tipo TYPE() de Valores das Variáveis do Python 3 no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/ref_func_type.asp
```python
#Salvar o arquivo de script com o nome: 28-type.py no diretório: ScriptsPython
#Executar o script com a opção: F5 ou Ctrl+F5 ou clicar o ícone: Run Python File

#Atribuindo os valores de string, inteiro e ponto flutuante (decimal) nas variáveis
seu_nome = "Robson Vaamonde"
sua_idade = 45
seu_saldo = 135.45

#Imprimindo na tela a composição das variáveis String {}, Números Inteiros {} e Números Decimais
#{} e mostrando o Tipo de Dados de cada variável armazenada.
print(f"O tipo (Type) da Variável: seu_nome = {seu_nome} é:", type(seu_nome))
print(f"O tipo (Type) da Variável: sua_idade = {sua_idade} é:", type(sua_idade))
print(f"O tipo (Type) da Variável: seu_nome = {seu_saldo} é:", type(seu_saldo))
```
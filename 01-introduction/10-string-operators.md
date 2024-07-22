#Autor: Robson Vaamonde<br>
#Procedimentos em TI: http://procedimentosemti.com.br<br>
#Bora para Prática: http://boraparapratica.com.br<br>
#Robson Vaamonde: http://vaamonde.com.br<br>
#Facebook Procedimentos em TI: https://www.facebook.com/ProcedimentosEmTi<br>
#Facebook Bora para Prática: https://www.facebook.com/BoraParaPratica<br>
#Instagram Procedimentos em TI: https://www.instagram.com/procedimentoem<br>
#YouTUBE Bora Para Prática: https://www.youtube.com/boraparapratica<br>
#Data de criação: 16/07/2024<br>
#Data de atualização: 22/07/2024<br>
#Versão: 0.02<br>

Conteúdo estudado nessa aula:<br>
#01_ Trabalhando com Concatenação de Adição (+) de String do Python 3 no Linux Mint<br>
#02_ Trabalhando com Concatenação de Multiplicação (*) de String do Python 3 no Linux Mint<br>
#03_ Trabalhando com Composição de String do Python 3 no Linux Mint<br>
#04_ Trabalhando com Composição de String com a Função FORMAT() do Pytnon 3 no Linux Mint<br>
#05_ Trabalhando com Composição de String e Formatação F-STRING do Pytnon 3 no Linux Mint<br>
#06_ Trabalhando com Fatiamento de String do Pytnon 3 no Linux Mint<br>

#01_ Trabalhando com Concatenação de Adição (+) de String do Python 3 no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/python_strings_concatenate.asp
```python
#criando as variáveis e atribuindo os valores de string
seu_nome = "robson"
seu_dominio = "boraparapratica.com.br"

#imprimindo na tela a concatenação das variáveis e a string @ (arroba)
print("Seu e-mail é: ", seu_nome+"@"+seu_dominio)
```

#02_ Trabalhando com Concatenação de Multiplicação (*) de String do Python 3 no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/python_strings_concatenate.asp
```python
#criando as variáveis e atribuindo os valores de string
seu_nome = "Robson"
seu_sobrenome = "Vaamonde"
seu_domínio = "BORAPARAPRATICA"
descritivo = "Parabéns"

#imprimindo na tela a concatenação das variáveis e convertendo tudo para maiúscula e minúscula
#os valores atribuídos com o parâmetro .UPPER() e .LOWER() das variáveis
print(descritivo.upper()+"!"*6,
     "Seu e-mail é: ", 
     seu_nome.lower()+"."+seu_sobrenome.lower()+"@"+seu_domínio.lower()+".com.br")
```

#03_ Trabalhando com Composição de String do Python 3 no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/python_strings.asp
```python
#criando as variáveis e atribuindo os valores de string, inteiro e ponto flutuante (decimal)
seu_nome = "Robson Vaamonde"
sua_idade = 45
seu_saldo = 135.45

#imprimindo na tela a composição das variáveis String %s, Números Inteiros %d e Números Decimais
#%f com a opção de 5.2 que indica que vamos reservar 5 (cinco) caracteres para o número inteiro 
#e 2 (dois) caracteres de casas decimais.
print("%s tem %d anos e R$%5.2f no Banco." % (seu_nome, sua_idade, seu_saldo))
```

#04_ Trabalhando com Composição de String com a Função FORMAT() do Pytnon 3 no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/ref_func_format.asp<br>
Link de apoio: https://www.w3schools.com/python/python_string_formatting.asp
```python
#criando as variáveis e atribuindo os valores de string, inteiro e ponto flutuante (decimal)
seu_nome = "Robson Vaamonde"
sua_idade = 45
seu_saldo = 135.45

#imprimindo na tela a composição das variáveis String {}, Números Inteiros {} e Números Decimais
#{} com a opção de :5.2f que indica que vamos reservar 5 (cinco) caracteres para o número inteiro 
#e 2 (dois) caracteres de casas decimais e utilizar a função FORMAT() para os valores.
print("{} tem {} anos e R${:5.2f} no Banco.".format(seu_nome, sua_idade, seu_saldo))
```

#05_ Trabalhando com Composição de String e Formatação F-STRING do Pytnon 3 no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/ref_func_format.asp<br>
Link de apoio: https://www.w3schools.com/python/python_string_formatting.asp
```python
#criando as variáveis e atribuindo os valores de string, inteiro e ponto flutuante (decimal)
seu_nome = "Robson Vaamonde"
sua_idade = 45
seu_saldo = 135.45

#imprimindo na tela a composição das variáveis String {}, Números Inteiros {} e Números Decimais
#{} com a opção de :5.2f que indica que vamos reservar 5 (cinco) caracteres para o número inteiro 
#e 2 (dois) caracteres de casas decimais e utilizando a formatação F-STRING.
print(f"{seu_nome} tem {sua_idade} anos e R${seu_saldo:5.2f} no Banco.")
```

#06_ Trabalhando com Fatiamento de String do Pytnon 3 no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/ref_func_format.asp<br>
Link de apoio: https://www.w3schools.com/python/python_string_formatting.asp
```python
#criando as variáveis e atribuindo os valores de string, inteiro e ponto flutuante (decimal)
seu_nome = "Robson Vaamonde"
total_caracteres = len(seu_nome)

#imprimindo na tela
print(f"Total de caracteres do seu nome+espaço é: {total_caracteres}")
print(f"Seu nome é: {seu_nome[0:6]} e Seu sobrenome é: {seu_nome[7:15]}")
```
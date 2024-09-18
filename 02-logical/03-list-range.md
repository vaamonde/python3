#Autor: Robson Vaamonde<br>
#Procedimentos em TI: http://procedimentosemti.com.br<br>
#Bora para Prática: http://boraparapratica.com.br<br>
#Robson Vaamonde: http://vaamonde.com.br<br>
#Facebook Procedimentos em TI: https://www.facebook.com/ProcedimentosEmTi<br>
#Facebook Bora para Prática: https://www.facebook.com/BoraParaPratica<br>
#Instagram Procedimentos em TI: https://www.instagram.com/procedimentoem<br>
#YouTUBE Bora Para Prática: https://www.youtube.com/boraparapratica<br>
#Data de criação: 26/08/2024<br>
#Data de atualização: 29/08/2024<br>
#Versão: 0.02<br>

Conteúdo estudado nessa aula:<br>
#01_ Criando Lista de Dados utilizando a Função LIST() e RANGE()<br>
#02_ Criando Lista de Dados de Início e Fim utilizando a Função LIST() e RANGE()<br>
#03_ Criando Intervalos em Lista de Dados utilizando a Função LIST() e RANGE()<br>
#04_ Criando Intervalos Regressivos em Lista de Dados utilizando a Função LIST() e RANGE()<br>

A) A função list() cria um objeto de lista, um objeto de lista é uma coleção ordenada e mutável.

B) A função range() retorna uma sequência de números, começando em 0 por padrão, e incrementando em 1 (por padrão), e parando antes de um número especificado.

#01_ Criando Lista de Dados utilizando a Função LIST() e RANGE()<br>
Link de apoio: https://www.w3schools.com/python/python_lists.asp<br>
Link de apoio: https://www.w3schools.com/python/ref_func_list.asp<br>
Link de apoio: https://www.w3schools.com/python/ref_func_range.asp
```python
#Pressione: Ctrl + L para limpar o Shell do Python 3 facilitando a digitação
#Você pode utilizar o TAB (Tabulador) para facilitar a digitação das funções

#Primeiro exemplo: utilizando o função list() e range()
#Imprimindo os dados na saída padrão do valor da função RANGE() e criando uma sequência
#numérica com a função LIST() a partir do: 0 (zero) até 10 (dez) números finalizando no 
#9 (nove) que corresponde a lógico do range de número determinado
>>> list(range(10))
[0, 1, 2, 3, 4, 5, 6, 7, 8, 9]
>>>
```

#02_ Criando Lista de Dados de Início e Fim utilizando a Função LIST() e RANGE()<br>
Link de apoio: https://www.w3schools.com/python/python_lists.asp<br>
Link de apoio: https://www.w3schools.com/python/ref_func_list.asp<br>
Link de apoio: https://www.w3schools.com/python/ref_func_range.asp
```python
#Pressione: Ctrl + L para limpar o Shell do Python 3 facilitando a digitação
#Você pode utilizar o TAB (Tabulador) para facilitar a digitação das funções

#Segundo exemplo: utilizando o função list() e range()
#Imprimindo os dados na saída padrão do valor da função RANGE() e criando uma sequência
#numérica com a função LIST() a partir do: 1 (um) que será o número inicial até o 10 (dez)
#que será o número final, começando a contagem de 1 (um) até 9 (nove) que corresponde a 
#lógica do range dos números determinados (INÍCIO E FIM).
>>> list(range(1, 10))
[1, 2, 3, 4, 5, 6, 7, 8, 9]
>>>
```

#03_ Criando Intervalos em Lista de Dados utilizando a Função LIST() e RANGE()<br>
Link de apoio: https://www.w3schools.com/python/python_lists.asp<br>
Link de apoio: https://www.w3schools.com/python/ref_func_list.asp<br>
Link de apoio: https://www.w3schools.com/python/ref_func_range.asp
```python
#Pressione: Ctrl + L para limpar o Shell do Python 3 facilitando a digitação
#Você pode utilizar o TAB (Tabulador) para facilitar a digitação das funções

#Terceiro exemplo: utilizando o função list() e range()
#Imprimindo os dados na saída padrão do valor da função RANGE() e criando uma sequência
#numérica com a função LIST() a partir do: 1 (um) que será o número inicial até o 10 (dez)
#que será o número final, começando a contagem de 1 (um) até 9 (nove) adicionando 1 (um)
#a cada variação que corresponde a lógica do range dos números determinados (INÍCIO E FIM).
>>> list(range(1, 10, 1))
[1, 2, 3, 4, 5, 6, 7, 8, 9]
>>> 

#Quarto exemplo: utilizando o função list() e range()
#Imprimindo os dados na saída padrão do valor da função RANGE() e criando uma sequência
#numérica com a função LIST() a partir do: 1 (um) que será o número inicial até o 10 (dez)
#que será o número final, começando a contagem de 1 (um) até 9 (nove) adicionando 2 (dois)
#a cada variação que corresponde a lógica do range dos números determinados (INÍCIO E FIM).
>>> list(range(1, 10, 2))
[1, 3, 5, 7, 9]
>>>

#Quinto exemplo: utilizando o função list() e range()
#Imprimindo os dados na saída padrão do valor da função RANGE() e criando uma sequência
#numérica com a função LIST() a partir do: 1 (um) que será o número inicial até o 10 (dez)
#que será o número final, começando a contagem de 1 (um) até 9 (nove) adicionando 3 (três)
#a cada variação que corresponde a lógica do range dos números determinados (INÍCIO E FIM).
>>> list(range(1, 10, 3))
[1, 4, 7]
>>>
```

#04_ Criando Intervalos Regressivos em Lista de Dados utilizando a Função LIST() e RANGE()<br>
Link de apoio: https://www.w3schools.com/python/python_lists.asp<br>
Link de apoio: https://www.w3schools.com/python/ref_func_list.asp<br>
Link de apoio: https://www.w3schools.com/python/ref_func_range.asp
```python
#Pressione: Ctrl + L para limpar o Shell do Python 3 facilitando a digitação
#Você pode utilizar o TAB (Tabulador) para facilitar a digitação das funções

#Sexto exemplo: utilizando o função list() e range()
#Imprimindo os dados na saída padrão do valor da função RANGE() e criando uma sequência
#numérica com a função LIST() a partir do: 10 (dez) que será o número inicial até o 0 (zero)
#que será o número final, começando a contagem de 10 (dez) até 1 (um) e subtraindo -1 (menos
#um) a cada variação que corresponde a lógica do range dos números determinados (INÍCIO E FIM).
>>> list(range(10, 0, -1))
[10, 9, 8, 7, 6, 5, 4, 3, 2, 1]
>>>
```
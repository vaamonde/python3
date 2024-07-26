#Autor: Robson Vaamonde<br>
#Procedimentos em TI: http://procedimentosemti.com.br<br>
#Bora para Prática: http://boraparapratica.com.br<br>
#Robson Vaamonde: http://vaamonde.com.br<br>
#Facebook Procedimentos em TI: https://www.facebook.com/ProcedimentosEmTi<br>
#Facebook Bora para Prática: https://www.facebook.com/BoraParaPratica<br>
#Instagram Procedimentos em TI: https://www.instagram.com/procedimentoem<br>
#YouTUBE Bora Para Prática: https://www.youtube.com/boraparapratica<br>
#Data de criação: 16/07/2024<br>
#Data de atualização: 26/07/2024<br>
#Versão: 0.02<br>

Conteúdo estudado nessa aula:<br>
#01_ Trabalhando com Condições de Estrutura de Decisão IF do Python 3 no Linux Mint<br>
#02_ Trabalhando com Condições de Estrutura de Decisão e Blocos IF do Python 3 no Linux Mint<br>

#01_ Trabalhando com Condições de Estrutura de Decisão IF do Python 3 no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/gloss_python_if_statement.asp
```python
#CENÁRIO 01: estrutura de decisão simples com IF

#atribuindo valores inteiros a duas variáveis dinâmicas
valor01=int(input("Digite o primeiro valor: "))
valor02=int(input("Digite o segundo valor.: "))
print()

#teste lógico de condição verdadeira utilizando o IF
if valor01 > valor02:
    #imprimi na tela se o resultado for verdadeiro, se for falso não
    print("Primeiro valor é MAIOR que o Segundo valor!")
if valor02 > valor01:
    #imprimi na tela se o resultado for verdadeiro, se for falso não
    print("Segundo valor é MAIOR que o Primeiro valor!")
```
```python
#CENÁRIO 02: estrutura de decisão simples com IF

#atribuindo o valor inteiro a variável constante
#Link: https://www.autoindustria.com.br/2024/04/24/frota-brasileira-envelhece-e-idade-media-dos-carros-supera-11-anos/
media_idade = int(11)

#atribuindo valor inteiros a variável dinâmica
idade_carro = int(input("Digite a idade do seu carro: "))
print()

#teste lógico de condição verdadeira utilizando o IF
if idade_carro <= media_idade:
    #imprimi na tela se o resultado for verdadeiro, se for falso não
    print("Seu carro é MAIS NOVO que a média de idade dos carros dos Brasileiro!")
if idade_carro > media_idade:
    #imprimi na tela se o resultado for verdadeiro, se for falso não
    print("Seu carro é MAIS VELHO que a média de idade dos carros dos Brasileiro!")
```

#02_ Trabalhando com Condições de Estrutura de Decisão e Blocos IF do Python 3 no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/gloss_python_if_statement.asp
```python
#CENÁRIO 03: 

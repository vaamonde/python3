#Autor: Robson Vaamonde<br>
#Procedimentos em TI: http://procedimentosemti.com.br<br>
#Bora para Prática: http://boraparapratica.com.br<br>
#Robson Vaamonde: http://vaamonde.com.br<br>
#Facebook Procedimentos em TI: https://www.facebook.com/ProcedimentosEmTi<br>
#Facebook Bora para Prática: https://www.facebook.com/BoraParaPratica<br>
#Instagram Procedimentos em TI: https://www.instagram.com/procedimentoem<br>
#YouTUBE Bora Para Prática: https://www.youtube.com/boraparapratica<br>
#Data de criação: 16/07/2024<br>
#Data de atualização: 20/08/2024<br>
#Versão: 0.08<br>

Conteúdo estudado nessa aula:<br>
#01_ Estrutura de Decisão Simples IF (SE) do Python 3 no Linux Mint Exemplo-01<br>
#02_ Estrutura de Decisão Simples IF (SE) do Python 3 no Linux Mint Exemplo-02<br>
#03_ Estrutura de Decisão Simples IF (SE) do Python 3 no Linux Mint Exemplo-03<br>
#04_ Estrutura de Decisão em Blocos IF (SE) do Python 3 no Linux Mint Exemplo-01<br>

#01_ Estrutura de Decisão Simples IF (SE) do Python 3 no Linux Mint Exemplo-01<br>
Link de apoio: https://www.w3schools.com/python/gloss_python_if_statement.asp<br>
Link de apoio: https://www.w3schools.com/python/python_conditions.asp
```python
#CENÁRIO 01: estrutura de decisão simples com IF (SE)

#Salvar o arquivo de script com o nome: 30-ifbasic01.py no diretório: ScriptsPython
#Executar o script com a opção: F5 ou Ctrl+F5 ou clicar o ícone: Run Python File

#Atribuindo os valores inteiros a duas variáveis dinâmicas
valor01=int(input("Digite o primeiro valor: "))
valor02=int(input("Digite o segundo valor.: "))
print()

#Bloco de teste lógico de condição verdadeira utilizando o IF
if valor01 > valor02:
    #Imprimir na tela se o resultado for verdadeiro, se for falso não
    print("Primeiro valor é MAIOR que o Segundo valor!")
if valor02 > valor01:
    #Imprimir na tela se o resultado for verdadeiro, se for falso não
    print("Segundo valor é MAIOR que o Primeiro valor!")
```

#02_ Estrutura de Decisão Simples IF (SE) do Python 3 no Linux Mint Exemplo-02<br>>
Link de apoio: https://www.w3schools.com/python/gloss_python_if_statement.asp<br>
Link de apoio: https://www.w3schools.com/python/python_conditions.asp
```python
#CENÁRIO 02: estrutura de decisão simples com IF (SE)

#Salvar o arquivo de script com o nome: 31-ifbasic02.py no diretório: ScriptsPython
#Executar o script com a opção: F5 ou Ctrl+F5 ou clicar o ícone: Run Python File

#Atribuindo o valor inteiro a variável constante
#Link: https://www.autoindustria.com.br/2024/04/24/frota-brasileira-envelhece-e-idade-media-dos-carros-supera-11-anos/
media_idade = int(11)

#Atribuindo valor inteiro a variável dinâmica
idade_carro = int(input("Digite a idade do seu carro: "))
print()

#Bloco de teste lógico de condição verdadeira utilizando o IF
if idade_carro <= media_idade:
    #Imprimir na tela se o resultado for verdadeiro, se for falso não
    print("Seu carro é MAIS NOVO que a média de idade dos carros dos Brasileiro!")
if idade_carro > media_idade:
    #Imprimir na tela se o resultado for verdadeiro, se for falso não
    print("Seu carro é MAIS VELHO que a média de idade dos carros dos Brasileiro!")
```

#03_ Estrutura de Decisão Simples IF (SE) do Python 3 no Linux Mint Exemplo-03<br>
Link de apoio: https://www.w3schools.com/python/gloss_python_if_statement.asp<br>
Link de apoio: https://www.w3schools.com/python/python_conditions.asp
```python
#CENÁRIO 03: estrutura de decisão simples com IF (SE)

#Salvar o arquivo de script com o nome: 32-ifbasic03.py no diretório: ScriptsPython
#Executar o script com a opção: F5 ou Ctrl+F5 ou clicar o ícone: Run Python File

#Atribuindo os valor flutuantes as variáveis constante
#Link: https://www.jusbrasil.com.br/artigos/multa-de-transito-por-excesso-de-velocidade-acima-de-50-atualizado-2024/501444512
ate_20 = 130.16
de_20_ate_50 = 195.23
acima_de_50 = 880.41

#Atribuindo valor flutuante a variável dinâmica
print("Você está trafegando numa via Arterial que a velocidade máxima permitida é: 80km/h", end='\n\n')
velocidade = float(input("Digite a velocidade do seu carro: "))
print()

#Bloco de teste lógico de condição verdadeira utilizando o IF
if velocidade <= 80:
    #Imprimir na tela se o resultado for verdadeiro, se for falso não
    print("Você está dentro do Limite de Velocidades, Parabéns!!!!!")
if velocidade > 80.01 and velocidade <= 96:
    #Imprimir na tela se o resultado for verdadeiro, se for falso não, formatar as casas
    #Decimais {}, com a opção de :.2f que indica que vamos reservar o número inteiro e 2 
    #(dois) caracteres de casas decimais e utilizar a formatação F-STRING com a função 
    #FORMAT() acrescentando o caractere % (porcentagem)
    print("Você está acima da velocidade máxima permitida de: 80km/h")
    print("Sua velocidade é de:", velocidade ,"km/h, você está acima:", "{:.2f}%".format(((velocidade / 80) - 1) * 100))
    print("O valor da multa é: R$:", ate_20)
if velocidade > 96.01 and velocidade <= 120:
    #Imprimir na tela se o resultado for verdadeiro, se for falso não
    print("Você está acima da velocidade máxima permitida de: 80km/h")
    print("Sua velocidade é de:", velocidade ,"km/h, você está acima:", "{:.2f}%".format(((velocidade / 80) - 1) * 100))
    print("O valor da multa é: R$:", de_20_ate_50)
if velocidade > 120.01:
    #Imprimir na tela se o resultado for verdadeiro, se for falso não
    print("Você está MUITO ACIMA da velocidade máxima permitida de: 80km/h")
    print("Sua velocidade é de:", velocidade ,"km/h, você está acima:", "{:.2f}%".format(((velocidade / 80) - 1) * 100))
    print("O valor da multa é: R$:", acima_de_50)
```

#04_ Estrutura de Decisão em Blocos IF (SE) do Python 3 no Linux Mint Exemplo-01<br>
Link de apoio: https://www.w3schools.com/python/gloss_python_if_statement.asp<br>
Link de apoio: https://www.w3schools.com/python/python_conditions.asp
```python
#CENÁRIO 04: trabalhando com IF para uma nova versão do IRPF (modo simples)

#Salvar o arquivo de script com o nome: 33-irpfv2.py no diretório: ScriptsPython
#Executar o script com a opção: F5 ou Ctrl+F5 ou clicar o ícone: Run Python File

#Link dos valores: https://www.gov.br/receitafederal/pt-br/assuntos/meu-imposto-de-renda/tabelas/2024
#Link dos valores: https://www.gov.br/inss/pt-br/noticias/confira-as-aliquotas-de-contribuicao-ao-inss-com-o-aumento-do-salario-minimo

#!/usr/bin/python3
#Instalando o módulo: Tabulate (Tabulador) do Python: pip install tabulate
#Importando a Função Tabulate do Módulo Tabulate para o projeto do Python
from tabulate import tabulate

#Criando a Tabela de Alíquotas do IRPF 2024 utilizando o Módulo Tabulate
tabela_irpf2024 = [ 
	["Base de Cálculo", "Alíquota", "Dedução"],
	["Até 2.259,20", "0%", "0,00"],
	["De 2.259,21 até 2.826,65", "7,5%", "169,44"],
	["De 2.826,66 até 3.751,05", "15.0%", "381,44"],
	["De 3.751,06 até 4.664,68", "22,5%", "662,77"],
	["Acima de 4.664,68", "27,5%", "896,00"],
]

#Bloco de digitação dos Valores para o Cálculo do IRPF 2024
print("Digite os valores para o Cálculo do IRPF 2024")
renda_bruta = float(input("Digite a sua Renda Bruta Mensal.: "))
salario = renda_bruta
imposto = 0.0
print()

#Bloco de teste lógico das condições verdadeiras utilizando o IF
#O código abaixo verifica a renda_bruta em faixas decrescentes, ajustando o valor do
#imposto de acordo com a alíquota correspondente, o ajuste da faixa da variável da
#renda_bruta garante que cada faixa de renda seja tributada corretamente, sem sobreposição.
if renda_bruta > 4664.68:
    imposto = imposto + ((renda_bruta - 4664.68) * 0.275)
    renda_bruta = 4664.68
if renda_bruta > 3751.06:
    imposto = imposto + ((renda_bruta - 3751.06) * 0.225)
    renda_bruta = 3751.06
if renda_bruta > 2826.66:
    imposto = imposto + ((renda_bruta - 2826.66) * 0.15)
    renda_bruta = 2826.66
if renda_bruta > 2259.21:
    imposto = imposto + ((renda_bruta - 2259.21) * 0.075)
    renda_bruta = 2259.21

#Imprimindo na tela a composição das variáveis de  Números Decimais {}, com a opção de 
#:6.2f que indica que vamos reservar 6 (seis) caracteres para o número inteiro e 2 
#(dois) caracteres de casas decimais e utilizando a formatação F-STRING.
print(f"Renda Bruta Mensal: R$:{salario:6.2f} - Imposto a Pagar: R$:{imposto:6.2f}")

#Imprimindo na Tela a Tabela do IRPF 2024 utilizando a Função Tabulate
#A Função TABULATE() chama os valores da variável: tabela_irpf2024 e passa os parâmetros
#de: headers="firstrow" que usa a primeira linha como cabeçalho, tablefmt="grid"
#que formata a tabela com bordas e stralign="center" que centraliza o Texto.
print(tabulate(tabela_irpf2024, headers="firstrow", tablefmt="grid", stralign="center"))
```
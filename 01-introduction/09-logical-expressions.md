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
#01_ Trabalhando com Módulos e Expressões Lógicas do Python 3 no Linux Mint<br>

#01_ Trabalhando com Módulos e Expressões Lógicas do Python 3 no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/gloss_python_module_import_from.asp
```python
#Instalando o módulo: Tabulate (Tabulador) do Python: pip install tabulate
#Importando a Função Tabulate do Módulo Tabulate para o projeto do Python
from tabulate import tabulate

#Criando a Tabela de IMC (Índice de Massa Corpórea) utilizando o Módulo Tabulate
tabela_imc = [ 
	["De", "Até", "Descrição"],
	["15", "18", "Baixo Peso"],
	["18", "25", "Peso Normal"],
	["25", "30", "Acima do Peso"],
	["30", "40", "Obesidade Grau 1"],
	["40", "60", "Obesidade Grau 2"],
]

#Declarando as Variáveis e Recendo os Valores
seu_peso = float(input("Digite o seu peso: "))
sua_altura = float(input("Digite a sua altura: "))

#Imprimindo na Tela os Valores das Variáveis
print("Seus dados são:", seu_peso, "de peso", "e", sua_altura, "de altura")

#Calculando o IMC com base nos Valores das Variáveis
imc = int(seu_peso / (sua_altura ** 2))

#Imprimindo na Tela do Valor do Cálculo do IMC
print("Seu IMC é:", imc, "Veja a Tabela de IMC para saber mais")

#Imprimindo na Tela da Tabela do IMC utilizando a Função Tabulate
#A Função TABULATE() chama os valores da variável: tabela_imc e passa os parâmetros
#de: headers="firstrow" que usa a primeira linha como cabeçalho e: tablefmt="grid"
#que formata a tabela com bordas.
print(tabulate(tabela_imc, headers="firstrow", tablefmt="grid"))
```

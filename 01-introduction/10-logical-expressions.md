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
#Versão: 0.04<br>

Conteúdo estudado nessa aula:<br>
#01_ Trabalhando com Módulos e Expressões Lógicas do Python 3 no Linux Mint<br>
#02_ Trabalhando com Módulos, Comparação e Expressões Lógicas do Python no Linux Mint<br>
#03_ Trabalhando com Módulos, Funções Pi e de Raiz Quadrada do Python no Linux Mint<br>

A) Você pode optar por importar apenas peças de um módulo, usando a palavra-chave from.

B) A função round() retorna um número de ponto flutuante que é uma versão arredondada do número especificado, com o número especificado de decimais.

#01_ Trabalhando com Módulos e Expressões Lógicas do Python 3 no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/gloss_python_module_import_from.asp
```python
#CENÁRIO 01: Calculando o IMC (Índice de Massa Corpórea) com base no Peso e Altura

#Salvar o arquivo de script com o nome: 17-imc.py no diretório: ScriptsPython
#Executar o script com a opção: F5 ou Ctrl+F5 ou clicar o ícone: Run Python File

#!/usr/bin/python3
# Autor: Robson Vaamonde
# Site: www.procedimentosemti.com.br
# Facebook: facebook.com/ProcedimentosEmTI
# Facebook: facebook.com/BoraParaPratica
# YouTube: youtube.com/BoraParaPratica
# Linkedin: https://www.linkedin.com/in/robson-vaamonde-0b029028/
# Instagram: https://www.instagram.com/procedimentoem/?hl=pt-br
# Github: https://github.com/vaamonde
# Data de criação: 22/07/2024
# Data de atualização: 22/07/2024
# Versão: 0.01
# Testado e homologado para a versão do Python 3.10.x

# Primeiro software (programa) utilizando a linguagem de programação Python 3 que tem o
# objetivo de calcular o IMC (Índice de Massa Corpórea) de Homens ou Mulheres, no final
# será mostrado o valor com base no seu Peso e Altura para consultar na Tabela de IMC.

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

#Declarando as Variáveis e Atribuindo os Valores
seu_peso = float(input("Digite o seu peso: "))
sua_altura = float(input("Digite a sua altura: "))

#Imprimindo na Tela os Valores das Variáveis
print("Seus dados são:", seu_peso, "de peso", "e", sua_altura, "de altura.")
print()

#Calculando o IMC com base nos Valores das Variáveis (Peso dividido pela Altura elevada ao Quadrado)
imc = int(seu_peso / (sua_altura ** 2))

#Imprimindo na Tela do Valor do Cálculo do IMC e usando o parâmetro END para criar
#uma quebra de duas linhas (\n\n) sem precisar usar mais uma função PRINT()
print("Seu IMC é:", imc, "Veja a Tabela de IMC para saber mais.", end='\n\n')

#Imprimindo na Tela a Tabela do IMC utilizando a Função Tabulate
#A Função TABULATE() chama os valores da variável: tabela_imc e passa os parâmetros
#de: headers="firstrow" que usa a primeira linha como cabeçalho, tablefmt="grid"
#que formata a tabela com bordas e stralign="center" que centraliza o Texto.
print(tabulate(tabela_imc, headers="firstrow", tablefmt="grid", stralign="center"))
```

#02_ Trabalhando com Módulos, Comparação e Expressões Lógicas do Python no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/ref_func_round.asp
```python
#CENÁRIO 02: Calculando a Média Aritmética e Ponderada das Provas e Trabalhos

#Salvar o arquivo de script com o nome: 18-notas.py no diretório: ScriptsPython
#Executar o script com a opção: F5 ou Ctrl+F5 ou clicar o ícone: Run Python File

#!/usr/bin/python3
# Autor: Robson Vaamonde
# Site: www.procedimentosemti.com.br
# Facebook: facebook.com/ProcedimentosEmTI
# Facebook: facebook.com/BoraParaPratica
# YouTube: youtube.com/BoraParaPratica
# Linkedin: https://www.linkedin.com/in/robson-vaamonde-0b029028/
# Instagram: https://www.instagram.com/procedimentoem/?hl=pt-br
# Github: https://github.com/vaamonde
# Data de criação: 22/07/2024
# Data de atualização: 22/07/2024
# Versão: 0.01
# Testado e homologado para a versão do Python 3.10.x

# Segundo software (programa) utilizando a linguagem de programação Python 3 que tem o
# objetivo de calcular as notas da Provas, Trabalhos e Faltas de um aluno do curso de
# matemática utilizando cálculos de média aritmética, ponderada e porcentagem simples.

#Atribuição dos Valores das Variáveis Estáticas das Provas, Trabalhos, Faltas e Aulas
provas = 7.0
trabalhos = 6.0
faltas = 0.75
aulas = 10

#Bloco de digitação das Notas das Provas
print("Digite as Notas das Provas 01, 02 e 03", end='\n\n')
prova01 = float(input("Digite a nota da Prova 01: "))
prova02 = float(input("Digite a nota da Prova 02: "))
prova03 = float(input("Digite a noa da Prova 03: "))
print()

#Bloco de digitação das Notas dos Trabalhos
print("Digite as Notas dos Trabalhos 01 e 02", end='\n\n')
trabalho01 = float(input("Digite a nota do Trabalho 01 com Peso 2: "))
trabalho02 = float(input("Digite a nota do Trabalho 02 com Peso 3: "))
print()

#Bloco de digitação do Total de Frequência do Aluno
print("Digite o Total de Frequência do Aluno no Curso: ", end='\n\n')
presencas = int(input("Digite o total de Frequência do Aluno: "))
print()

#Bloco de processamento das notas das Provas, Trabalhos e Frequência
resultado_provas = float(((prova01 + prova02 + prova03) / 3))
resultado_trabalhos = float(((trabalho01 * 2) + (trabalho02 * 3)) / 5) 
resultado_presencas = float((presencas / aulas))

#Bloco do Resultado do processamento das Provas, Trabalhos e Frequência
print("Média Aritmética das Provas........: ", round(resultado_provas, 1))
print("Média Ponderada dos Trabalhos......: ", round(resultado_trabalhos, 1))
print("Percentual de Frequência nas Aulas.: ", int((resultado_presencas * 100)),"%")
print()

#Bloco Final do Resultado de Aprovação nas Provas, Trabalhos e Frequência 
print("Resultado Final das Provas, Trabalhos e Frequência (TRUE=Aprovado | FALSE=Reprovado)")
print("Resultado das Provas......:", (resultado_provas >= provas))
print("Resultado dos Trabalhos...:", (resultado_trabalhos >= trabalhos))
print("Resultado das Frequências.:", (resultado_presencas >= faltas))
```

#03_  Trabalhando com Módulos, Funções Pi e de Raiz Quadrada do Python no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/gloss_python_module_import_from.asp
```python
#CENÁRIO 03: Calculando o Pi e Raiz Quadrada de Dois com o Módulo Math

#Salvar o arquivo de script com o nome: 19-math.py no diretório: ScriptsPython
#Executar o script com a opção: F5 ou Ctrl+F5 ou clicar o ícone: Run Python File

#!/usr/bin/python3
# Autor: Robson Vaamonde
# Site: www.procedimentosemti.com.br
# Facebook: facebook.com/ProcedimentosEmTI
# Facebook: facebook.com/BoraParaPratica
# YouTube: youtube.com/BoraParaPratica
# Linkedin: https://www.linkedin.com/in/robson-vaamonde-0b029028/
# Instagram: https://www.instagram.com/procedimentoem/?hl=pt-br
# Github: https://github.com/vaamonde
# Data de criação: 22/07/2024
# Data de atualização: 22/07/2024
# Versão: 0.01
# Testado e homologado para a versão do Python 3.10.x

# Terceiro software (programa) utilizando a linguagem de programação Python 3 que tem o
# objetivo de utilizar o valor de Pi (constante matemática da circunferência de um círculo
# e seu diâmetro) e um cálculo simples de Raiz Quadrada de 2 utilizando o Módulo Math 

#Importando as Funções Pi e Sqrt do Módulo Math para o projeto do Python
from math import pi, sqrt

#Atribuindo os Valores das Variáveis Dinâmicas 
valor_pi = float(pi)
valor_raiz = float(2.0)

#Bloco do Resultado do processamento dos Valores de Pi e Raiz Quadrada de Dois
print("Se você precisar saber o valor do Pi, pode usar a Função math.pi que retorna o valor de:", valor_pi)
print("Se você precisar saber o valor da Raiz Quadrada de: " + str(valor_raiz), ", pode usar a Função math.sqrt que retorna o valor de:", sqrt(valor_raiz))

#Bloco do Resultado do Arredondamento dos Valores de Pi e Raiz Quadrada de Dois
print("Se quiser o valor arredondado de Pi:", round(valor_pi,2))
print("Ou o valor arredondado da Raiz Quadrada:", round(sqrt(valor_raiz),2))
```
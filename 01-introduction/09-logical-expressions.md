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
#01_ Trabalhando com Módulos e Expressões Lógicas do Python 3 no Linux Mint<br>
#02_ Trabalhando com Módulos, Comparação e Expressões Lógicas do Python no Linux Mint<br>

#01_ Trabalhando com Módulos e Expressões Lógicas do Python 3 no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/gloss_python_module_import_from.asp
```python
#CENÁRIO 01: Calculando o IMC (Índice de Massa Corpórea) com base no Peso e Altura

#Salvar o arquivo de script com o nome: 15-imc.py no diretório: ScriptsPython
#Executar o script com a opção: F5 ou Ctrl+F5 ou clicar o ícone: Run Python File

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
print("Seus dados são:", seu_peso, "de peso", "e", sua_altura, "de altura.")
print()
#Calculando o IMC com base nos Valores das Variáveis (Peso dividido pela Altura elevada ao Quadrado)
imc = int(seu_peso / (sua_altura ** 2))

#Imprimindo na Tela do Valor do Cálculo do IMC e usando o parâmetro END para criar
#uma quebra de duas linhas (\n\n) sem precisar usar mais uma função PRINT()
print("Seu IMC é:", imc, "Veja a Tabela de IMC para saber mais.", end='\n\n')

#Imprimindo na Tela da Tabela do IMC utilizando a Função Tabulate
#A Função TABULATE() chama os valores da variável: tabela_imc e passa os parâmetros
#de: headers="firstrow" que usa a primeira linha como cabeçalho, tablefmt="grid"
#que formata a tabela com bordas e stralign="center" que centraliza o Texto.
print(tabulate(tabela_imc, headers="firstrow", tablefmt="grid", stralign="center"))
```

#02_ Trabalhando com Módulos, Comparação e Expressões Lógicas do Python no Linux Mint<br>
Link de apoio: https://www.w3schools.com/python/ref_func_round.asp
```python
#CENÁRIO 02: Calculando a Média Aritmética e Ponderada das Provas e Trabalhos

#Salvar o arquivo de script com o nome: 16-notas.py no diretório: ScriptsPython
#Executar o script com a opção: F5 ou Ctrl+F5 ou clicar o ícone: Run Python File

#Declaração das Variáveis Estáticas das Provas, Trabalhos, Faltas e Aulas
provas = 7.0      #Atribuindo o valor da média aritmética de aprovação das Provas
trabalhos = 6.0   #Atribuindo o valor da média aritmética de aprovação dos Trabalhos
faltas = 0.75     #Atribuindo o valor de percentual de faltas no curso de 25%
aulas = 10        #Atribuindo o valor de total de alunos do curso

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
print("Digite o Total de Frequência do Aluno: ", end='\n\n')
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

#Bloco Final do Resultado se foi aprovado nas Provas, Trabalhos e Frequência 
print("Resultado Final das Provas, Trabalhos e Frequência (TRUE=Aprovado | FALSE=Reprovado)")
print("Resultado das Provas......:", (resultado_provas >= provas))
print("Resultado dos Trabalhos...:", (resultado_trabalhos >= trabalhos))
print("Resultado das Frequências.:", (resultado_presencas >= faltas))
```
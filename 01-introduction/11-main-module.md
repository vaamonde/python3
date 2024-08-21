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

A) Comentários podem ser usados ​​para explicar o código Python, tornar o código mais legível ou podem ser usados ​​para impedir a execução ao testar o código<br>
B) A função help() executa o sistema de ajuda integrado e o conteúdo do Docstring<br>

Conteúdo estudado nessa aula:<br>
#01_ Trabalhando com Docstring, Help e Import do Python 3 no Linux Mint<br>
#02_ Trabalhando com Import e Cálculos do IRPF do Python 3 no Linux Mint<br>

#01_ Trabalhando com Docstring e Help() do Python 3 no Linux Mint<br>
Link de apoio: https://www.w3schools.com/Python/python_comments.asp
Link de apoio: https://www.w3schools.com/python/python_ref_functions.asp
```python
#CENÁRIO 01: criando o arquivo de cálculo simples de IRPF 2024

#Salvar o arquivo de script com o nome: irpfv1.py no diretório: ScriptsPython
#Executar o script com a opção: F5 ou Ctrl+F5 ou clicar o ícone: Run Python File

#!/usr/bin/python3
#Bloco do Docstring de ajuda HELP() do programa de IRPF 2024
"""
Programa: irpfv1.py
Autor: Robson Vaamonde
Descrição: Cálculo de Imposto de Renda Pessoa Física
1. Constantes Significativas
   Alíquota do Imposto de Renda
   Dedução Padrão  do Imposto de Renda
   Dedução por Dependente do Imposto de Renda
2. Entrada dos Dados
   Renda Bruta Mensal
   Número de Dependentes
   Despesas Escolar
   Pensão Alimentícia
   Despesas Médicas
   Valor Retido na Fonte
3. Cálculos
   Resultado Líquido = Rendimento Bruto - Dedução Padrão - Dedução Dependente
4. Saída dos Dados
   Imposto de Renda Devido
5. Ajuda do Módulo IRPF: 
   Importar o arquivo: import irpfv1
   Ajuda Docstring do arquivo: help(irpfv1) 
"""

#Bloco de variáveis constantes
#Link dos valores: https://www.gov.br/receitafederal/pt-br/assuntos/meu-imposto-de-renda/tabelas/2024
#Link dos valores: https://www.gov.br/inss/pt-br/noticias/confira-as-aliquotas-de-contribuicao-ao-inss-com-o-aumento-do-salario-minimo
aliquota_irpf=float((0 + 7.5 + 15 + 22.5 + 27.5) / 5)
deducao_irpf=float((0 + 169.44 + 381.44 + 662.77 + 896.0) / 5)
deducao_inss=float((7.5 + 9 + 12 + 14) / 4)
deducao_dep=float(189.59)
```

#02_ Trabalhando com Import e Cálculos do IRPF do Python 3 no Linux Mint<br>
```python
#CENÁRIO 02: criando o arquivo para importar o cálculo simples de IRPF 2024

#Salvar o arquivo de script com o nome: 29-irpfv1.py no diretório: ScriptsPython
#Executar o script com a opção: F5 ou Ctrl+F5 ou clicar o ícone: Run Python File

#!/usr/bin/python3
#Importando os Módulos do arquivo irpfv1.py e Sistema sys para o projeto do Python
import irpfv1, sys

#Bloco do Resultado do processamento dos Valores das Variáveis do Módulo IRPF 2024
print("Valores das Variáveis Constante do Módulo IRPF")
print("Alíquota padrão (Média Aritmética) do IRPF:", str(irpfv1.aliquota_irpf)+"%")
print("Dedução padrão (Média Aritmética) do IRPF.:", "R$: "+str(irpfv1.deducao_irpf))
print("Dedução padrão de Dependentes do IRPF.....:", "R$: "+str(irpfv1.deducao_dep))
print("Dedução padrão (Média Aritmética) do INSS.:", str(irpfv1.deducao_inss)+"%", end="\n\n")

#Bloco de digitação dos Valores para o Cálculo do IRPF 2024
print("Digite os valores para o Cálculo do IRPF")
renda_bruta=float(input("Digite a sua Renda Bruta Mensal.....: "))
numero_dep=int(input("Digite o número de dependentes......: "))
despesas_escola=float(input("Digite o valor das Despesas Escolar.: "))
despesas_saude=float(input("Digite o valor das Despesas em Saúde: "))
pensao_alim=float(input("Digite o valor da Pensão Alimentícia: "))
print()

#Bloco do Resultado do processamento dos Valores das Variáveis Dinâmicas
print("Valores das Variáveis Dinâmicas Digitadas")
print(f"Renda Bruta Mensal.....R$: {renda_bruta:5.2f}",
      f"Número de Dependentes....: {numero_dep}",
	  f"Despesas Escolar.......R$: {despesas_escola:5.2f}",
	  f"Despesas Médicas.......R$: {despesas_saude:5.2f}",
	  f"Pensão Alimentícia.....R$: {pensao_alim:5.2f}",
	  sep="\n", end="\n\n")

#Bloco do Cálculo Matemática (Aritmética) do IRPF 2024
calculo_base=float((renda_bruta - (renda_bruta * (irpfv1.deducao_inss / 100))) - \
				   ((numero_dep * irpfv1.deducao_dep) + 
				   despesas_escola + despesas_saude + pensao_alim))
irpf2024=float((calculo_base * irpfv1.aliquota_irpf / 100) - irpfv1.deducao_irpf)
print(f"Valor do IRPF de 2024 é R$: {irpf2024:5.2f}", end="\n\n")

#Bloco Final do Script em Python do IRPF com encerramento do Script.
input("Pressione <Enter> para finalizar o script")
sys.exit()
```
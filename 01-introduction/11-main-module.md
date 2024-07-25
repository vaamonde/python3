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
#01_ Trabalhando com Docstring, Help e Import do Python 3 no Linux Mint<br>


#01_ Trabalhando com Docstring, Help e Import do Python 3 no Linux Mint<br>
Link de apoio: 
```python
#CENÁRIO 01: criando o arquivo de cálculo simples de IRPF

#Salvar o arquivo de script com o nome: irpf.py no diretório: ScriptsPython
#Executar o script com a opção: F5 ou Ctrl+F5 ou clicar o ícone: Run Python File

#!/usr/bin/python3
#bloco do Docstring de ajuda HELP() do programa de IRPF
"""
Programa: irpf.py
Autor: Robson Vaamonde
Descrição: Cálculo de Imposto de Rede Pessoa Física
1. Constantes Significativas
   Alíquota do Imposto
   Dedução Padrão
   Dedução por Dependente
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
   Imposto de Rede Devido
5. Ajuda do Módulo IRPF: 
   Importar o arquivo: import irpf
   Ajuda Docstring do arquivo: help(irpf) 
"""

#bloco de variáveis constantes
aliquota_irpf=float((0 + 7.5 + 15 + 22.5 + 27.5) / 5)
deducao_irpf=float((0 + 169.44 + 381.44 + 662.77 + 896.0) / 5)

#Salvar o arquivo de script com o nome: 20-irpf.py no diretório: ScriptsPython
#Executar o script com a opção: F5 ou Ctrl+F5 ou clicar o ícone: Run Python File

#!/usr/bin/python3
#Importando o Módulo do arquivo irpf.py para o projeto do Python
import irpf

#bloco do Resultado do processamento dos Valores das Variáveis do Módulo IRPF
print("Alíquota padrão (Média Aritmética) do IRPF:", str(irpf.aliquota_irpf)+"%")
print("Dedução padrão (Média Aritmética) do IRPF:", "R$: "+str(irpf.deducao_irpf))
```

#Autor: Robson Vaamonde<br>
#Procedimentos em TI: http://procedimentosemti.com.br<br>
#Bora para Prática: http://boraparapratica.com.br<br>
#Robson Vaamonde: http://vaamonde.com.br<br>
#Facebook Procedimentos em TI: https://www.facebook.com/ProcedimentosEmTi<br>
#Facebook Bora para Prática: https://www.facebook.com/BoraParaPratica<br>
#Instagram Procedimentos em TI: https://www.instagram.com/procedimentoem<br>
#YouTUBE Bora Para Prática: https://www.youtube.com/boraparapratica<br>
#Data de criação: 21/08/2024<br>
#Data de atualização: 22/08/2024<br>
#Versão: 0.02<br>

Conteúdo estudado nessa aula:<br>
#01_ Utilizando o PDB (Python Debugger) do Python 3 no Terminal do Linux Mint<br>

A) O módulo pdb (Python Debugger) define um depurador de código-fonte interativo para programas Python. Ele suporta configuração de breakpoints (condicionais) e single stepping no nível da linha de origem, inspeção de stack frames, listagem de código-fonte e avaliação de código Python arbitrário no contexto de qualquer stack frame. Ele também suporta depuração post-mortem e pode ser chamado sob controle do programa.

#01_ Utilizando o PDB (Python Debugger) do Python 3 no Terminal Linux Mint<br>
Link de apoio: 
```python
#Utilizando a Biblioteca/Módulo PDB (Python Debugger) no Terminal do Linux Mint

#Primeira etapa: Acessar o diretório de Scripts do Python 3
#opção do comando cd: ~ (atalho do path $HOME)
cd ~/python3/ScriptsPython

#Segunda etapa: Listando o conteúdo do diretório de Scripts do Python 3
#opção do comando ls: -l (long listing format), -h (human-readable)
ls -lh

#Terceira etapa: Debugando o script em Python: 29-irpfv1.py 
#Para sair do PDB (Python Debugger) do Python 3 pressione: Ctrl + D, exit ou quit
#Pressione: Ctrl + L para limpar PDB Python 3 para facilitar o Debugger
#opção do comando python3: -m (module-name), pdb (module python debugger)
python3 -m pdb 29-irpfv1.py 
> /home/vaamonde/python3/ScriptsPython/29-irpfv1.py (3)<module>()
-> import irpfv1, sys   #O módulo do pdb irá parar na primeira linha do script
(Pdb)                   #Prompt de comando da biblioteca do pdb

#Quarta etapa: utilizando o comando Help para obter ajuda do PDB
(Pdb) help

Documented commands (type help <topic>):
========================================
EOF    c          d        h         list      q        rv       undisplay
a      cl         debug    help      ll        quit     s        unt      
alias  clear      disable  ignore    longlist  r        source   until    
args   commands   display  interact  n         restart  step     up       
b      condition  down     j         next      return   tbreak   w        
break  cont       enable   jump      p         retval   u        whatis   
bt     continue   exit     l         pp        run      unalias  where    

Miscellaneous help topics:
==========================
exec  pdb

(Pdb)

#Quinta etapa: listando todo o código fonte do script em Python
(Pdb) list
  1  	#!/usr/bin/python3
  2  	#Importando os Módulos do arquivo irpfv1.py e Sistema sys para o projeto do Python
  3  ->	import irpfv1, sys
  4  	
  5  	#Bloco do Resultado do processamento dos Valores das Variáveis do Módulo IRPF 2024
  6  	print("Valores das Variáveis Constante do Módulo IRPF")
  7  	print("Alíquota padrão (Média Aritmética) do IRPF:", str(irpfv1.aliquota_irpf)+"%")
  8  	print("Dedução padrão (Média Aritmética) do IRPF.:", "R$: "+str(irpfv1.deducao_irpf))
  9  	print("Dedução padrão de Dependentes do IRPF.....:", "R$: "+str(irpfv1.deducao_dep))
 10  	print("Dedução padrão (Média Aritmética) do INSS.:", str(irpfv1.deducao_inss)+"%", end="\n\n")
 11
(Pdb)    #Pressione Enter para listar até o fim do arquivo

[EOF]
(Pdb)    #Fim do arquivo será mostrado o EOF (End Of Line) do Script em Python

#Sexta etapa: executando um Debugger Passo-a-Passo do Script em Python
(Pdb) next   #Você também pode usar a opção: n (next)
> /home/vaamonde/Documentos/python3/ScriptsPython/29-irpfv1.py (6)<module>()
-> print("Valores das Variáveis Constante do Módulo IRPF")
(Pdb)    #Pressionando Enter ele vai debugar o script linha por linha ou digitando: n o next
```
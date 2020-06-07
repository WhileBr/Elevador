# Elevador
Desenvolvimento de um elevador com computercraft e estruturas de frames no minecraft

Conceitos a ser aplicado:

Estrutura de dado fila: https://pt.wikipedia.org/wiki/FIFO

# Instalação
CraftOS 1.77 e superior (minecraft 1.8.9 e superior) <br>
execute: <br>
> wget https://raw.githubusercontent.com/emanuelfranklyn/Elevador/master/instalar.lua instalar.lua <br>
> instalar.lua <br>
- - - - - - - - - - - - - - -
CraftOS 1.4 até 1.76 (minecraft 1.6.4 (ou 1.2.5 com api http ativada nas configurações do mod) até 1.8) <br>
execute: <br>
> lua <br>
> Instalador = http.get("https://raw.githubusercontent.com/emanuelfranklyn/Elevador/master/instalar.lua") <br>
> Install = fs.open("instalar.lua","w") <br>
> Install.write(Instalador.readAll()) <br>
> Install.close() <br> 
> exit() (ou segure *control + t* até aparecer **Terminated** escrito em vermelho) <br> 
> instalar.lua <br>
- - - - - - - - - - - - - - -
**OBS**: A url inserida no passo a passo acima é referente ao instalador desse repositorio, caso você deseje instalar o repositorio original veja as instruções presentes no repositorio original.

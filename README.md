# Elevador
Desenvolvimento de um elevador com computercraft e estruturas de frames no minecraft

Conceitos a ser aplicado:

Estrutura de dado fila: https://pt.wikipedia.org/wiki/FIFO

# Instalação
CraftOS 1.77 e superior (minecraft 1.8.9 e superior)
execute:
wget https://raw.githubusercontent.com/emanuelfranklyn/Elevador/master/instalar.lua instalar.lua
instalar.lua
- - - - - - - - - - - - - - -
CraftOS 1.4 até 1.76 (minecraft 1.6.4 (ou 1.2.5 com api http ativada nas configurações do mod) até 1.8)
execute:
lua
Instalador = http.get("https://raw.githubusercontent.com/emanuelfranklyn/Elevador/master/instalar.lua")
Install = fs.open("instalar.lua","w")
Install.write(Instalador.readAll())
Install.close()
exit() ou segure control + t até aparecer "Terminated" escrito em vermelho
instalar.lua
- - - - - - - - - - - - - - -
OBS: A url inserida no passo a passo acima é referente ao instalador desse repositorio, caso você deseje instalar o repositorio original veja as instruções presentes no repositorio original.

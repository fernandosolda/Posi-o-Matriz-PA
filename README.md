# Posi-o-Matriz-PA
// Disciplina   : [PA]
// Professor   :cintia pinho
// Descri��o   : o programa ve a matriz que deve ser posiocionada
// Autor(a)    :Luis Fernando Osuña Soldá
// Data atual  : 25/11/2021
Var
   matriz:vetor [1..2,1..3] de inteiro
   x,y :inteiro
Inicio
    para y de 1 ate a 3 fa�a
    escreval("Vamos montar uma matriz,escolha a posi��o"(",x,"(",y,")))
    leia (matriz[x,y])
    fimpara
    para x de 1 at� 2 fa�a
    para y de 1 ate a 3 fa�a
    escrvea(matriz[x,y]:3)
    fimpara
    escreval("") //pularlinha
    fimpara
Fimalgoritmo 

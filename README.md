# animaisclassificacao #se #selecao #logica #programacao #émamifero #animalescolhido #seentaosenao 
//Proposta: · Construa um algoritmo que seja capaz de concluir qual dentre os animais seguintes foi escolhido, através de perguntas e respostas.
Animais possíveis: leão, cavalo, homem, macaco, morcego, baleia, avestruz, pingüim, pato, águia, tartaruga, crocodilo e cobra.  
Exemplo: É mamífero ? Sim É quadrúpede ? Sim É carnívoro ? Não É herbívoro ? Sim Então o animal escolhido foi o cavalo.

Algoritmo "escolhaanimal"

Var
// Seção de Declarações das variáveis 
 opcao:caracter
 mamifero, ave, reptil: caracter
 quadruplede,bipede, naovoa: caracter

Inicio
// Seção de Comandos, procedimento, funções, operadores, etc...
Escreval ("Mamifero, ave ou reptil")
leia(opcao)
se (opcao = "mamifero") então
escreval ("quadruplede, bipede, aquatico ou voador")

leia (mamifero)
se (mamifero = "quadruplede") então
escreval ("O animal é carnivoro ou herbivoro")
senão
se (mamifero = "bipede") então
escreval ("onivoro ou frutifero")
senão
se (mamifero = "voador") então
escreval ("morcego")
senão
se (mamifero = "aquatico") então
escreval ("baleia")
senão
escreval ("Fim das opções mamiferos")
fimse
fimse
fimse
fimse
leia(quadruplede)
se (quadruplede = "carnivoro")então
escreval ("O animal é o leão")
senão
se (quadruplede = "herbivoro") então
escreval ("O animal é o cavalo")
senão
escreval ("Fim das opções de quadruplede")
fimse
fimse
leia(bipede)
se (bipede = "frutifero") então
escreval ("macaco")
senão
se (bipede = "onivoro") então
escreval ("Homem")
senão
escreval ("Fim das opções de bipede")
fimse
fimse
senão
//ave
   se (opcao = "ave") então
escreval ("naovoa, rapina ou nadadora")


leia(ave)
se (ave = "naovoa") então
escreval ("Polar ou tropical")
senão
se (ave = "nadadora")então
escreval ("pato")
senao
se (ave = "rapina")então
escreval ("aguia")
senão
escreval ("Fim das opções de aves")
fimse
fimse
fimse
leia(naovoa)
se (naovoa = "polar")então
escreval ("pinguim")
senão
se (naovoa = "tropical")então
escreval ("avestruz")
senão
escreval ("Fim das opções de aves que não voam")
fimse
fimse

senão
se (opcao = "reptil") então
escreval ("com casco, carnivoro, ou sempatas")
senão
escreval ("Fim das opções de repteis")
fimse
fimse
fimse

leia(reptil)
se (reptil = "comcasco") então
escreval ("tartaruga")
senão
se (reptil = "carnivoro") então
escreval ("crocodilo")
senão
se (reptil = "sempatas") então
escreval ("cobra")
senão
escreval("Fim das opções de animais e suas classificações")
fimse
fimse
fimse
Fimalgoritmo

# Exercícios JavaScript - MODULO 15
1. Descrever um algorítmo para resolver o problema da travessia de modo "seguro".
    Um homem precisa atravessar um rio com um barco que possui capacidade apenas
    para carregar ele mesmo e mais um de seus três pertences, que são: um lobo,
    uma cabra e um maço de alfafa. Em cada viagem só poderá ir o homem e apenas
    um de seus pertences. A seguinte regra deverá ser respeitada: o lobo não pode
    ficar sozinho com a cabra e nem a cabra não pode ficar sozinha com o maço de
    alfafa. Escreva um algoritimo para fazer a travessia dos pertences que estão
    em uma margem do rio para a outra.
RESPOSTA:
    1- Homem leva a cabra para a outra margem do rio
    2- Homem volta sozinho
    3- Homem leva o maço de alfafa para a outra margem do rio
    4- Homem volta com a cabra
    5- Homem leva o Lobo para a outra margem do rio
    6- Homem volta sozinho
    7- Homem leva a cabra para a outra margem do rio 

2. JS: Exibir média de 3 números com entradas pelo formulário HTML
    
    RESPOSTA:
    https://jsfiddle.net/thaianebet/4uLjdvcz/14/

# Exercícios JavaScript - MODULO 16
3. Resolva as operações:
    10 + 15 = 25 (number)
    “10” + 2 = 102 (string)
    “10” * 2 = 20 (number)
    “10” / 3 = 3.33333333 (number)
    “10” % 3 = 1 (number)
    10 + true = 11 (number)
    10 == ”10” = true (boolean)
    10 === “10” = false (boolean)
    10 < 11 = true (boolean)
    10 > 12 = false (boolean)
    10 <= 10.1 = true (boolean) 
    10 > 9.99 = true (boolean)
    10 != “dez” = true (boolean)
    10 + true = 11 (number)
    “dez” + true = 10true (string)
    10 + false = 10 (number)
    10 * false = 0 (number)
    true + true = 2 (number)
    10++ = 11 (number)
    10-- = 9 (number)
    1 & 1 = 1 (number)
    1 & 0 = 0 (number)
    0 & 0 = 0 (number)
    0 / 1 = 0 (number)
    5 + 5 == 10 = true (boolean)
    “5” + ”5” == 10 = false (boolean)
    “5” * 2 > 9 = true (boolean)
    (10 + 10) * 2 = 40 (number)
    10 + 10 * 2 = 30 (number)

4. Responda as perguntas de acordo com as variáveis.
var branco = “preto”;
var preto = “cinza”;
var cinza = “branco”;
var carro = “preto”;
var valor = 3000;
var prestacao = 750;

    a) branco == “branco”
        false (boolean)
    b) branco == cinza
        false (boolean)
    c) carro === branco
        true (boolean)
    d) var cavalo = carro == “preto” ? “cinza” : “marron”;
        cinza (string)
    e) Quantas prestações são necessárias para pagar o valor do carro com uma entrada
    de 3.000? Demonstre a operação.
        var qtdeprestacoes = valor/prestacao
        4 prestações
    f) Somando as variáveis de cores é formada uma string de quantos caracteres?
        16 caracteres
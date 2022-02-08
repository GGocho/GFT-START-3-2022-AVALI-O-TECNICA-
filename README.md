# GFT-START-3-2022-AVALI-O-TECNICA-

html
ATV1
class nome 
<meta charset="utf-8"> // correção de acentuação 

	
<script> // emtrada do mundo javaScript

var numeroPrimeiro = parseInt(prompt("informe um numero"));
var numeroSegundo =  parseInt(prompt("informe outro nuemro"));
var numeroTerceiro =  parseInt(prompt("informe outro numero"));
var numeroQuarto =  parseInt(prompt("informe outro numero"));
var numeroQuinto =  parseInt(prompt("informe outro numero")); // criação de 5 variaveis para armazenar numeros
var media = (numeroPrimeiro + numeroSegundo + numeroTerceiro + numeroQuarto + numeroQuinto)/5;// criação de uma variavel para calculo de media



if (numeroPrimeiro == numeroSegundo == numeroTerceiro == numeroQuarto == numeroQuinto){

alert("os 5 numero são iguais");// alerta de numeros iguais

}

if (numeroPrimeiro < numeroSegundo && numeroSegundo < numeroTerceiro && numeroTerceiro < numeroQuarto && numeroQuarto < numeroQuinto){

document.write(" o menor numero é : " + numeroPrimeiro + "<br>");

} else if (numeroSegundo < numeroPrimeiro && numeroPrimeiro < numeroTerceiro && numeroTerceiro < numeroQuarto && numeroQuarto < numeroQuinto){

document.write(" o menor numero é : " + numeroSegundo + "<br>");

} else if (numeroTerceiro < numeroPrimeiro && numeroPrimeiro < numeroSegundo && numeroSegundo < numeroQuarto && numeroQuarto < numeroQuinto){

document.write(" o menor numero é : " + numeroTerceiro + "<br>");

}else if (numeroQuarto < numeroPrimeiro && numeroPrimeiro < numeroSegundo && numeroSegundo < numeroTerceiro && numeroTerceiro < numeroQuinto){

document.write(" o menor numero é : " + numeroQuarto + "<br>");

}else if (numeroQuinto < numeroPrimeiro && numeroPrimeiro < numeroSegundo && numeroSegundo < numeroTerceiro && numeroTerceiro < numeroQuarto){

document.write(" o menor numero é : " + numeroQuinto + "<br>");

} // condição para executar o comenado de aparecer na tela o valor menor 



if (numeroPrimeiro > numeroSegundo && numeroSegundo > numeroTerceiro && numeroTerceiro > numeroQuarto && numeroQuarto > numeroQuinto){

document.write(" o maior numero é : " + numeroPrimeiro + "<br>");

} else if (numeroSegundo > numeroPrimeiro && numeroPrimeiro > numeroTerceiro && numeroTerceiro > numeroQuarto && numeroQuarto > numeroQuinto){

document.write(" o maior numero é : " + numeroSegundo + "<br>");

} else if (numeroTerceiro > numeroPrimeiro && numeroPrimeiro > numeroSegundo && numeroSegundo > numeroQuarto && numeroQuarto > numeroQuinto){

document.write(" o maior numero é : " + numeroTerceiro + "<br>");

}else if (numeroQuarto > numeroPrimeiro && numeroPrimeiro > numeroSegundo && numeroSegundo > numeroTerceiro && numeroTerceiro > numeroQuinto){

document.write(" o maior numero é : " + numeroQuarto + "<br>");

}else if (numeroQuinto > numeroPrimeiro && numeroPrimeiro > numeroSegundo && numeroSegundo > numeroTerceiro && numeroTerceiro > numeroQuarto){

document.write(" o maior numero é : " + numeroQuinto + "<br>");

} // comando de aparecer na tela o valor maior 

document.write("A media dos numeros são adicionados são: ");

document.write(Math.round(media)); // mostrar a media calculada 



</script>

















html
ATV2
class pessoa

<meta charset="UTF-8">// correção de acentuação 

<script> // entrada no mundo javaScript

var nomeP = "joao";
var nomeS = "leandro";
var nomeT = "paulo";
var nomeQ = "jessica"; //input de nomes
var idade1 = 15
var idade2 = 21
var idade3 = 17
var idade4 = 18// input de idades 
document.write("nomes: " + nomeP + "<br>" + nomeS + "<br>" + nomeT + "<br>" + nomeQ + "<br>"); // exibir nomes

document.write(" pessoas acima de 18 anos: " +"<br>" ); 
document.write(nomeP + "<br>" + nomeS + "<br>" + nomeQ + "<br>"); // exibir nomes maior de 18 anos

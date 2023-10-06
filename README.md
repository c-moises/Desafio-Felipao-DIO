# Desafio-Felipao-DIO
Classificador de Nível de Herói
//Com switch case
const nome = "vegeta"
const xp = 1999

let nivel = ""

switch (true) {
  case xp <= 1000:
    nivel = "ferro";
    break;
  case xp >= 1001 && xp <= 2000:
    nivel = "bronze";
    break;
  case xp >= 2001 && xp <=5000:
      nivel = "Prata"
      break;
  case xp >= 6001 && xp <= 7000:
    nivel = "Ouro"
    break;
  case xp >= 7001 && xp <= 8000:
    nivel = "Platina"
    break;
  case xp >= 8001 && xp <= 9000:
    nivel = "Ascendente"
    break;
  case xp >= 9001 && xp <= 10000:
    nivel = "Imortal"
    break;
  default:
    nivel = "Radiante"
}

console.log("O Herói de nome " + nome + " está no nível de " + nivel)  

//Com if
const nome = "Gohan"
const xp = 9999

let nivel;

if (xp <= 1000){
  nivel = "ferro";
} 
else if (xp >= 1001 && xp <= 2000){
  nivel = "Bronze"
}
else if (xp >= 2001 && xp <= 5000) {
  nivel = "Prata"
}
else if (xp >= 6001 && xp <= 7000){
  nivel = "Ouro"  
}
else if (xp >= 7001 && xp <= 8000 ){
  nivel = "Platina"
}
else if (xp >= 8001 && xp <= 9000){
  nivel = "Ascendente"
}
else if (xp >= 9001 && xp <= 10000){
  nivel = "Imortal"
}
else {
  nivel = "Radiante"
}

console.log("O Herói de nome " + nome + " está no nível de " + nivel)  

# Classificador de Nível de Herói
Esse é um projeto de JavaScript proposto pela [DIO](https://www.dio.me/). Se trata de um simples algoritmo para RPG de um classificador de nível. O objetivo é exerciar a lógica de programação.

## O que devia ser utilizado

- Variáveis;
- Operadores;
- Laços de repetição;
- Estruturas de decisões

  # O código
```
let nome = "ShadowPunch";
let xp = 0;
let random = Math.floor(Math.random() * 10);
let nivel = "Ferro";

while(random <= 7){
    xp += 1000
    if(xp <= 1000){
        nivel = "Ferro";
    }
    else if (xp > 1000 && xp <= 2000){
        nivel = "Bronze";
    }
    else if (xp > 2000 && xp <= 5000){
        nivel = "Prata";
    }
    else if (xp > 5000 && xp <= 7000){
        nivel = "Ouro";
    }
    else if (xp > 7000 && xp <= 8000){
        nivel = "Platina";
    }
    else if (xp > 8000 && xp <= 9000){
        nivel = "Ascendente";
    }
    else if (xp > 9000 && xp <= 10000){
        nivel = "Imortal";
    }
    else{
        nivel = "Radiante"
    }
    random = Math.floor(Math.random() * 10);
}

console.log("O Herói de nome " + nome + " está no nível de " + nivel)
```

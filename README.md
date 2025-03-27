
let nomes =["Luis","Mateus","Rafael","Davi","Anna"];
console.log(nomes[3]);

nomes[0]= "Isaac";
nomes.push("Felipe");

nomes.pop;
console.log(nomes);

const original =[2,4,6,8];
const original_dobro= original.map(function(num){
    return num*2;
})

console.log(original_dobro);


let numeros = [1, 3, 5, 7, 9];
let maioresQueCinco = numeros.filter(num => num >5);
console.log(maioresQueCinco);

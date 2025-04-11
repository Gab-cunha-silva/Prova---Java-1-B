# Prova---Java-1-B
Gabriel Cunha da Silva

//Exercício 1
Alternativa D


//Exercício 2
Alternativa B


//Exercício 3
let Banco = []
Banco.push("Gabriel")
Banco.push("Maria")
Banco.push("Flávia")
console.log(Banco)
Banco.shift()
Banco.shift()
Banco.shift()
console.log(Banco)


//Exercício 4
let devolucoes = []
const livro1 ={
  titulo: "Fundação",
  autor: "Isaac Asimov",
  atrasado: "Não",
}
const livro2 ={
  titulo: "Todas as suas imperfeições",
  autor: "Collen Hover",
  atrasado: "Não",
}
const livro3 ={
  titulo: "Drácula",
  autor: "Bram Stoker",
  atrasado: "Não",
}
devolucoes.unshift(Livro1)
devolucoes.unshift(Livro2)
devolucoes.unshift(Livro3)
console.log(Livro1)
console.log(Livro2)
console.log(Livro3)
console.log(devolucoes.pop())
console.log(devolucoes.pop())
console.log(devolucoes.pop())
console.log(devolucoes)


//Exercício 5
const tipo_ingresso = function(idade) {
  if (idade<12){
    return "Ingresso Infantil"
  } else if ((idade>11)&&(idade<18)){
    return "Ingresso Adolescente"
  } else if ((idade>17)&&(idade<60)){
    return "Ingresso Adulto"
  } else {
    return "Ingresso Sênior"
  }
}
console.log("Tipo de ingresso: " + tipo_ingresso(18))

# prova-1bim
//atividade 3
let banco = []
banco.unshift('Julia', 'Paulo', 'Roberto')
console.log(banco)

banco.shift()
console.log(banco)

banco.shift()
console.log(banco)

banco.shift()
console.log(banco)

//atividade 4
let devoluções = []
const livro1 = {
    título:'A casa branca',
    autor: 'João Batista',
    atrasado: false
};
const livro2 ={
    título: 'Viagem ao centro da terra',
    autor: 'Julio Verme',
    atrasado: true
};
const livro3 = {
    título: 'Estrela dourada',
    autor: 'Clarisse Linspector',
    atrasado: false
}
devoluções.unshift(livro1, livro2, livro3)
console.log(livro1)
console.log(livro2)
console.log(livro3)
devoluções.pop()
console.log(devoluções)
devoluções.pop()
console.log(devoluções)
console.pop()
console.log


//atividade 5
let idade= 20
if (idade<=12) {
    console.log('Ingresso infantil')
}
else if (idade<=17) {
    console.log('ingresso adolescente')
}
else if (idade<=59) {
    console.log('Ingresso adulto')
}
else {
    console.log('ingresso sênior')
}

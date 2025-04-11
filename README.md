# C-digo-aula-objetos-1
const estudante = {
    nome: "Melissa",
    idade: 15,
    prontuario: 12345,
    bolsista: true,
    telefones: ["1234-5678", "8765-4321"]
}

// verificar se existe a propriedade endereço
const chaveObjeto = Object.keys(estudante)
console.log("", chaveObjeto)

if (!chaveObjeto.includes("endereco")){ // se propriedade end não existe
    console.error("É necessário ter um endereço cadastrado") // mensagem de erro
}else {
    console.log("Endereço cadastrado")
}

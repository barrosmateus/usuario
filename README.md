# usuario
aula básica de programação - desafio 4

 const usuario = {
     nome: 'carlos',
     idade: 32,
     tecnologias:[
         {linguagem: 'c++', especialidade:'desktop'},
         {linguagem: 'python', especialidade:'inteligencia artificial'}
     ]
 }
 console.log(`o programador ${usuario.nome} tem ${usuario.idade} e usa a linguagem ${usuario.tecnologias[0].linguagem} com especialidade em ${usuario.tecnologias[0].especialidade}`)

typeof n - printa o tipo da variável n

window.alert('minha mesagem') //alerta
window.confirm('está gostando?') //confirmação
window.prompt('qual seu nome?') //prompt com campo de texto

	CONVERSÃO DE TIPOS

Number.parseInt(n) - converte uma string em int
Number.parseFloat(n) - converte uma string em float
Number(n) - converte o n em número
String(n) - converte um número em string
 n.toString ''


	IMPRESSÃO DE STRING COM TIPOS DE DADOS

'o aluno' + nome + 'com a idade' + idade + 'tirou a nota' + nota

TAMPLATE STRING:
`o aluno ${nome} com a idade ${idade} tirou a nota ${nota}`

	'o aluno lucas com a idade 22 tirou a nota 7.5'

	FORMATAR STRINGS

s.length - mostra o tamanho da string
s.toUpperCase() - transforma em maiúscula
s.toLowerCase() - transforma em minúscula

	FORMATAR NÚMEROS
n1.toFixed(2) - duas casas decimais
n1.toFixed(2).replace('.',',') troca o ponto por vírgula

	ESCREVER NO DOCUMENTO

document.write(`Seu nome é ${nome}`)
document.write(`<h2>Seu nome é ${nome}</h2`)
document.writeln(`Seu nome é ${nome}`)

	FORMATAR EM DINHHEIRO

n1.toLocaleString('pt-BR', {style: 'currency', currency: 'BRL'})



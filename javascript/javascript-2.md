
# Javascript

- Estado do JS (2020.statofjs)
- Onde é executado (ok)
Omnipresente na WEB


## Fundamentos JS

## Funções

- Evitar a repetição de código
- Realizar chamadas dinâmicas de algorítimos

function calcularMedia( notas ) {
	
	var soma = 0;
	for( c = 0; c < notas.length; c++ ) {
		soma += notas[c];
	}

	media = soma / notas.length;

	return media;

}

function aprovacao( notas ) {
	
	let media = calcularMedia( notas );

	let condicao = media >= 8 ? "Aprovado" : "Reprovado";

	return "Média: " media + ' - ' condicao;
}

console.log( "Media: " + calcularMedia([8, 8, 10]))
console.log( aprovacao( calcularMedia([8, 8, 10])))
console.log( aprovacao([8, 8, 10]))

console.log( "Media: " + calcularMedia([8, 8, 10, 6]))
console.log( aprovacao( calcularMedia([8, 8, 10, 6])))
console.log( aprovacao([8, 8, 10, 6]))

console.log( "Media: " + calcularMedia([8, 8, 7, 8]))
console.log( aprovacao( calcularMedia([8, 8, 7, 8])))
console.log( aprovacao([8, 8, 7, 8]))
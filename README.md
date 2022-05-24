# Calculo-da-Media

# ALGORITMO

inicio
	escreva "Digite a nota de AC1:  "
	ler notaum

	escreva "Digite a nota de AC2:  "
	ler notadois

	escreva "Digite a nota de AG:  "
	ler notaag

	escreva "Digite a nota de AF:  "
	ler notaaf
	
	notaum = notaum * 0.15
	notadois = notadois * 0.3
	notaag = notaag * 0.1
	notaaf = notaaf * 0.45

	resultado = notaum + notadois + notaag + notaaf
	
	se resultado >= 5 faca
		escreva "Aluno Aprovado"
	senão 
		escreva "Aluno Reprovado"
	fimse
fim




# FLUXOGRAMA

![Fluxograma calculo da media](https://user-images.githubusercontent.com/101130228/169937148-5b9a1738-ca87-4a22-987c-d47700c6d055.png)

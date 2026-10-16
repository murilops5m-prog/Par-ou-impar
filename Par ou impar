import random
acertos = 0
erros = 0
while True:
	numero = random.randint(1,10)
	result = numero % 2
	if result == 0:
		result = 'par'
	else:
		result = 'impar'
	decisao = input('par ou impar? ').lower()
	if decisao == result:
		acertos += 1
		print('acerto miseravel!!')
	else:
		erros += 1
		print('errou kkkkkkk! era',result)
	sair = input ('escreva sair se quiser desistir! e veja sua pontuação ').lower()
	if sair == 'sair':
		print('cagão!')
		print('acertos:',acertos, 'erros:',erros)
		break

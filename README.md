nome = input('Digite seu nome')
ano_que_nasceu = int(input('Digite seu ano de nascimento:'))
ano_atual = int(input('digite ono atual:'))

idade = ano_atual-ano_que_nasceu
resultado = f"{nome}possui a´proximadamente {idade}anos."
print(resultado)

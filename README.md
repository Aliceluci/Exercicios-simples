# Exercicios-simples If/elif

# If é uma forma de colocar condiçãoe em um código
# Elif é a junção de Else + If, que é a continuação da condição

exercicio = int(input('Quantos minutos você se exercita por dia? '))

if exercicio < 30:
    print('Você deveria se exercitar mais!')
elif exercicio >= 30 and exercicio < 60:
    print('Você está no caminho certo!')
elif exercicio >= 60 and exercicio <=120:
    print('Uau,você é um(a) atleta!')
else:
    print('Você se exercita muito')

# Else quer dizer que os próximos valores vão entrar nessa mesma condição, ou seja, não precisa criar novas elif.

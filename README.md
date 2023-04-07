# tabuada_in_python_iniciante
Código utilizando o laço de repetição FOR para gerar a tabuada. Projetos iniciais nos estudos em Python.

for i in range(1, 11):
    for j in range(0, 11):
        print(f'{i} x {j} = ',i*j)
        if i == 10 and j == 10:
            print('_'*10)

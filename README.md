# EP-DSoft
GGG - EP

#input
print('Controle de estoque')
print('0 - sair')
print('1 - adicionar item')
print('2 - remover item')
print('3 - alterar item')
print('4 - imprimir estoque')
escolha = int(input('Faça sua escolha: '))

#estoque

estoque = []
quantidades = []

#opcao 0
if escolha == 0:
    print('Até mais')
    
#opcao 1

elif escolha == 1:
    nome_do_produto = input('Nome do produto: ')
    quantidade = int(input('Quantidade inicial: '))
    
#se a quantidade for negativa ela nao e salva e preinta 'quantidade inicial 
#nao pode ser negativa'
    if quantidade < 0:
        print('quantidade inicial não pode ser negativa.')
    elif quantidade > 0:
        quantidades.append(quantidade)
        
# adiciona o produto e verifica se ele ja esta contido na lista
    if len(estoque) == 0:
            estoque.append(nome_do_produto)
    elif len(escolha) != 0:  
        for e in range(len(estoque)):
            if estoque[e] != nome_do_produto:
                estoque.append(nome_do_produto)
            elif estoque[e] == nome_do_produto:
                print('Produto já está cadastrado.')

#opcao 2
elif escolha == 2:
    nome_do_produto == input('Nome do produto: ')
    
    for e in range(len(estoque)):
        if estoque[e] == nome_do_produto:
            estoque.remove(e)
        else:
            print ("produto nao econtrado")
#opcao 3
elif escolha == 3:
    
    nome_do_produto == input('Nome do produto: ')
    if 
        quantidadenova = int(input('Quantidade: '))
        if quantidadenova +=quatidades[] > 0:
            quantidades[].append(quantidadenova + quatidades[])

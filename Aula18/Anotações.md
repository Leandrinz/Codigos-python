--- Listas (parte 2)
pessoas = []
dados = ['Pedro', 25]
Pra colocar a lista de dados dentro da lista de pessoas:
    pessoas.append(dados[:])
    
    Agora, o elemento 0 de pessoas contém 'Pedro' - Índice 0 dentro do 0 e 25 - índice 1 dentro do 0.
    
    Agora temos uma lista dentro de uma lista
    Em resumo temos o índice 0, com 2 elementos, indo de 0 a 1.

        Pessoas 0 - | 'Pedro' | 25
                         0       1
                           índice
Na sintaxe:
    pessoas = [['Pedro',25], ['Maria', 19], ['João', 32]]
    print(pessoas[0][0]):
        Vai mostrar o item 0 do índice 0, ou seja: Pedro
    print(pessoas[1][1]): 19
    print(pessoas[2][0]): João
    print(pessoas[1]): Maria, 19

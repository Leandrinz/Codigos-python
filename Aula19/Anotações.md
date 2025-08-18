----- DICIONÁRIOS -----
. O primeiro problema que encontramos usando listas, é que indentificavamos os índices através de 0,1,2...
. Agora com os dicionários, podemos identificar esses índices de formas literais. Como 'nome'.

- COMO IDENTIFICAR DICIONÁRIOS:
    . TUPLAS ()
    . lISTAS []
    . DICIONÁRIOS {} ou dados = dict()
    . Exemplo:
        dados = {'nome': 'Pedro', idade: 25 }
        print(dados['nome'])
            pedro

- COMO ADICIONAR ELEMENTOS:
    dados['sexo'] = 'M'

- COMO REMOVER ELEMENTOS:
    del dados['idade']

- EXEMPLOS: 
    # Criando um dicionário
    filme = { 'título': 'Star Wars',
              'ano'   :  1977,
            'diretor' : 'George Lucas'
            }

- OBSERVAÇÕES:
    print(filme.values()) # Mostra 'título', 1977, 'George Lucas'

    print(filme.keys()) # Mostra título, ano, diretor

    print(filme.itens()) # Mostra tudo

    for k,v in filme.itens():
        print(f'O {k} é {v}') # O título é Star Wars

- JUNÇÃO DE LISTAS, TUPLAS E DICIONÁRIOS
    . Dentro de uma lista, é possível colocar dicionários. Onde cada índice representaria um dicionário
    . Exemplo:
        print(locadora[0]['ano']) # Vai no primeiro dicionário e vê o ano

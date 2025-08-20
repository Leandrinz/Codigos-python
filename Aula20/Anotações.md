---- FUNÇÕES (PARTE 1) ---- 
- O que são funções?
    . Está assimilado a uma palavra: Rotina
    . Está relacionado a algo que fazemos constantemente, por exemplo o print(), float()...
    . Podemos criar uma função para criar uma função para mostrar linha. 
        mostraLinha()
    . Personalizamos conforme nossa necessidade

- Como faz?
    .exemplo:
        def mostraLinha():
            print('----------------------')

- Como chamar a função:
    .exemplo:
        mostraLinha()
        print('SISTEMAS DE ALUNOS')
        mostraLinha()
# IMPORTANTE!!!
. Você vai declarar as funções no começo do código e tem que deixar duas linhas separando as funções do código em si.

- Parâmetros:
    Imagine que temos 3 blocos:
        -------------------------
                SISTEMAS
        -------------------------
        -------------------------
                 VASCO
        -------------------------
        -------------------------
                  ABC
        -------------------------
    . Perceba que temos 3 blocos quase iguais, e o que muda é apenas o que está no meio. Podemos também personalizar a função para que personalizemos ela de acordo com o que queremos.
    .exemplo: 
        def mensagem(msg):
            print('--------------')
            print(msg)
            print('--------------')
        . Acabamos de personalizar o bloco conforme nossa vontade
        . E para por ela em atividade, basta fazer:
            mensagem('SISTEMA DE ALUNOS'):
        . E agora quando chamarmos a função:
            mensagem('VASCO'):
                --------------------------
                          VASCO
                --------------------------

- Empacotador de parâmetros:
    contador(5,7,3,1,4) # O contador conta quantos parâmetros foram passados, nesse caso, foram 5
    contador(8,4,7) # 3 parâmetros passados
    . Para termos esse contador, temos que criar uma def dele.
        .exemplo:
            def contador( *num     ):
            # O *num, vai desempacotar os parâmetros.
            ! VEJA O TESTE3.PY

- Trabalhando com Listas:
    valores =  [7,2,5,0,4]
    . Como eu faria para dobrar os valores dentro sem precisar desempacotar?
        . VEJA TESTE3.PY
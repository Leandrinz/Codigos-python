---- FUNÇÕES (PARTE 2) ----
- INTERACTIVE HELP:
    Como faz pra usar:
        help(): Rodar esse comando, faz aparecer no terminal uma série de informações que vão te ajudar.
        .exemplo:
            Se você quiser saber pra que serve um determinado comando, tipo o print:
                help(print) (Parece que no Vscode nn funciona, mas no pycharmy ss)
            . Outra forma é:
                print(input.__doc__)

- DOCSTRINGS:
    . Uma string de documentaçao, o help é um exemplo.
    .exemplo:
        # Você que criou o código vai saber bem como funciona isso aqui.
        def contador(i,f,p):
            c = i
            while c <= f:
                print(f'{c}', end = '..')
                c += p
            print('FIM!')


        contador (2,10,2)
        # Agora se uma pessoa que não foi você vai usar seu código, ela pode usar as docstrings, que é basicamente o que eu já tenho feito nos exercícios, só que invés de usar o #, usa aspas triplas
- PARÂMETROS OFICIAIS:
    def somar(a,b,c):
        s = a + b + c
        print(f'A soma vale (s)')


    somar(3,2,5) # Aqui deu tudo certo, pois o número de parâmetros passados está igual
    somar(8,4) # Mas e agora, ele só tem 2 parâmetros passados?
    Agora entra os parâmetros oficiais:
        def somar(a,b,c=0) # caso não haja 3 parâmetros, o valor de c vai ser 0, evitando que dê erro no programa. Logicamente, para evitar futuros erros, colamos assim:
        def somar(a=0,b=0,c=0)

- ESCOPO DE VARIÁVEIS:  
    . Locais onde a variável existe e não existe.
    . Tipos: 
        . Escopo Global: Funciona em todas as partes
        . Escopo Local: Só existe em algumas partes do código. Quando por exemplo você cria uma variável dentro de uma função, e pede pra printar ela fora da funçao, isso dará erro por que como ela é uma variável local, ela só existe dentro daquela função.

- RETORNANDO VALORES:
    def somar(a=0,b=0,c=0):
        s = a + b + c
        print(f'A soma vale {s}')


    somar(3,2,5)
    # Veja o Teste3.py
# Programa para saber o que cada comando do Python faz. PARA SAIR DO PROGRAMA DIGITE 'FIM'.

cores = ('\033[m',              # 0 - Sem cores
         '\033[0;30;41m',       # 1 - Vermelho
         '\033[0;30;42m',       # 2 - Verde
         '\033[0;30;43m',       # 3 - Amarelo
         '\033[0;30;44m',       # 4 - Azul
         '\033[0;30;45m',       # 5 - Roxo
         '\033[7;40m')          # 6 - Branco


def ajuda(comand):
    titulo(f'Acessando o manual do comando \'{comand}\'', 4)
    print(cores[6], end='')
    help(comand)
    print(cores[0], end='')


def titulo(mensagem, cor=0):
    tamanho = len(mensagem) + 4
    print(cores[cor], end='')
    print('=' * tamanho)
    print(f'  {mensagem}')
    print('=' * tamanho)
    print(cores[0], end='')


comando = ''
while True:
    titulo('SISTEMA DE AJUDA PyHelp', 2)
    comando = str(input('Digite a Função ou Biblioteca que deseja saber a informação: > '))
    if comando.upper() == 'FIM':
        break
    else:
        ajuda(comando)

titulo('Obrigado por usar os softwares do HILÁRIO!', 1)

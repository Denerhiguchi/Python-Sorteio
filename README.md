# Python-Sorteio
aqui no Python coloquei  alguns Alunos aleatórios de um Sorteio
import random
Bruno = input('Digite o nome do aluno 1: ')
Dener = input('Digite o nome do aluno 2: ')
Debora = input('Digite o nome do aluno 3: ')
Elaine = input('Digite o nome do aluno 4: ')
Fernando = input('Digite o nome do aluno 1: ')
Caio =  input('Digite o nome do aluno 2: ')
Jéssica = input('Digite o nome do aluno 3: ')
Roberto = input('Digite o nome do aluno 4: ')

lista = [Bruno, Dener, Debora, Elaine,Fernando,Caio,Jéssica,Roberto]
sorteio = random.choice(lista)
print('O aluno sorteado foi:', sorteio, 'Parabéns !!! ')
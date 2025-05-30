   #lista de forma pratica
    #uma lista pode ser usadas colchetes []
    
alunos = ['joão','pedro','Claudio']
notas = [10,7,8]
    #trabalha com indices joao = 10 pedro = 7 Claudio = 8
    #a lista mais facil
    
    #se usarmos esse codigo ira ser a unica e especifico indice: print(alunos[0],' - ',notas[0])
    #se voce quiser achar um indice mais facilmente seria variavel.index e o elemento que eu queira descobrir o indice varialvel.index('indice')

i = alunos.index('Claudio')
nota = notas [i]
     #o append() e um método de lista que adiciona um elemento ao final de uma list, sendo ultilizado para expandir uma lista nao complexa dicionando um novo elemento sem criar uma nova lista
     
alunos.append('jaja')
notas.append(2)

print(alunos)
print(notas)

print(nota)

     #alguns codigos mais famosos para deletar uma lista sao primeiro remove() 
     #Este método remove o primeiro elemento da lista que corresponde ao valor fornecido
     #Se o valor não estiver na lista, um erro ValueError será lançado
     #exemplo:
     #lista = [1, 2, 3, 4, 3]
     #lista.remove(3)  Remove a primeira ocorrência de 3
     #print(lista)   Saída: [1, 2, 4, 3]
     
     #outro codigo de deletar pop()
     #Este método remove o elemento no índice fornecido e retorna o valor do elemento removido
     #Se nenhum índice for fornecido, ele remove o último elemento da lista
     #lista = [1, 2, 3, 4]
     #elemento_removido = lista.pop(1) # Remove o elemento no índice 1 (que é 2)
     #print(lista) # Saída: [1, 3, 4]
     #print(elemento_removido) # Saída: 2

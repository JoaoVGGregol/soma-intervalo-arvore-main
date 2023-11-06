Soma do intervalo da Árvore Binária de Busca
Dado o nó raiz de uma árvore de pesquisa binária e dois inteiros inicial e final, retorne a soma dos valores de todos os nós com um valor no intervalo inclusivo [inicial, final].

 
Exemplo 1

Entrada: raiz = [10,5,15,3,7,nulo,18], inicial = 7, final = 15
Saída: 32
Explicação: Os nós 7, 10 e 15 estão no intervalo [7, 15]. 7 + 10 + 15 = 32.

 

Exemplo 2

Entrada: raiz = [10,5,15,3,7,13,18,1,nulo,6], inicial = 6, final = 10
Saída: 23
Explicação: Os nós 6, 7 e 10 estão no intervalo [6, 10]. 6 + 7 + 10 = 23.

 

Restrições:

O número de nós na árvore está no intervalo [1, 2 * 104].
1 <= Nó.val <= 105
1 <= inicial <= final <= 105
Todos os Node.val devem ser únicos.

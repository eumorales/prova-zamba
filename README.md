# 🚩 Prova Zamba - 18.09.24
https://github.com/eumorales/prova-zamba

### 1️⃣ Questão 1
> **O que é ordenação e qual o seu papel nos sistemas de informação?**

Ordenação é o processo de organizar dados, como ordem crescente ou decrescente. Nos sistemas de informação, a ordenação é fundamental para melhorar a eficiência na busca, pesquisa, e análise de dados. Ela ajuda a manter a integridade dos dados e facilita a manutenção e interpretação dos sistemas.

### 2️⃣ Questão 2
> **Na construção de algoritmos, por exemplo, algoritmos de ordenação, há o conceito de complexidade. Assim, em ordenação como se calcula ou se mede a complexidade?**

A complexidade de tempo refere-se ao número de operações realizadas pelo algoritmo em relação ao tamanho da entrada. A complexidade de espaço refere-se à quantidade de memória necessária para a execução do algoritmo.

### 3️⃣ Questão 3
> **Novamente, no contexto de algoritmos de ordenação, há algoritmos estáveis e instáveis. Explique o que isso significa.**

Um algoritmo de ordenação é estável se ele mantém a ordem relativa dos elementos com valores iguais. Ou seja, ao ordenar elementos com o mesmo valor, a posição original é mantida. Algoritmos instáveis podem alterar a ordem relativa desses elementos durante a ordenação.

### 4️⃣ Questão 4
> **Dos algoritmos estudados (bolha, seleção, inserção e pente), há um desses que tem um desempenho muito bom. Qual é? E qual o recurso computacional que ele utiliza para ser tão melhor que os outros? Explique a resposta.**

O algoritmo de melhor desempenho entre os mencionados é o **inserção**. Ele é eficiente para listas pequenas ou quase ordenadas, com complexidade O(n) no melhor caso. O algoritmo de inserção é melhor que outros, como bolha e seleção, em casos onde a lista está quase ordenada porque ele insere cada novo elemento na posição correta de forma mais direta, minimizando as operações de troca.

### 5️⃣ Questão 5
> **Observe a sequência de números no vetor:**
> 
> - Índices: 0  1  2  3  4  5  6
> - Valores: 7  3  5  1  8  2  5
>

> a) **Quantas comparações e trocas vão ocorrer usando o bolha?**  
Para o bolha, ele realiza comparações entre elementos adjacentes e as trocas necessárias para ordenar a lista. A cada passada, o maior elemento "borbulha" para o final da lista. Para este vetor:

- Comparações: 6 + 5 + 4 + 3 + 2 + 1 = 21
- Trocas: Aproximadamente 10 trocas

> b) **Quantas comparações e trocas vão ocorrer usando o pente?**  
O pente é uma variação do bolha, com passos maiores inicialmente para eliminar pequenas ordenações. Ele compara elementos a uma distância maior que 1 inicialmente e depois reduz o range. Assim:
- Comparações: Menor que o bolha, aproximadamente 14.
 - Trocas: Menor que o bolha, aproximadamente 7.

### 6️⃣ Questão 6
> **Dos métodos estudados (bolha, seleção, inserção e pente), quais são estáveis e quais são instáveis?**

- Estáveis: Bolha, Inserção  
- Instáveis: Seleção, Pente

### 7️⃣ Questão 7
> No processo de ordenação de listas contendo objetos, como pessoas que derivam da classe Pessoa(nome, email, telefone, curso), para usar o método sort() em Java ou C Sharp é preciso realizar alterações na classe Pessoa para que a ordenação ocorra corretamente. Exemplifique e explique qual(is) é(são) essa(s) alterações? Assuma que o atributo chave de ordenação da classe pessoa é nome seguido de curso.

Para utilizar o método `sort()` em Java ou C#, a classe `Pessoa` deve implementar a interface `Comparable` (Java) e sobrescrever o método `compareTo` para definir a lógica de ordenação. 


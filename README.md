# comparacao_estruturas_grafos
Comparação de tempo de execução e custo de memória dos algoritmos de grafos: Matriz de Adjacência, Matriz de Incidência e Lista de Adjacência.

<h2>Execução</h2>

Para executar o software o usuário deve executar os seguintes passos no termianl dentro da pasta baixada do terminal:

~~~
make 

make run
~~~

Deve-se atentar ao fato que para a execução do arquivo médio, esparço, o usuário deve mudar o tamanho do grafo manualmente no algoritmo, visto que fazer essa alteração dinamicamente dentro do algoritmo estava gerando erros de compilação. O mesmo para o arquivo grande, denso. Já para o arquivo pequeno, modelo, é primordial que mantenha o tamanho padrão de 10 elementos, como se encontra inicialmente.

~~~
Graph G = GraphInitialize(10); <- A edição do tamanho do grafo deve ser feita aqui!
~~~

<h2>Diferenças entre as estruturas</h2>

Nas matrizes de Adjacência o número 1 é usado para representar a ligação entre os vértices, enquanto que nas listas de adjacência o que ocorre é a criação de vetores para cada vértice, esses vetores contém cada vertice que o vertice conhece, assim dependendo de como o usuário a programa, as buscas são bem mais rápidas, pois você só pode ir pelos vértices "amigos" do vértice corrente. Sobre as Matrizes de Incidência, são associações entre vértices, linhas, arestas e colunas. A matriz de adjacência é boa para saber se um vértice é amigo de outro, pois basta testar matriz[v][w]. Em alguns casos, o mais barato é usar as duas representações juntas.

<h2>Tempo de Execução - Matriz de Adjacência</h2>

<h2>Tempo de Execução - Matriz de Incidência</h2>

<h2>Tempo de Execução - Lista de Adjacência</h2>

<h2>Conclusões</h2>

O trabalho sugerido foi muito bom para solidificar meus conhecimentos em grafos e suas formas de representações. tornou minha base em algoritmos mais forte visto a tamanha diversidade de conhecimentos absorvidos no universo de grafos.

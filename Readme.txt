Contextualização  
Na teoria dos grafos, um problema de teste de planaridade é um problema algorítmico que testa se um determinado grafo é plano (ou seja, pode ser desenhado em um plano sem arestas de interseção). Este é um problema bem estudado em ciência da computação, e muitos algoritmos práticos surgiram, muitos dos quais tiram vantagem de novas estruturas de dados.

Problema 
Se um grafo G for um grafo que possui um subgrafo de Kuratowski, então G é não-planar, e apesar de Kuratowski ser um teste elegante, não fornece um algoritmo prático para o teste de planaridade. O primeiro algoritmo incremental para teste de planaridade foi proposto por Auslander que é chamado recursivamente para obter um desenho plano de cada uma dessas partes junto com o circuito. A complexidade de tempo deste algoritmo é cúbica
O problema geral de desenhar um grafo não-planar de tal forma que o número total de cruzamentos de suas arestas seja menor ou igual a um dado inteiro k, é NP completo.

Definição formal 
Os grafos mais importantes do problema em questão são os grafos nomeados na literatura como K3,3 e K5, que tem como características: 
Grafos Simples, Regulares e Não Planares 
A importância desses grafos é que eles são utilizados como bases para testar se outros grafos são planares ou não.

Método

Para a execução foi utilizado o algoritmo de planaridade presente na biblioteca Networkx, cujo é uma biblioteca especializada em manipulação de grafos. Além do algoritmo em si presente na biblioteca, algumas funções da biblioteca foram utilizadas para gerar, manipular ou exibir grafos no terminal. Das funções da biblioteca, as funções e métodos utilizados foram: 

nx.Graph() → cria um grafo networkx
nx.check_planarity() → checa se um grafo é planar, retornando True ou False
nx.draw() → desenha o grafo
nx.draw_planar() → desenha o grafo planar
nx.fast_gnp_random_graph() → gera um grafo aleatório com a quantidade de vértices escolhida.

As configurações do PC que iremos usar são as seguintes:

Hardware sugerido: Aqui um exemplo do que você deve colocar aqui: Processador Intel(R) Core(TM) i3 6006U CPU @ 2,00GHz 1.99GHz, 
com 8GB 2133MHz DDR4 e SSD 240GB + HDD 500GB na versão do sistema operacional Windows 10 Home Single Language.

Lembrem-se que o projeto deve ser disponibilizado em um repositório (como o GitHub) com as seguintes informações disponíveis: 


Contato do desenvolvedor: 

1. Gustavo Henrique da Silva Xavier -	gustavo.xavier@arapiraca.ufal.br
2. João Victor Brito da Silva - 		joao.brito@arapiraca.ufal.br
3. José Alisson Nogueira da Silva - 		jose.alisson@arapiraca.ufal.br

Endereço: UFAL Arapiraca 

Av. Manoel Severino Barbosa
Bom Sucesso
Arapiraca - AL
CEP:57309-005

Ano: 2022

Hardware sugerido: Aqui um exemplo do que você deve colocar aqui: Processador Intel(R) Core(TM) i3 6006U CPU @ 2,00GHz 1.99GHz, 
com 8GB 2133MHz DDR4 e SSD 240GB + HDD 500GB na versão do sistema operacional Windows 10 Home Single Language.

Nome do software: VS Code

Sistema operacional: Windows 10 Home Single Language.
 
Custo: Todas as ferramentas utilizadas são gratuitas.


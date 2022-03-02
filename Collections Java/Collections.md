# Collections 

+ É um objeto que agrupa múltiplos elementos (variáveis primitivas ou objetos) dentro de uma única unidade.
+ Serve para armazenar e processar conjuntos de dados de forma eficiente.



## Composição 

+ **Interfaces**: é um contrato que quando assumido por uma classe deve ser implementado.
+ **Implementações ou classes**: são as materializações, a codificação das interfaces.
+ **Algoritmos**: é uma sequência lógica, finita e definida de instruções que devem ser seguidas para resolver um problema.



## Hierarquia 

<img src = "https://i.stack.imgur.com/YDt8R.png" />



## Interface List

### java.util.List

+ Elementos duplicados e garante ordem de inserção.

**OBS**: *ArrayList* deve ser usado onde mais operações de pesquisa são necessárias, e *LinkedList* deve ser usado onde mais operações de inserção e exclusão são necessárias.



## Interface Set

### java.util.Set

+ Não permite elementos duplicados;
+ Não possui índice.



## Interface Map

### java.util.Map

+ Elementos únicos (key) para cada valor (value).





# Java Streams 

### Objetivos:

1. Classe Anônima
2. Functional Interface
3. Lambda
4. Referência Mathod
5. Stream API



## Classe Anônima

É uma classe que não recebeu um nome e é tanto declarado e instanciado em uma única instrução. Você deve considerar o uso de uma classe anônima sempre que você precisar para criar uma classe que será instanciada apenas uma vez.



## Functional Interface

Qualquer interface com um SAM (Single Abstract Method) é uma interface funcional e sua implementação pode ser tratada como expressões lambda.

+ Comparator
+ Consumer
+ Function
+ Predicate



## Lambda

É uma função sem declaração, isto é, não é necessário colocar um nome, um tipo de retorno e o modificador de acesso. A ideia é que o método seja declarado no mesmo lugar em que será usado. As funções lambda em Java tem a sintaxe definida como (argumento) -> (corpo).



## Reference Method

Permite fazer referência a um método ou construtor de uma classe (de forma funcional) e assim indicar que ele deve ser utilizado num ponto específico do código, deixando-o mais simples e legível. Para utilizá-lo, basta informar uma classe ou referência seguida do símbolo "::" e o nome do método sem os parênteses no final.

**OBS**: a grosso modo, a Reference Method serve para simplificar uma expressão lambda.



## Streams API

Combinada com as expressões lambda, ela proporciona uma forma diferente de lidar com conjuntos de elementos, oferecendo ao dev uma maneira simples e concisa de escrever código que resulta em facilidade de manutenção e paralelização sem efeitos indesejados em tempo de execução.

# Introdução a Java

### Características: 

+ Compilada
+ Interpretada
+ Fortemente tipada
+ Linguagem de alto nível
+ Executada em uma máquina virtual - JVM (Java Virtual Machine)



## O que é a JVM?

"JVM (Java Virtual Machine) - é uma máquina virtual responsável pela tradução dos ByteCodes oriundos do compilador Javac (Java Compiler) em código de máquina de cada sistema operacional."

### Características da JVM

+ Execução de pilhas
+ Gerenciamento de memória
+ Gerenciamento de threads 
+ Otimização de código (Compilação JIT - Just In Time)
+ Garbage Collector (GC)



### Diferenças entre JRE e JDK

+ JRE (Java Runtime Environment) - responsável por executar os programas em Java.
+ JDK (Java Development Kit) - utilitários que permite o desenvolvimento de programas em Java. Já possui a JVM para executar os programas. 



### Tipos de plataformas Java

+ Java SE (Java Standard Edition) - contém as especificações do Java e pode ser implementado por diversas empresas como Oracle, OpenJDK, Azul Zulu, etc.
+ Java EE (Java Enterprise Edition) - contém todas as especificações do Java SE e um número de programas úteis para que executam em servidores. Em 2019 foi renomeado para Jakarta EE.
+ Java ME (Java Micro Edition) - contém especificações para desenvolvimento de programas para dispositivos pequenos como celulares, PDAs, etc. 



# Tipos de Modificadores de acesso

+ public - qualquer classe de qualquer pacote poderá acessar o atributo ou método;
+ protected - qualquer classe definida no mesmo pacote ou subclasse;
+ private - apenas a própria classe;
+ sem modificador - apenas classes definidas no mesmo pacote.



# Métodos

São funções que definem o comportamento de uma classe.



Existem 2 tipos de métodos:

+ Métodos construtores - definem como uma classe será instanciada "construída";
+ Métodos comum - definem comportamentos que podem ou não estar atrivuídas às regras de negócio. Ex: calcular taxas de um pedido, etc.



# O que é Javadoc

É uma ferramenta para documentação no formato HTML que se baseia nos comentários do código-fonte.

Os comentários precisam conter tags para que a documentação fique legível.

## Tags Javadoc

|    Tags     |                           Funções                            |
| :---------: | :----------------------------------------------------------: |
|   @author   |          especifica o autor da classe ou do método           |
| @deprecated |           identifica classes ou métodos obsoletos            |
|    @link    | possibilita a definição de um link p/ um outro documento local ou remoto através de um URL |
|   @param    |      descreve um parâmetro que será passado a um método      |
|   @return   |          descreve qual tipo de retorno de um método          |
|    @see     |             associa a outras classes ou métodos              |
|   @since    |  descreve desde quando uma classe ou métodos foi adicionado  |
|   @throws   | descreve os tipos de exceções que podem ser lançadas por um método |
|  @version   |            descreve a versão da classe ou método             |



# Atalhos no Eclipse

1. F2 - alterar o nome do package 
2. ctrl + d - apagar a linha
3. ctrl + 3 - buscar comandos
4. ctrl + shift + f - reorganizar a indentação 



# Casting (conversões)

É a transformação de uma determinada variável de tipo menos específico para um tipo mais específico ou vice-versa.



→ Tipos:

+ Upcast (implícito)
+ Downcast (explícito)



# Utilização 

|            | byte  | short | char  |  int  | long  | float | double |
| :--------: | :---: | :---: | :---: | :---: | :---: | :---: | :----: |
|  **byte**  | **-** | U - I | char  | U - I | U - I | U - I | U - I  |
| **short**  | D - E | **-** | char  | U - I | U - I | U - I | U - I  |
|  **char**  | D - E | D - E | **-** | U - I | U - I | U - I | U - I  |
|  **int**   | D - E | D - E | D - E | **-** | U - I | U - I | U - I  |
|  **long**  | D - E | D - E | D - E | D - E | **-** | U - I | U - I  |
| **float**  | D - E | D - E | D - E | D - E | D - E | **-** | U - I  |
| **double** | D - E | D - E | D - E | D - E | D - E | D - E | **-**  |

U - I: Upcast - Implícito; D - E: Downcast - Explícito

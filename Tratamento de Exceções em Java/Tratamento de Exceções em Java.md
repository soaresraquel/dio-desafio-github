# Tratamento de Exceções

+ É um evento que interrompe o fluxo normal do processamento de uma classe;
+ O uso correto de exceções torna o programa mais robusto e confiável;
+ Com o tratamento de exceções, um programa pode continuar executando depois de lidar com um problema;

+ Incorpore sua estratégia de tratamento de exceções no sistema desde o princípio do processo do projeto, pois pode ser difícil incluir um tratamento de exceções eficiente depois que um sistema foi implementado.



## Tipos de Exceções

+ **Error**: usado pela JVM que serve para indicar se existe algum problema de recurso do programa, tornando a execução impossível de continuar;
+ **Unchecked (Runtime)**: exceptions que podem ser evitados se forem tratados e analisados pelo dev;
+ **Checked Exception**: Exeptions quem DEVEM ser evitados e tratados pelo dev para o programa funcionar.



## Palavras reservadas para tratamento de exceções

+ **try, catch, finally**: cada uma dessas palavras, juntas, definem blocos para o tratamento de exceções;
+ **throws**: declara que um método pode lançar uma ou várias exceções;
+ **throw**: lança explicitamente uma exception.

# Protocolo HTTP

+ Protocolo de comunicação - Rege a estrutura das mensagens;
+ Browser - Implementa o cliente HTTP;
+ Servidor - Host objetos web.



 ### Cliente

Mensagens - Request HTTP (objetos web)



### Servidor 

Mensagens - Response HTTP (TCP)

+ Stateless - o servidor não armazena o estado do cliente



## Mensagens HTTP



| Métodos |                    Função                     |
| :-----: | :-------------------------------------------: |
|   GET   |        Solicita um recurso do servidor        |
|  HEAD   |           GET sem corpo de resposta           |
|  POST   |       Submete uma entidade a um recurso       |
|   PUT   |     Substituição de recursos pelos dados      |
| DELETE  |             Remoção de um recurso             |
|  TRACE  | Chamada de loop-back a um determinado recurso |
| OPTION  |       Opções de comunicação com recurso       |
| CONNECT |     Tunelamento identificado pelo recurso     |
|  PATCH  |              Modificação parcial              |



### Métodos seguros:

Não carregam nenhuma alteração de estado. São:

+ Get

+ Head

+ Option



## Status Code

| Status                         | Função                                              |
| ------------------------------ | --------------------------------------------------- |
| 200 OK:                        | Request bem sucedida e objeto enviado               |
| 301 MOVED PERMANENTLY          | Objeto realocado nova URL no campo Location         |
| 400 BAD REQUEST                | Reposta genérica - servidor não entendeu a mensagem |
| 404 NOT FOUND                  | Documento solicitado inexistente                    |
| 505 HTTP VERSION NOT SUPPORTED | Versão do protocolo não suportada pelo servidor     |



## Criptografia por Chave

+ Assimétrica
+ Simétrica



### Assimétrica

+ Chave privada
  + Assinatura - criptografia
+ Chave pública
  + Verificação de autenticidade



### Simétrica

+ Chave única privada
  + Conhecimento prévio da chave
    + Cifra de César - Substituição da letra pela k-ésima do alfabeto (rotatividade do alfabeto)

+ Cifra de fluxo
  + Sequência de bits pseudo-aleatório
  + Mapeamento 1 para 1
+ Cifra de bloco
  + SSL, PGP, Ipsec



## Protocolo SSL

+ Segurança para conexões TCP
+ Confidencialidade
+ Integridade 
+ Autenticidade end-point



# API JAVA

Coleção de métodos disponibilizados por um serviço para interação indireta.






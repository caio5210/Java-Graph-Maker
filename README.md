# Java-Graph-Maker

## I) Grupo e Ideias Iniciais

### Grupo:
* João Miguel Descendente
* Caio Meireles Vieira
* Lucas Passos de Siqueira
* Daniel Machado Santos Diaz 
* Henrique Miranda Queiroz

Para o tema do nosso projeto de Compiladores, o nosso grupo decidiu desenvolver uma linguagem para a criação de grafos utilizando o ANTLR e a linguagem de programação Java. durante o andamento de projeto, fomos capazes de criar dois tipos de DSL para desenvolver o problema. Sendo a primeira versão do programa feito com ums DSL interna, ou seja, que usa somente a linguagem de programação Java, onde essa foi chamada de versão 0.5 ou beta. Essa implementação tetve como objetivo testar a compatibilidade do Java com as ideias que tivemos. Já a segunda versão foi uma DSL externa, feita com o ANTLR em conjunto com o Java. 

Link para o [Replit](https://replit.com/join/sqqioaudzv-caiovieira2) do nosso projeto.

Link para o [Replit](https://replit.com/@CaioVieira2/Projeto-de-DSL-Interno) da versão inicial do nosso projeto (DSL Interna).

## II) Motivação

Nosso interesse pelo assunto de grafos gerou o desejo de implementá-los de forma alternativa, sendo assim utilizamos Java e os conhecimentos de compiladores adquiridos ao longo do semestre para criar uma nova linguagem que cria grafos. Essa ideia surgiu, pois as diferentes formas de introduzir e representar um gráfico são: Lista de Adjacência e Matriz de Adjacência. O que é mais difícil de usar, especialmente em linguagens como Java, que não têm matrizes como cidadãos de primeira classe.

## III) Linguagens Utilizadas

A principal linguagem utilizada no rojeto foi o *Java* em conjunto com a ferramente *ANTLR*. 

## IV) Manual

Na versão inicial 0.5 do projeto apenas é necessário executar o código normalmente para ele funcionar. Na versão final do projeto deve ser executado no shell do replit o comando: source Comp.sh pois esse comando faz com que todos os comandos no arquivo Comp.sh sejam executados ao mesmo tempo, o que é necessário para o funcionamento correto do código.

Comandos dentro do Comp.sh:

![image](https://user-images.githubusercontent.com/33666609/148286044-f88d2e29-4cbe-4921-adf7-162aab933393.png)


## V) Informações Adicionais

O nosso codigo ficou dividido em três tipos de arquivos: o arquivo .g4 para o desenvolvimento da nossa gramatica, o nosso arquivo .graph que corresponde a nossa DSL e os arquivos Java para a realização dos codigos. Adicionalmente temos os arquivos gerados pelo ANTLR dentro da Pasta graph.

A nossa principal referencia é o [site do ANTLR](https://www.antlr.org/).

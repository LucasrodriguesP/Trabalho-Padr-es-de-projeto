                                  
## **Aula 09**

*Questão 1: Uma das fontes de informação acerca do clima são as boias meteorológicas de alto 
mar, que emitem sinais para alguns satélites, e estes enviam as informações para um receptor 
em terra, de forma codificada. De uma forma simples, temos uma cadeia de caracteres, onde 
as letras iniciais definem um evento, seguido de parâmetros que podem ser numéricos ou 
literais, em quantidades e tamanhos diversos, obedecendo a padronização para cada tipo de 
evento.*

*Qual padrão de desenvolvimento seria indicado para o decodificador do sistema?*

**A) Template Method** ✅

*B) Abstract Factory*

*C) Memento*

*D) Interpreter*

*E) Chain of Responsibility*


*Questão 2: Os frameworks se tornaram muito comuns na área de desenvolvimento, onde no Java temos 
exemplos como Spring, Struts e Hibernate. Eles definem um arcabouço com todas as funcionalidades 
comuns para determinado domínio de problemas, mas permitem ao desenvolvedor especializar a 
implementação original, para satisfazer aos requisitos apresentados pelo sistema. Na construção do 
framework, um padrão de desenvolvimento muito utilizado é o Template Method.
Qual é a afirmação correta acerca do Template Method?*

**A) O padrão define um algoritmo dividido em vários passos, onde alguns desses passos são a implementação 
da parte comum, enquanto outros são lacunas a serem preenchidas pelo desenvolvedor.** ✅

*B) Para que o padrão possa ser adotado, o princípio da orientação a objetos que deve ser utilizado é o da 
agregação, segundo um relacionamento todo-parte.*

*C) Permite apenas uma derivação do processo original, já que uma das condições impostas pelo padrão é a 
existência de apenas uma instância da classe em todo o ambiente de execução.*

*D) Trabalha com uma sequência de filtros, por onde uma dada requisição deverá passar, efetuando 
modificação específicas em cada filtro utilizado.*

*E) Exige a utilização de comunicação remota, a qual pode ser feita de uma forma transparente para o 
desenvolvedor, com base em Stubs e Skeletons.*


## **Aula 10**

*Questão 1: Uma abordagem comum para o acesso ao banco de dados, nos sistemas atuais, é a
concentração das operações com uso de SQL (Structured Query Language) em uma classe do
tipo DAO (Data Access Object), que deve se comunicar com o restante do sistema através de
entidades ou coleções delas.
Qual padrão GRASP se mostra predominante nesse contexto?*

*A) Polimorfismo*

*B) Especialista na Informação*

**C) Controlador** ✅

*D) Criador*

*E) Acoplamento Fraco*


*Questão 2: Alocação de memória é um dos processos mais caros para a execução de sistemas, exigindo
muitas operações envolvendo a CPU e o barramento. Saber onde criar os objetos, para que tenhamos
maior visibilidade e menor número de instâncias, pode ser um fator decisivo na eficiência do sistema, e
o padrão Criador, do GRASP, define boas práticas no que tange ao assunto.
Qual a opção correta acerca do padrão de desenvolvimento Criador?*

**A) Um dos fatores para escolha do criador é o fato da classe geradora conter as informações
necessárias para inicialização das instâncias geradas.** ✅

*B) Tem como objetivo garantir baixo acoplamento entre as classes.*

*C) Em termos de orientação a objetos, baseiase no princípio do polimorfismo.*

*D) Atribui ao objeto a responsabilidade de mediar diálogos entre componentes.*

*E) Precisa ser definido através de classes abstratas, já que a criação propriamente dita será delegada
ara o sistema operacional.*


## **Aula 11**

*Questão 1: Um dos ferramentais mais interessantes da orientação a objetos é a herança, pois
permite alto reuso estrutural, diminuindo de forma considerável o tempo utilizado no
desenvolvimento de um sistema. Apesar de oferecer uma grande vantagem em termos de reuso,
a criação de uma grande hierarquia de classes pode dificultar ações de manutenção, pois
qualquer modificação repercute em todos os descendentes.
Qual padrão do GRASP estaria sendo violado nessa situação?*

*A) Coesão Alta*

*B) Especialista na Informação*

**C) Controlador** ✅

*D) Criador*

*E) Acoplamento Fraco*

*Questão 2: Um código bem escrito é sempre mais fácil de manter, pois a semântica adequada facilita a
compreensão das entidades e dos processos que atuam sobre elas. Utilizar nomes compreensíveis,
manter os objetos focados em seus reais objetivos e definir um ambiente facilmente gerenciável, estão
entre os muitos elementos que podem ser utilizados para melhorar a semântica e facilitar o uso dos
objetos.
Qual padrão do GRASP demonstra esse tipo de preocupação?*

*A) Acoplamento Baixo*

**B) Especialista na Informação** ✅

*C) Polimorfismo*

*D) Coesão Alta*

*E) Controlador*


## **Aula 012**

*Questão 1: A orientação a objetos tem uma característica adaptativa muito forte, baseada na
alteração funcional de métodos herdados, sem modificação de assinaturas, para que os
descendentes possam ser utilizados em um novo contexto de forma automática.
Qual padrão do GRASP se baseia nessa característica?*

*A) Acoplamento Baixo*

*B) Coesão Alta*

**C) Polimorfismo** ✅

*D) Criador*

*E) Especialista na Informação*

*Questão 2: Nem sempre é fácil garantir acoplamento baixo e alta coesão. Por exemplo, em um
sistema para controle de vendas, teríamos a definição do Especialista na Informação com base na
classe Venda, já que ela detém os dados necessários, mas isso poderia trazer uma dependência
dos componentes JDBC.
Como o padrão Invenção Pura seria utilizado para resolver esse problema?*

*A) Utilizando o polimorfismo e acrescentando a persistência no descendente.*

*B) Eliminando o uso de JDBC e adotando listas em memória.*

*C) Movendo o uso do JDBC para objetos no padrão Criador.*

*D) Deixando os métodos de persistência privados.*

**E) Definindo uma classe de persistência genérica** ✅

.
.
.

Lucas Rodrigues Pereira - 202202293555 - Padrões de Projetos de Software Com Java - Prof RONALDO CANDIDO DOS SANTOS - Sistemas de Informação - Barra World/Recreio

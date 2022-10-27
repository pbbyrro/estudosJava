# Linguagem Java

Java é uma linguagem de computação simples e fácil de compreender. Tudo nela é escrito em CLASSES e OBJETOS.

## Anatomia da Classe - 1

A escrita de códigos de um programa é feita através da composição de palavras pré-definidas pela linguagem com as expressões que utilizamos para determinar o nome dos nossos arquivos, classes, atributos e métodos.
<br/>É muito comum mesclarmos expressões em inglês com o nosso vocabulário.

public class Minha class {

      // CÓDIGO AQUI
}

## Anatomia da Classe - 2
### Padrão de Nomenclatura

Arquivo .java: todo arquivo java deve começar com letra MAIÚSCULA. Se a palavra for composta, a segunda palavra também deve ser maiúscula;

Nome da classe no arquivo: a classe deve possuir o mesmo nome do arquivo.java;

Nome de variável: toda variável deve ser escrita com letra minúscula, porém, se a palavra for composta, a primeira letra da segunda palavra deve ser maiúscula (ex. ano e anoFabricacao). O nome da prática para nomear variáveis dessa forma é “camelCase”;

<br/>A expressão final é utilizada para determinar uma variável que nunca sera alterada (ex. final String BR = “Brasil”). Ela também deve ser escrita em letras MAIÚSCULAS.
<br/>As variáveis devem contar apenas letras, _, $ ou números de 0 a 9.
<br/>As variáveis nunca devem ser iniciadas por número.
<br/>As variáveis devem ser iniciadas por letra minúscula.
<br/>As variáveis não podem conter espaços.
<br/>Não podemos usar palavras-chave da linguagem.
<br/>O nome deve ser único dentro de um escopo.

## Anatomia da Classe - 3
### Declarando variáveis e métodos

Declarar uma variável em java sempre segue a seguinte estrutura:
Tipo NomeBemDefinido = Atribuição (opcional em alguns casos)

Exs.
<br/>int idade = 23;
<br/>double altura = 1.62;
<br/>Dog;
<br/>Ike;


Declarar um método em java sempre segue a seguinte estrutura:
TipoRetorno NomeObjetivoNoInfinitivo Parametro(s)

Exs.

<br/>int somar (int numero1, int numero2)
<br/>String formatarCep (long cep)

Como eu sei diferenciar uma variável de um método? Todo método exige um parâmetro ().

## Anatomia da Classe - 4
### Identação

A identação é uma maneira de escrever o código de forma hierárquica para facilitar a visualização e o entendimento do programa.
No caso do java, indentar não é necessário para que o computador interprete o código, mas é uma boa prática.

## Anatomia da Classe - 5
### Organizando arquivos

À medida que nosso sistema vai evoluindo, surgem novos arquivos (códigos fonte) em nossa estrutura de arquivos do projeto.
Isso exige que seja realizada uma organização destes arquivos através de pacotes (packages).

<br/>com. = comercial
<br/>org. = organizacional
<br/>opensource = opensource

## Anatomia da Classe - 6
### Java Beans

A Java Beans é uma iniciativa conceitual da comunidade de como expressar, através de convenções, formas de escrita universal para classes, atributos, métodos e pacotes.

<br/>Uma variável deve ser clara, sem abreviações ou definições sem sentido;
<br/>Uma variável deve estar sempre no singular, exceto quando se referir a  uma array ou coleções;
<br/>Um idioma único deve ser definido para as variáveis.
<br/>Os métodos devem ser nomeados como verbos através de uma mistura de letras maiúsculas e minúsculas (a primeira letra de cada palavra composta a partir da segunda palavra deve ser maiúscula). 

## Tipos e Variáveis

<br/>As palavras reservadas se referem a tipos primitivos que representam valores brutos. São eles: int, byte, short, long, float, double, boolean e char.
<br/>Embora os quatro primeiros termos sejam usados para números inteiros, é muito comum fazer uso do int.
<br/>Da mesma maneira, embora float e double sejam usados para números fracionados, é muito comum fazer uso do double.
<br/>Para utilizar o tipo float, é necessário inserir um F no final. Da mesma forma, para utilizar o tipo long, é necessário inserir um L no final.
<br/>Já o char se refere ao tipo caracter e permite o uso de apenas um caracter entre aspas simples.

## Operadores

Operadores são símbolos especiais que tem um significado próprio para a linguagem e estão associados a determinadas operações.

<br/>Atribuição: =
<br/>Adição: + (quando utilizado com strings, realiza a concatenação de textos)
<br/>A partir do momento que o código detecta um caracter, ele passa a realizar a concatenação e deixa de realizar a soma.
<br/>Subtração: -
<br/>Multiplicação: *
<br/>Divisão: /
<br/>Módulo (resto da divisão): %
<br/>Igual a: ==
<br/>Diferente: !=
<br/>Maior que: >
<br/>Maior ou igual: >=
<br/>Menor que: <
<br/>Menor ou igual: <=
<br/>Para comparar objetos ao invés de números, é utilizado o método equals.
<br/>Operador lógico E: &&
<br/>Operador lógico OU: ||
<br/>Operador unário de valor positivo: + (números são positivos sem esse operador explicitamente)
<br/>Operador unário de valor negativo: - (nega um número ou expressão aritmética)
<br/>Para tornar um valor negativo positivo, é necessário fazer * -1.
<br/>Operador unário de incremento de valor: ++ (incrementa o valor em uma unidade)
<br/>Operador unário de decremento de valor: -- (decrementa o valor em uma unidade)
<br/>Operador unário lógico de negação: ! (nega o valor de uma expressão booleana)
<br/>O operador ternário (?:) é utilizado para definir uma condição e escolher por um entre dois valores. A condição ternária é como se fosse um IF normal, porém de uma forma que toda a estrutura está escrita em uma única linha.
<br/>Exemplo de estrutura:
<br/><Expressão Condicional> ? <Caso condição seja true> : <Caso condição seja false>

## Métodos

Todas as ações das aplicações são consideradas métodos. Uma classe é definida por atributos e métodos.
Já vimos que atributos são, em sua grande maioria, variáveis de diferentes tipos e valores.
Os métodos, por sua vez, correspondem a funções ou sub-rotinas disponíveis dentro das classes.

Os critérios de nomeação de métodos são não obrigatórios, mas é recomendado que eles sejam seguidos:

Devem ser nomeado como verbo;
Devem seguir o padrão camelCase.

Não existe em Java o conceito de métodos globais, portanto todos os métodos devem ser definidos dentro de uma classe. 

Quando um método não possui um retorno (não retorna nada), utiliza-se a expressão void.

Quando um método possui uma exceção, utiliza-se a expressão throws Exception {}.

## Escopo

O escopo consiste no ambiente onde uma variável vai ser acessada. Para tal, é preciso identificar a localização mais conveniente para a escrita de algoritmos necessária para o programa. Em Java, o escopo de variáveis vai de acordo com o bloco onde elas são declaradas

A variável é criada no primeiro acesso à ela, se tornando inacessível após o interpretador sair do bloco de execução ao qual ela pertence. Portanto, esta variável não pode ser lida ou manipulada por rotinas e códigos que estão fora do seu bloco de variação, ou seja, fora do escopo da variável.

Em uma classe, podemos visualizar a diferença de escopos. Os atributos (variáveis) são declarados no corpo principal da Classe, sendo portanto acessíveis por todos os métodos.

Ao declarar uma variável DENTRO DE UM MÉTODO, o escopo dessa variável está limitado apenas ao escopo desse método.

## Palavras reservadas

Palavras reservadas são identificadores de uma linguagem que já possuem uma finalidade específica, portanto não podem ser utilizados para nomear variáveis, classes, métodos ou atributos. 

A linguagem Java possui 52 palavras reservadas. Todas elas são classificadas em grupos e escritas com letra minúscula, sendo identificadas com uma cor especial pela maioria das IDEs.

### Controle de pacotes
</br>import: importa pacotes ou classes para dento do código
</br>package: especifica a que pacote todas as classes de um arquivo pertencem

### Modificadores de acesso
</br>public: acesso de qualquer classe
</br>private: acesso apenas dentro da classe
</br>protected: acesso por classe no mesmo pacote e subclasses

### Modificadores de classes, variáveis ou métodos
</br>abstract: classe que não pode ser instanciada ou método que precisa ser implementando por uma subclasse não abstrata
</br>class: especifica uma classe
</br>extends: indica a superclasse que uma subclasse está inserida
</br>final: impossibilita que uma classe seja estendida, que um método seja sobrescreito ou que uma variável seja reiniciada
</br>implements: indica as interfaces que uma classe irá implementar
</br>interface: especifica uma interface
</br>native: indica que o método está escrito em uma linguagem dependente de plataforma, como o C
</br>new: instancia um novo objeto, chamando seu construtor
</br>static: faz um método ou variável pertencer à classe ao invés de às instâncias
</br>strictfp: usado em frente a um método ou classe para indicar que os números de ponto flutuante seguirão as regras de ponto flutuante em todas as expressões
</br>synchronized: indica que um método só pode ser acessado por uma thread de cada vez
</br>transient: impede a serialização de campos
</br>volatile: indica que uma variável pode ser alterada durante o uso de threads

### Controle de fluxo dentro de um bloco de código
</br>break: sai do bloco de código em que ele está
</br>case: executa um bloco de código dependendo do teste do switch
</br>continue: pula a execução do código que viria após essa linha e vai para a próxima passagem do loop

### Palavras "opostas"
</br>package <> import
</br>extends <> implements
</br>final <> abstract
</br>throws <> throw

## Java Doc

Java Documentation é composto por tags que representam dados relevantes para a compreensão da proposta de uma classe e os conjuntos de seus métodos e atributos.

</br>@autor: autor/criador
</br>@version: versão do recurso disponibilizado
</br>@since: data de início da disponibilização do recurso
</br>@param: descrição dos parâmetros dos métodos criados
</br>@return: definição do tipo de retorno de um método
</br>@throws: se o método tem alguma excessão

</br>Comentários em uma única linha: //
</br>Comentários em mais de uma linha: /*
</br>*
</br>*
</br>*
</br>*/

## Terminal e Argumentos

Nem sempre executamos nosso programa Java pela IDE. Com a JVM devidamente configurada, é possível criar um executável do programa e disponibilizar o instalador para qualquer sistema operacional. Observe que num projeto criado na IDE, há uma pasta chamada bin. É nesta pasta que ficarão os arquivos .class, o nosso bytecode.

Mesmo usando uma IDE, é sempre importante identificar onde estão as classes do projeto.

</br>1. Abra o MS-DOS ou Power Shell;
</br>2. Localize o diretório do projeto;
</br>3. Acesse a pasta bin: cd bin
</br>4. Digite o comando: java MinhaClasse (nome da classe sem a extensão .class)

### Argumentos

Quando executamos uma classe que contém o método main, o mesmo permite que passemos um array [] de argumentos do tipo String. Logo podemos, após a definição da classe a ser executada, informar estes parâmetros. Exemplo:

</br> java MinhaClasse argumentoUm argumentoDois

### Scanner

Para receber dados digitados pelo usuário no sistema, tudo precisa estar em uma só linha e em suas respectivas posições. Esta abordagem pode deixar margens de execução com erro. Para isso, com a finalidade de deixar as entradas de dados mais seguras, vamos receber estes dados via Scanner. A classe Scanner permite que o usuário tenha uma interação mais assertiva com o programa.

## Operadores Relacionais

Os operadores relacionais são símbolos capazes de realizar comparações entre determinados operandos e, em seguida, retornar um resultado. 
</br>É possível comparar int e float pois ambos são tipos de dados numéricos.
</br>Não é possível comparar strings ou booleanos pelo tamanho.
</br>Não é possível comparar tipos de dados diferentes caso não sejam ambos numéricos (ex. string e char).

## Operadores Lógicos

Os operadores lógicos são símbolos capazes de realizar comparações lógicas entre entre operandos lógicos ou expressões e, em seguida, retornar um resultado.
</br>Conjunção: operação lógica que só é verdadeira quando ambos os operandos ou expressões envolvidas são verdadeiros;
</br>Disjunção: operação que só é falsa quando ambos os operandos ou expressões envolvidas são falsos;
</br>Disjunção exclusiva: operação que só é verdade quando ambos os operandos ou expressões são opostos (simbologia: ^);
</br>Negação: operação que inverte o valor lógico de um operando ou expressão.

## Controle de fluxo

Os operadores de controle de fluxo são estruturas que têm a capacidade de direcionar o fluxo de execução do código. O switch trata os casos de uma única entrada, enquanto o if não restringe quantas entradas serão avaliadas. O if pode avaliar apenas valores booleanos, não suportando expressões aritméticas.

## Blocos

Um bloco é um grupo de 0 ou mais códigos que trabalham em conjunto para executar uma operação.

</br>Locais: dentro de métodos
</br>Estáticos: dentro de classes
</br>Instância: dentro de classes

## Estruturas de Repetição

O real poder dos computadores está na sua habilidade para repetir uma operação ou uma série de operações várias vezes. Cada repetição é chamada de laço (loop). Uma estrutura de repetição permite que uma sequência de comandos seja executada repetidamente caso determinadas condições sejam satisfeitas. Essas condições são representadas por expressões lógicas.

</br>While: repetição com teste no início
</br>Do-while: repetição com teste no final
</br>For: repetição contada

O comando break é utilizado para terminar de forma abrupta uma repetição. Quando o comando continue é utilizado, os comandos restantes da repetição são ignorados e o programa volta a testar novamente.

### Operadores de incremento e decremento

Para somar um ao valor da variável, retornando o valor original, utiliza-se o atalho numero++.

</br>Forma original:
</br>(retorne numero)
</br>numero = numero + 1

Para subtrair um ao valor da variável, retornando o valor original, utiliza-se o atalho numero--.

</br>Forma original:
</br>(retorne numero)
</br>numero = numero - 1

### Operações aritméticas

</br>Para somar k unidades ao valor da variável, utiliza-se o atalho numero += k.
</br>Para subtrair k unidades ao valor da variável, utiliza-se o atalho numero -=k.
</br>Para multiplicar o valor da variável por k, utiliza-se o atalho numero *= k.
</br>Para dividir o valor da variável por k, utiliza-se o atalho numero /= k.

## Arrays

Array é um objeto utilizado para armazenar sequencialmente dados do mesmo tipo. Os arrays permanecem com o mesmo tamanho depois de criados. As posições em uma array sempre começam no 0.

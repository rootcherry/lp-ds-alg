---
# home: true
# heroImage: https://v1.vuepress.vuejs.org/hero.png
# tagline: Algoritmo e Lógica de Programação
# actionText: Quick Start →
# actionLink: /guide/
# features:
# - title: Feature 1 Title
#   details: Feature 1 Description
# - title: Feature 2 Title
#   details: Feature 2 Description
# - title: Feature 3 Title
#   details: Feature 3 Description
# footer: Made by Chris with ❤️
---

<!-- # Algoritmos - Lógica de Programação -->

## Conteúdo

1. [Introdução](#introducao)
1. [Necessidade do uso da Lógica](#necessidade-do-uso-da-logica)
1. [Aplicabilidade da Lógica no Desenvolvimento](#aplicabilidade-da-logica-no-desenvolvimento)
1. [Nomenclaturas](#nomenclaturas)
1. [Formas de Representação Gráfica](#formas-de-representacao-grafica)
1. [Simbologias Básicas](#simbologias-basicas)
1. [Programação Sequencial](#programacao-sequencial)
1. [Tomada de Decisão (Condição)](#tomada-de-decisao-condicao)
1. [Operadores Relacionais](#operadores-relacionais)
1. [Tomada de Decisão Simples](#tomada-de-decisao-simples)
1. [Tomada de Decisão Composta](#tomada-de-decisao-composta)
1. [Tomada de Decisão por Seleção](#tomada-de-decisao-por-selecao)
1. [Operadores Lógicos](#operadores-logicos)
1. [Operador Lógico E (Conjunção)](#operador-logico-e-conjuncao)
1. [Operador Lógico OU (Dinjunção Inclusiva)](#operador-logico-ou-disjuncao-inclusiva)
1. [Operador Lógico XOU (Dinjunção Exclusiva)](#operador-logico-xou-dinjuncao-exclusiva)
1. [Operador Lógico NAO (Negação)](#operador-logico-nao-negacao)
1. [Tomada de Decisão Operador Lógico de Negação (NÃO)](#tomada-de-decisao-operador-logico-de-negacao-nao)
1. [Laços](#lacos)
1. [Laço Pré-Teste com fluxo verdadeiro (Iterativo)](#laco-pre-teste-com-fluxo-verdadeiro-iterativo)
1. [Laço Pré-Teste com fluxo falso (Iterativo)](#laco-pre-teste-com-fluxo-falso-iterativo)
1. [Laço Pós-Teste com fluxo falso (Iterativo)](#laco-pos-teste-com-fluxo-falso-iterativo)
1. [Laço Pós-Teste com fluxo verdadeiro (Iterativo)](#laco-pos-teste-com-fluxo-verdadeiro-iterativo)
1. [Laço Seletivo (Iterativo)](#laco-seletivo-iterativo)
1. [Laço Puramente Iterativo](#laco-puramente-iterativo)

<a id="alg-intro"></a>

## [Introdução](#alg-intro)

Pode-se dizer que lógica é a ciência que estuda as leis e critérios de validade que regem o pensamento e a demonstração, ou seja, ciência dos princípios formais do raciocínio.

<a id="alg-necessidade"></a>

## [Necessidade do uso da Lógica](#alg-necessidade)

No dia-a-dia dentro das organizações os profissionais da área de Tecnologia buscam solucionar problemas e atingir os objetivos apresentados por seus usuários com eficiência e eficácia, utilizando recursos computacionais e automatizados. O objetivo deste trabalho é mostrar como desenvolver e aperfeiçoar melhor essa técnica, persistindo e praticando constantemente.

<a id="alg-aplicabilidade"></a>

## [Aplicabilidade da Lógica no Desenvolvimento](#alg-aplicabilidade)

Muitos programadores preferem preparar um programa iniciando com um diagrama de blocos para demonstrar sua linha de raciocínio lógico. Esse diagrama, também denominado por alguns de fluxograma, estabelece a seqüência de operações a se efetuar em um programa.

Essa técnica permite uma posterior codificação em qualquer linguagem de programação de computadores,
pois na elaboração do diagrama de blocos não se atinge um detalhamento de instruções ou comando
específicos, os quais caracterizam uma linguagem.

A técnica mais importante no projeto da lógica de programas é chamada programação estruturada, a qual
consiste em uma metodologia de projeto, objetivando:
  - agilizar a codificação da escrita de programas;
  - facilitar a depuração da sua leitura;
  - permitir a verificação de possíveis falhas apresentadas pelos programas;
  - facilitar as alterações e atualizações dos programas.

E deve ser composta por quatro passos fundamentais:

  - Escrever as instruções em seqüências ligadas entre si apenas por estruturas seqüenciais, repetitivas ou de        selecionamento.
  - Escrever instruções em grupos pequenos e combiná-las.
  - Distribuir módulos do programa entre os diferentes programadores que trabalharão sob a
  supervisão de um programador sênior, ou chefe de programação.
  - Revisar o trabalho executado em reuniões regulares e previamente programadas, em que
  compareçam programadores de um mesmo nível.

<a id="alg-nomenclaturas"></a>

## [Nomenclaturas](#alg-nomenclaturas)

**Fluxograma**: é uma ferramenta que tem como finalidade descrever o fluxo, seja manual ou mecânico, especificando os suportes usados para os dados e as informações. Utiliza símbolos convencionais representado por desenhos geométricos básicos, os quais indicarão os símbolos de entrada de dados, do processamento de dados e da saída de dados, pelo analista de sistemas e a serem realizados pelo programador por meio do desenvolvimento do raciocínio lógico, o qual deverá solucionar o problema do programa a ser processado pelo computador.

**Diagrama de Bloco**: é uma ferramenta que tem como objetivo descrever o método e a seqüência do processo dos planos num computador. Utiliza diversos símbolos geométricos, os quais estabelecerão as seqüências de operações a serem efetuadas em um processamento computacional. Após a elaboração do diagrama de blocos, será realizada a codificação do programa.

**Algoritmo**: é uma descrição sistemática da resolução de um grupo de problemas semelhantes. São regras formais para obtenção de um resultado ou da solução de um problema, englobando fórmula de expressões aritméticas.

<a id="alg-formas"></a>

## [Formas de Representação Gráfica](#alg-formas)

Representação gráfica é a maneira de representar dados sobre uma superfície plana, por meio de formas geométricas preestabelecidas de modo a visualizar a linha de raciocínio lógico de um programador, quando da representação dos dados e do fluxo de ação de programa de computador. Há um número excessivo de símbolos existentes, e quando combinados entre si, criam-se novos tipos de representações, aumentando o número de símbolos. Encontramos muitos profissionais e organizações criando suas próprias nomenclaturas.

<a id="alg-simbologia"></a>

## [Simbologias Básicas](#alg-simbologias)

### Terminal (Terminator)

<p align="center"><img src="/images/terminal.png" alt="Terminal" width="340"></p>

O símbolo representa a definição de início e fim do fluxo lógico de um programa. Também é utilizado na definição de sub-rotinas de procedimento ou de função.

### Entrada manual (Manual input)

<p align="center"><img src="/images/entrada-manual.png" alt="Entrada manual" width="340"></p>

Representa a entrada manual de dados, normalmente efetuada em um teclado conectado diretamente ao console do computador.

### Processamento (Process)

<p align="center"><img src="/images/processamento.png" alt="Processamento" width="340"></p>

Representa a execução de uma operação ou grupo de operações que estabelecem o resultado de uma operação lógica ou matemática.

### Exibição (Display)

<p align="center"><img src="/images/exibicao.png" alt="Exibição" width="340"></p>

Representa a execução da operação de saída visual de dados em um monitor de vídeo conectado ao console do computador.

### Decisão (Decision)

<p align="center"><img src="/images/decisao.png" alt="Decisão" width="340"></p>

O símbolo representa o uso de desvios condicionais para outros pontos do programa de acordo com situações variáveis.

### Preparação (preparation)

<p align="center"><img src="/images/preparacao.png" alt="Preparação" width="340"></p>

Representa a modificação de instruções ou grupo de instruções existentes em relação à ação de sua atividade subsequencial.

### Processo predefinido (Predefined process)

<p align="center"><img src="/images/processo-predefinido.png" alt="Processo Predefinido" width="340"></p>

Definição de um grupo de operações estabelecidas como uma sub-rotina de processamento anexa ao diagrama de blocos.

### Conector (Connector)

<p align="center"><img src="/images/conector.png" alt="Conector" width="100"></p>

Representa a entrada ou a saída em outra parte do diagrama de blocos. Pode ser usado na definição de quebras de linha e na continuação da execução de decisões.

### Linha (Line)

<p align="center"><img src="/images/linha.png" alt="Linha" width="340"></p>

O símbolo representa a ação de vínculo existente entre os vários símbolos de um diagrama de blocos. Possui a ponta de uma seta indicando a direção do fluxo de ação.

<a id="alg-seq"></a>

## [Programação Sequencial](#alg-seq)

### Etapas de Ação de um Computador

Um computador executa basicamente três ações de trabalho, sendo:

- a entrada de dados;
- o processamento de dados;
- a saída de dados.

A etapa de entrada de dados é a parte em que o computador recebe os dados do mundo externo, podendo armazená-los na memória principal para realizar algum tipo de processamento, ou armazenar na memória secundária para usar futuramente. Essa etapa é realizada de forma bastante variada nas linguagens de programação, pois são muitas as formas de realização de entrada de dados.

A etapa de processamento de dados é quando o computador, por meio de um programa (software) executado em sua memória primária, faz a transformação dos dados inseridos ou previamente armazenados em sua memória secundária, tornando-os elementos que possam ser usados como fontes de informação para o mundo externo. Essa etapa é realizada de forma muito comum nas linguagens de programação, pois, independentemente do tipo de linguagem em uso, sofre muito pouca alteração.

Na etapa de saída de dados o computador envia os dados processados na memória principal ou armazenados na memória secundária para o mundo externo. Os dados processados podem ser usados como fontes de informação, e assim facilitar a vida das pessoas que necessitam tomar decisões e precisam dos computadores como ferramentas desse processo. Essa etapa, assim como a entrada de dados, é realizada de forma bastante variada nas linguagens de programação.

### Tipos de Dados (Primitivos/Básicos)

Os dados são elementos do mundo exterior, que representam dentro de um computador digital as informações manipuladas pelos seres humanos. Os dados a serem utilizados devem primeiramente ser abstraídos para serem então processados. Eles podem ser classificados em três tipos primitivos ou tipos básicos: numéricos(representados por valores numéricos inteiros ou reais), caracteres (representados por valores alfabéticos ou alfanuméricos) e lógicos (valores dos tipos falso e verdadeiro).

### Inteiro

Os dados numéricos positivos e negativos pertencem ao conjunto de números inteiros, excluindo dessa categoria qualquer valor numérico fracionário. O tipo de dado inteiro é utilizado em operações de processamento matemático.

### Real

São reais os dados numéricos positivos e negativos que pertencem ao conjunto de números reais, incluindo nessa categoria todos os valores fracionários e inteiros. O tipo de dado real é utilizado em operações de processamento matemático.

### Caractere

São caracteres delimitados pelos símbolos aspas (" "). Eles são representados por letras (de A até Z), números (de O até 9), símbolos (por exemplo, todos os símbolos imprimíveis existentes num teclado) ou palavras contendo esses símbolos. O tipo de dado caractere é conhecido também como alfanumérico, string (em inglês, cordão, colar), literal ou cadeia.

Os tipos de dados caractere e cadeia são normalmente utilizados em operações de entrada e saída de dados no sentido de apresentar mensagens de orientação para o usuário do programa em execução. O tipo de dado caractere é utilizado quando se faz referência a um único caractere delimitado por aspas, já o tipo de dados cadeia é utilizado quando se faz referência a um conjunto de caracteres delimitados por aspas.

### Lógico

São lógicos os dados com valores binários do tipo sim e não, verdadeiro e falso, 1 e O, V e F, true e falsel entre outros, em que apenas um dos valores pode ser escolhido.

### Variáveis

Variável é tudo que está sujeito a variações, que é incerto, instável ou inconstante.
Todo dado a ser armazenado na memória de um computador deve ser previamente identificado segundo seu tipo, ou seja, primeiramente é necessário saber o tipo do dado para depois fazer seu armazenamento adequado. Após armazenar o dado desejado, ele pode ser utilizado e processado a qualquer momento.

### Constantes

Constante é tudo que é fixo, estável, inalterável, imutável, contínuo, incessante, invariável, de valor fixo e
que é aplicado em diversos pontos de vista. Assim sendo, do ponto de vista computacional constante é uma grandeza numérica fixa utilizada normalmente numa expressão aritmética ou matemática, que define um valor que será inalterado na expressão, independentemente das variáveis envolvidas na operação a ser realizada.

### Operadores Aritméticos

O termo operador é utilizado na área de programação para estabelecer as ferramentas responsáveis por executar algum tipo de ação computacional. Os operadores aritméticos são responsáveis pela execução do processamento matemático, exceto o operador de atribuição, que pode ser usado também em ações de processamento lógico.

Os operadores aritméticos são classificados em duas categorias, sendo binários ou unários. São binários quando utilizados em operações matemáticas de radiciação, exponenciação, divisão, multiplicação, adição e subtração; são unários quando atuam na inversão do estado de um valor numérico, que pode ser passado de positivo para negativo ou vice-versa.


| Operador | Operação     | Descrição                    | Tipo    | Prioridade | Resultado       |
|:--------:|:------------:|------------------------------|:-------:|:----------:|-----------------|
| +        | x+n          | Adição de "x" com "n"        | Binário | 2          | Real            |
| -        | x-n          | Subtração de "n" de "x"      | Binário | 2          | Inteiro ou Real | 
| *        | x*n          | Multiplicação de "x" por "n" | Binário | 3          | Inteiro ou Real | 
| /        | x/n          | Divisão de "x" por "n"       | Binário | 3          | Inteiro ou Real | 

### Instruções e Comandos

Para realizar a programação num computador é necessário passar ordens para que o computador as execute, para executá-las é necessário que o computador as compreenda por meio de uma linguagem de programação. 

Uma instrução a ser executada em um computador pode ter um ou mais comandos. Comando (palavra--chave) é um componente que pertence ao dicionário de uma linguagem de programação. É um conjunto de comandos que utilizados isoladamente ou em conjunto, determinam as instruções a serem dadas por um programa ao computador.

### Exemplo

**Problema**: *Desenvolver um programa de computador que efetue a leitura de dois valores numéricos inteiros. Processe a operação de adição dos dois valores e apresente na sequência a soma obtida com a operação.*

### Entendimento (análise passo a passo do que deve ser feito pelo programa)

1. Ler dois valores desconhecidos, representados pelas variáveis A e B.
2. Efetuar a adição das variáveis A e B, cujo resultado será atribuído à variável X.
3. Apresentar o valor da variável X, que é o resultado da soma realizada .

### Diagramação (confecção do diagrama de bloco de acordo com o entendimento)

Completada a fase de interpretação do problema, sabendo o que é necessário fazer, passa-se para faze de diagramação do algoritmo.

Observe a indicação dos rótulos **início** e **fim** no diagrama de bloco com o uso do símbolo *terminal*, que deve estar sempre presente, indicando o ponto de início e de fim do diagrama. Note também a existência das linhas com setas ligando os símbolos entre si. Isso é necessário, pois desta forma sabe-se a direção que o fluxo de ações de um programa deve seguir. Veja também o uso dos símbolos manual *input* (equivalente ao comando **leia**) com a definição das variáveis de entrada **A** e **B**, process ( equivalente à ação de processamento) com a definição do processamento matemático de adição **X <- A + B** e *display* ( equivalente ao comando **escreva**) com a definição da variável de saída **X**.

<p align="center"><img src="/images/diagrama-de-bloco-do-programa-de-adicao-de-dois-valores-inteiros.png" alt="Diagrama de bloco do programa de adição de dois valores inteiros" width="200"></p>

### Codificação (escrita do programa de forma textual)

Após estabelecer os passos anteriores (entendimento e diagramação), passa-se à fase de codificação do programa, que obedece ao que está definido no diagrama de bloco, pois ele é a representação gráfica (concreta) da linha de raciocínio lógico do programador a ser colocado em um programa que controla as ações de um computador. Nessa etapa do trabalho deve haver a preocupação do programador em definir o tipo de dado de cada variável.

#### Português Estruturado

```
programa SOMA_NUMEROS // nome de identificação do programa

var  
  X, A, B : inteiro   // nome de identificação das variáveis

início                // início do bloco de instruções
  leia A              // ações de entrada
  leia B              // ações de entrada
  X <-- A + B         // processamento
  escreva X           // saída
fim                   // fim do bloco de instruções
```
#### Linguagem C

```c
#include <stdio.h>
int main(void) {
  int A;
  int B;
  int X;
  scanf("%d", &A);
  scanf("%d", &B);
  X = A + B;
  printf("%d", X);
  return 0;
}
```

#### JavaScript

```js
TODO
```

O código escrito entre os comandos **início** e **fim** é apresentado com um deslocamento (indentação) de duas posições à direita.
O uso de *indentação* é um estilo de escrita que deve sempre ser respeitado, pois visa facilitar a leitura do código dos vários blocos de ação que um programa de computador possa ter.

## [Tomada de Decisão (Condição)](#alg-dec)

### Decisões, Condições e Operadores Relacionais

A tomada de decisão realizada pelo computador estabelece uma ação de desvio na operação do fluxo do programa. Desta forma, um determinado trecho do programa pode realizar uma ou outra tarefa de processamento. 

**Condição** pode ser entendida como uma obrigação que se impõe e se aceita, enquanto **decisão** pode ser o ato ou efeito de decidir, ou seja, de optar, de tomar uma decisão.

Do ponto de vista computacional uma condição é uma expressão booleana cujo resultado é um valor lógico *falso* ou *verdadeiro*. Desta forma, uma expressão booleana como condição é conseguida com uma relação lógica entre dois elementos e um operador relacional.

Os elementos relacionados em uma expressão lógica (condição) são representados por relações binárias entre variáveis e constantes. São possíveis as relações de *variáveis versus variáveis* e de *variáveis versus constantes*.

O estabelecimento de uma condição, ou seja, de uma relação lógica entre dois elementos, é feito a partir de operadores relacionais, que se encontram definidos na tabela seguinte.

## [Operadores Relacionais](#alg-op)

#### Tabela de operadores relacionais

| Operador        | Descrição        |
|:---------------:|------------------|
| =               | Igual a          |
| >               | Maior que        |
| <               | Menor que        | 
| >=              | Maior ou igual a | 
| <=              | Menor ou igual a | 
| <>              | Diferente de     | 

## [Tomada de Decisão Simples](#alg-dec-simples)

A tomada de decisão simples (desvio condicional simples) do ponto de vista do diagrama de blocos é representada pelos símbolos decision e connector. A partir do símbolo decision é estabelecido o foco do desvio do fluxo de um programa. Esse desvio é processado apenas para o lado que indicar o resultado da condição como verdadeira, não importando se essa ação estará sinalizada do lado esquerdo ou direito do símbolo decision. Por esta razão é importante sinalizar as duas linhas de fluxo que saem do símbolo decision com os rótulos **S** e **N** indicando, respectivamente, os lados **sim** e **não** da condição estabelecida, deixando bem claro o lado da ação considerada para a condição verdadeira.

A imagem básica de um diagrama de blocos com os rótulos **S** e **N** para a execução de uma tomada de decisão simples com base na **CONDIÇÃO** definida no símbolo *decision*. As linhas de fluxo com as setas indicam a direção do fluxo de processamento de programa.

<p align="center"><img src="/images/estrutura-de-tomada-de-decisao-simples.png" alt="Estrutura de tomada de decisão simples" width="540"></p>

A tomada de decisão simples do ponto de vista da codificação em português estruturado utiliza os comandos **se**, **então** e **fim_se** na construção da instrução **se ... então/fim_se**. Nessa instrução, se a condição ( definida entre os comandos **se** e **então**) for verdadeira, serão executadas todas as instruções subordinadas e definidas dentro do bloco adjacente entre os comandos **se ... então** e **fim_se**. Após a execução ocorre automaticamente a execução das eventuais instruções existentes após o comando **fim_se**.

Se a condição for falsa, serão executadas apenas as eventuais instruções que estiverem após o comando **fim_se**. Observe a estrutura sintática seguinte:

```
se (<condição>) então
  [instruções executadas após condição ser verdadeira]
fim_se
[instruções executadas após condição ser falsa ou após executar instruções da]
[condição verdadeira]
```

### Exemplo

**Problema**: *Elaborar um programa de computador que leia dois valores numéricos reais desconhecidos. Em seguida o programa deve efetuar a adição dos dois valores lidos e apresentar o resultado caso seja maior que 10.*

### Entendimento

1. Definir a entrada de dois valores incógnitos (variáveis A e B).
2. Efetuar a adição dos valores A e B e atribuir o resultado da adição à variável X.
3. Apresentar o resultado da soma armazenada na variável X, caso a variável X tenha seu valor maior que 10.

### Diagramação

<p align="center"><img src="/images/exemplo-da-utilizacao-da-instrucao-se-entao-fim-se.png" alt="Exemplo da utilização da instrução se...então/fim_se" width="540"></p>

### Codificação

#### Português Estruturado

```
programa ADIÇÃO_DE_NÚMEROS_1
var
  A, B, X : real
início
  leia A, B
  X <- A + B
  se (X > 10) então
    escreva X
  fim_se
fim
```

#### Linguagem C

```c
#include <stdio.h>
int main(void) {
  int A, B, X;
  printf("Informe um valor para a variavel A: "); scanf("%d", &A);
  printf("Informe um valor para a variavel B: "); scanf("%d", &B);
  X = A + B;
  if (X > 10)
    printf("\n o valor da variavel X equivale: %d", X);
  return 0;
}
```

#### JavaScript

```js
TODO
```

## [Tomada de Decisão Composta](#alg-dec-composta)

A tomada de decisão composta (desvio condicional composto) do ponto de vista do diagrama de blocos é representada também com os símbolos *decision* e *connector*, como ocorreu com a representação da tomada de decisão simples. A tomada de decisão composta desvia o fluxo de programa tanto para o lado indicado verdadeiro como para o lado indicado falso, não importando se está em uso o lado esquerdo ou direito do diagrama, obrigando a manter a sinalização dos lados com os rótulos **S** e **N** para indicar os lados **sim** e **não** da condição estabelecida.

Um diagrama de blocos com os rótulos **S** e **N** para uma tomada de decisão composta. Note o uso das linhas de fluxo com as setas indicando a direção do fluxo de processamento do programa a partir da **CONDIÇÃO**, a qual pode ter seu resultado lógico falso ou verdadeiro. Se o resultado lógico da condição for verdadeiro, executa-se o grupo de instruções subordinadas à linha de fluxo sinalizada pelo rótulo **S**. Após as instruções subordinadas, o fluxo de programa é direcionado para o símbolo connector. Se o resultado lógico da condição for falso, ocorre a execução do grupo de instruções subordinadas à linha de fluxo sinalizada pelo rótulo **N**. A principal característica de uma tomada de decisão composta é o fato de existir um bloco de operações para cada um dos lados da condição.

Após a tomada de decisão composta sobre a condição, independentemente de o resultado ser falso ou verdadeiro, executam-se as eventuais instruções estabelecidas após o símbolo *connector*. A tomada de decisão composta do ponto de vista da codificação em português estruturado utiliza os comandos **se, então, senão** e **fim_se** na construção da instrução **se...então/senão/fim_se**.

<p align="center"><img src="/images/estrutura-de-tomada-de-decisao-composta.png" alt="Estrutura de tomada de decisão composta" width="540"></p>

Nessa instrução, se a condição (definida entre os comandos **se** e **então**) for verdadeira, são executadas todas as instruções subordinadas do bloco adjacente entre os comandos **se ... então e senão**. Caso seja a condição falsa, são executadas todas as instruções subordinadas do bloco adjacente entre os comandos **senão** e **fim_se**. Após as instruções de um dos blocos adjacentes são executadas as eventuais instruções que existem após o comando **fim_se**. Observe a estrutura sintática seguinte:

```
se (<condição>) então
  [instruções executadas após condição ser verdadeira]
senão
  [instruções executadas após condição ser falsa]
fim_se
[instruções executadas após condição ser falsa ou após ser verdadeira]
```

### Exemplo

**Problema**: *Elaborar um programa de computador que leia dois valores numéricos reais desconhecidos. Em seguida o programa deve efetuar a adição dos dois valores lidos e caso o resultado seja maior ou igual a 10 deve ser somado ao resultado obtido o valor 5, obtendo-se novo resultado. Caso contrário, o valor do resultado inicialmente obtido deve ser subtraído de 7, gerando-se outro resultado. Após a obtenção de um dos novos resultados o novo resultado deve ser apresentado.*

### Entendimento

1. Definir a entrada de dois valores incógnitos (variáveis A e B).
2. Efetuar a adição dos valores A e B e atribuir o resultado da adição à variável X.
3. Verificar se o valor da variável X é maior ou igual a 1 O; caso seja maior ou igual a 1 O, proceder ao cálculo de X+ 5, atribuindo seu resultado à variável R. Se o valor da variável X não for maior ou igual a 10, proceder ao cálculo de X - 7, atribuindo seu resultado à variável R.
4. Apresentar o resultado da variável R.

### Diagramação

<p align="center"><img src="/images/exemplo-da-utilizacao-da-instrucao-se-entao-senao-fim-se.png" alt="Exemplo da utilização da instrução se...então/senão/fim_se" width="540"></p>

### Codificação

#### Português Estruturado

```
programa ADIÇÃO_DE_NÚMEROS_2
var
  A, B, X, R : real
início
  leia A, B
  X <- A + B
  se (X >= 10) então
    R <- X + 5
  senão
    R <- X - 7
  fim_se
  escreva R
fim
```

#### Linguagem C

```c
TODO
```

#### JavaScript

```js
TODO
```

## [Tomada de Decisão por Seleção](#alg-dec-selecao)

A tomada de decisão por seleção é uma alternativa mais rápida ao uso de tomadas de decisão sequenciais ou encadeadas. É útil e pode ser utilizada em situações em que se possui um grande número de verificações lógicas a serem realizadas.

Abaixo, após a verificação de cada condição da estrutura de decisão por seleção ocorre o desvio do fluxo do programa é desviado para um símbolo *connector* existente em toda a estrutura. Assim sendo, se a primeira condição **(CONDIÇÃO 1)** do primeiro símbolo *decision* possuir resultado lógico verdadeiro, são executadas as instruções subordinadas ao bloco adjacente da primeira condição indicada pela linha sinalizada com o rótulo **S**. Após a efetivação das instruções o fluxo do programa é desviado para o símbolo *connector* que dá continuidade a execução.

O mesmo raciocínio aplicado à primeira condição se aplica às demais condições previstas. Se uma das condições gerar resultado lógico falso, o fluxo do programa é desviado pela linha sinalizada pelo rótulo **N**. Se nenhuma das condições for satisfeita, executa-se a última ação antes e em cima do símbolo *connector*.

<p align="center"><img src="/images/estrutura-de-tomada-de-decisao-por-selecao.png" alt="Estrutura de tomada de decisão por seleção" width="540"></p>

A tomada de decisão por seleção do ponto de vista da codificação em português estruturado utiliza os comandos denominados **caso, seja, faça, senão** e **fim_caso** na construção da instrução **caso/seja ... faça/senão/fim_caso**. Essa instrução utiliza uma variável após o comando **caso** que estabelece de forma indireta sua relação lógica. Após o comando **seja** definem-se os valores a serem avaliados e que darão a orientação para executar ações após o comando **faça**. Caso a variável do comando **caso** possua um valor igual a um dos valores das constantes do comando seja, são executadas as ações previstas em cada comando faça. Se o valor da variável do comando caso for diferente dos valores das constantes do comando seja, são executadas as eventuais instruções entre os comandos senão e fim_caso. Após a instrução casolseja ... façalsenãolfim_caso, são executadas as eventuais instruções existentes após o comando fim_caso. Observe a estrutura sintática seguinte:

```
caso <variável>
  seja <opção 1> faça
    [ação para condição 1 verdadeira]
  seja <opção 2> faça
    [ação para condição 2 verdadeira]
  seja <opção 3> faça
    [ação para condição 3 verdadeira]
senão
  [ação para nenhuma condição satisfeita]
fim- caso
```

### Exemplo

**Problema**: *Desenvolver um programa de computador que leia um valor numérico inteiro entre os valores 1 e 12 e apresente por extenso o nome do mês correspondente ao valor entrado. Caso sejam fornecidos valores menores que 1 e maiores que 12, o programa deve apresentar a mensagem "Valor inválido".*

### Entendimento

1. Efetuar a leitura de um valor numérico inteiro (variável MÊS).
2. Se a variável MÊS for igual a 1, apresentar a mensagem "Janeiro".
3. Se a variável MÊS for igual a 2, apresentar a mensagem "Fevereiro".
4. Se a variável MÊS for igual a 3, apresentar a mensagem "Março".
5. Se a variável MÊS for igual a 4, apresentar a mensagem "Abril".
6. Se a variável MÊS for igual a 5, apresentar a mensagem "Maio".
7. Se a variável MÊS for igual a 6, apresentar a mensagem "Junho".
8. Se a variável MÊS for igual a 7, apresentar a mensagem "Julho".
9. Se a variável MÊS for igual a 8, apresentar a mensagem "Agosto".
10. Se a variável MÊS for igual a 9, apresentar a mensagem "Setembro".
11. Se a variável MÊS for igual a 10, apresentar a mensagem "Outubro".
12. Se a variável MÊS for igual a 11, apresentar a mensagem "Novembro".
13. Se a variável MÊS for igual a 12, apresentar a mensagem "Dezembro".
14. Se a variável MÊS for menor que 1 ou maior que 12, apresentar a mensagem "Valor inválido".

### Diagramação

<p align="center"><img src="/images/exemplo-tomada-de-decisao-por-selecao.png" alt="Exemplo da tomada de decisão por seleção" width="440"></p>

### Codificação

#### Português Estruturado

```
programa MES POR EXTENSO
var
  MÊS : inteiro
início
  leia MÊS
  caso MÊS
    seja 1 faça
      escreva "Janeiro"
    seja 2 faça
      escreva "Fevereiro"
    seja 3 faça
      escreva "Março"
    seja 4 faça
      escreva "Abril"
    seja 5 faça
      escreva "Maio"
    seja 6 faça
      escreva "Junho"
    seja 7 faça
      escreva "Julho"
    seja 8 faça
      escreva "Agosto"
    seja 9 faça
      escreva "Setembro"
    seja 10 faça
      escreva "Outubro"
    seja 11 faça
      escreva "Novembro"
    seja 12 faça
      escreva "Dezembro"
  senão
    escreva "Valor inválido"
  fim_caso
fim
```

#### Linguagem C

```c
TODO
```

#### JavaScript

```js
TODO
```

A instrução **caso/seja ... faça/senão/fim_caso** é útil apenas nos casos em que há tomadas de decisão sequenciais ou encadeadas utilizando as ações previstas com o operador relacional "igual a". Outro detalhe importante é que o comando **senão**, na estrutura de tomada de decisão por seleção, é opcional. Ele pode ser omitido quando não se desejar deixar definida uma ação quando as condições gerais não forem satisfeitas.

## [Operadores Lógicos](#alg-op-logicos)

Os operadores lógicos (ou booleanos) mais comuns, do ponto de vista da programação, são quatro: operador lógico **.e.** (operador lógico de conjunção), operador lógico **.ou.** (de disjunção inclusiva), operador lógico **.xou.** (de disjunção exclusiva) e operador lógico **.não.** (de negação). Dos quatro operadores, três trabalham diretamente com mais de uma condição, vinculando-as entre si para que seja tomada uma única decisão, sendo os operadores lógicos **.e., .ou.** e **.xou.**. O operador lógico **.não.** pode ser usado sempre à frente de uma condição no sentido de inverter seu resultado lógico.

## [Operador Lógico E (Conjunção)](#alg-op-e)

Do ponto de vista filosófico, a lógica de conjunção é a relação lógica entre duas ou mais proposições (entende-se, na esfera da programação, o termo proposição como sendo condição) que geram um resultadológico verdadeiro quando todas as proposições forem verdadeiras.

#### Tabela verdade do operador lógico de conjunção

| Condição 1 | Condição 2 | Resultado lógico |
|:----------:|:----------:|:----------------:|
| Verdadeiro | Verdadeiro | Verdadeiro       |
| Verdadeiro | Falso      | Falso            |
| Falso      | Verdadeiro | Falso            |
| Falso      | Falso      | Falso            |

O resultado é verdadeiro quando **todas** as condições forem verdadeiras.

O uso de um operador lógico de conjunção em um diagrama de blocos é demonstrado abaixo, com um exemplo de tomada de decisão simples.

<p align="center"><img src="/images/estrutura-de-tomada-de-decisao-com-operador-de-conjuncao.png" alt="Estrutura de tomada de decisão com operador de conjunção" width="540"></p>

A codificação em português estruturado do operador de conjunção utilizado na figura acima é realizada de acordo com o modelo do seguinte trecho de programa:

#### Português Estruturado

```
se (<condição 1>) .e. (<condição 2>) então
  [ação para condição 1 e condição 2 verdadeiras]
fim- se
```

O código em português estruturado mostra o uso dos sinais de parênteses para indicar cada condição em separado. Note o uso do operador lógico **.e.** entre as condições envolvidas na relação lógica de conjunção.

### Exemplo

**Problema**: *Desenvolver um programa de computador que leia um valor numérico inteiro que esteja na faixa de valores entre 20 e 90. O programa deve apresentar a mensagem "O valor está na faixa permitida", caso o valor informado esteja entre 20 e 90. Se o valor estiver fora da faixa permitida, o programa deve apresentar a mensagem "O valor está fora da faixa permitida".*

### Entendimento

1. Efetuar a leitura de um valor numérico inteiro (variável NÚMERO).
2. Verificar se o valor fornecido é maior ou igual a 20, e se o mesmo valor é menor ou igual a 90. Se esta condição for verdadeira,     apresentar a mensagem "O número está na faixa de 20 a 90"; caso contrário, apresentar a mensagem "O número está fora da faixa de 20 a 90".

### Diagramação

<p align="center"><img src="/images/utilizacao-de-tomada-de-decisao-com-operador-logico-de-conjuncao.png" alt="Utilização de tomada de decisão com operador lógico de conjunção" width="640"></p>

### Codificação

#### Português Estruturado

```
programa TESTA_LÓGICA_E
var
 NÚMERO : inteiro
início
  leia NÚMERO
  se (NÚMERO >= 20) .e. (NÚMERO <= 90) então
    escreva "O número está na faixa de 20 a 90"
  senão
    escreva "O número está fora da faixa de 20 a 90"
  fim_se
fim
```

#### Linguagem C

```c
TODO
```

#### JavaScript

```js
TODO
```

## [Operador Lógico OU (Disjunção Inclusiva)](#alg-dec-ou)

Do ponto de vista filosófico, lógica de disjunção inclusiva é a relação lógica entre duas ou mais proposições de tal modo que seu resultado lógico será verdadeiro quando pelo menos uma das proposições for verdadeira.

#### Tabela verdade do operador lógico de disjunção inclusiva

| Condição 1 | Condição 2 | Resultado lógico |
|:----------:|:----------:|:----------------:|
| Verdadeiro | Verdadeiro | Verdadeiro       |
| Verdadeiro | Falso      | Verdadeiro       |
| Falso      | Verdadeiro | Verdadeiro       |
| Falso      | Falso      | Falso            |

O resultado é verdadeiro quando pelo menos **uma** das condições é verdadeira.

A representação de um operador lógico de disjunção inclusiva em um diagrama de blocos está na figura abaixo, que mostra um exemplo de tomada de decisão simples.

<p align="center"><img src="/images/estrutura-de-tomada-de-decisao-com-operador-de-disjuncao-inclusiva.png" alt="Estrutura de tomada de decisão com operador de disjunção inclusiva" width="540"></p>

A codificação em português estruturado do operador de disjunção inclusiva da Figura 4.15 é realizada de acordo com o modelo do seguinte trecho de programa:

#### Português Estruturado

```
se (<condição 1>) .ou. (<condição 2>) então
  [ação para condição 1 e/ou condição 2 verdadeiras]
fim- se
```

O código em português estruturado usa parênteses para indicar cada condição da decisão em separado. Note o uso do operador lógico **.ou.** entre as condições envolvidas na relação lógica de disjunção inclusiva.

### Exemplo

**Problema**: *Desenvolver um programa que solicite a entrada do sexo de uma pessoa e indique se a informaçãofornecida é ou não válida. Para o sexo MASCULINO informe a entrada da letra Me para o sexo FEMININO da letra F. Se forem fornecidos os valores M e F, o programa deve apresentar uma mensagem avisando que o sexo informado é válido. No entanto, se for fornecido qualquer outro valor, o programa deve informar que o sexo fornecido é inválido.*

### Entendimento

1. Efetuar a entrada do sexo de uma pessoa (variável SEXO).
2. Verificar se o valor fornecido para a variável SEXO é válido, ou seja, se o valor é igual a F ou M. Se o valor for válido, apresentará a mensagem "Sexo válido"; caso contrário, apresentará a mensagem "Sexo inválido".

### Diagramação

<p align="center"><img src="/images/exemplo-de-tomada-de-decisao-com-operador-logico-de-disjuncao-inclusiva.png" alt="Exemplo de tomada de decisão com operador lógico de disjunção inclusiva" width="640"></p>

### Codificação

#### Português Estruturado

```
programa TESTA_LÓGICA_OU
var
  SEXO : caractere
início
  leia SEXO
  se (SEXO = "M") .ou. (SEXO = "F") então
    escreva "Sexo válido"
  senão
   escreva "Sexo inválido"
  fim_se
fim
```

#### Linguagem C

```c
TODO
```

#### JavaScript

```js
TODO
```

## [Operador Lógico XOU (Dinjunção Exclusiva)](#alg-dec-xou)

Do ponto de vista filosófico, a lógica de disjunção exclusiva é a relação que avalia duas ou mais proposições, de tal modo que o resultado lógico será verdadeiro quando uma, e apenas uma, das proposições for verdadeira. Ou ainda, em outras palavras, o resultado lógico será verdadeiro quando as condições avaliadas possuírem valores lógicos diferentes entre si.

#### Tabela verdade do operador lógico de disjunção exclusiva

| Condição 1 | Condição 2 | Resultado lógico |
|:----------:|:----------:|:----------------:|
| Verdadeiro | Verdadeiro | Falso            |
| Verdadeiro | Falso      | Verdadeiro       |
| Falso      | Verdadeiro | Verdadeiro       |
| Falso      | Falso      | Falso            |

O resultado é verdadeiro quando apenas **uma** das condições é verdadeira.

A representação de um operador lógico de disjunção exclusiva em um diagrama de blocos está na figura abaixo com um exemplo de tomada de decisão simples.

<p align="center"><img src="/images/estrutura-de-tomada-de-decisao-com-operador-de-disjuncao-exclusiva.png" alt="Estrutura de tomada de decisão com operador de disjunção exclusiva" width="540"></p>

A codificação em português estruturado do operador de disjunção exclusiva utilizado na figura acima é realizada de acordo com o modelo do seguinte trecho de programa:

#### Português Estruturado

```
se (<condição 1>) .xou. (<condição 2>) então
  [ação para condição 1 verdadei ra e condição 2 falsa ou condição 1 falsa e condição 2 ]
  [verdadeira]
fim- se
```

No código em português estruturado, observe os parênteses para cada condição em separado. Note o uso do operador lógico **.xou.** entre as condições envolvidas na relação lógica de disjunção exclusiva.

### Exemplo

**Problema**: *Desenvolver um programa de computador que efetue a entrada do nome e respectivo sexo de duas pessoas que pretendem formar um par para participar de uma quadrilha em uma festa junina. Os administradores da festa determinaram que somente serão aceitos pares heterogêneos (formados por pessoas de sexos diferentes). Não serão aceitos casais formados por pessoas do mesmo sexo. Para atender, a este requisito, o programa deve, após a entrada do sexo das duas pessoas, verificar se elas formam par e, no caso, deve apresentar uma mensagem informando a possibilidade. Caso contrário, o programa deve indicar a impossibilidade de formação de par.*

### Entendimento

1. Efetuar a entrada do nome (variável N 1) e do sexo (variável S 1) da primeira pessoa.
2. Efetuar a entrada do nome (variável N2) e do sexo (variável S2) da segunda pessoa.
3. Verificar se o sexo da primeira pessoa é exclusivamente igual a um determinado sexo e se o sexo da segunda pessoa é exclusivamente igual ao sexo informado exclusivamente para a primeira pessoa. Se um dos sexos for exclusivamente igual a um dos sexos informados e o outro for diferente, o programa apresenta uma mensagem informando que podem ser formados pares. Caso contrário, o programa apresenta uma mensagem informando que o par não pode ser formado.

### Diagramação

<p align="center"><img src="/images/exemplo-de-tomada-de-decisao-com-operador-logico-de-disjucao-exclusiva.png" alt="Exemplo de tomada de decisão com operador lógico de disjunção exclusiva" width="640"></p>

### Codificação

#### Português Estruturado

```
programa TESTA_LOGICA_XOU
var
  N1, N2 : cadeia
  S1, S2 : caractere
início
  leia N1, S1
  leia N2, S2
  se (S1 = "M") .xou. (S2 = "M") então
    escreva N1, " pode dançar com ", N2
  senão
    escreva N1, " não pode dançar com ", N2
  fim_se
fim
```

#### Linguagem C

```c
TODO
```

#### JavaScript

```js
TODO
```

## [Operador Lógico NAO (Negação)](#alg-dec-nao)

Do ponto de vista filosófico negação é a rejeição ou a contradição do todo ou de parte desse todo. Pode ser a relação entre uma proposição p e sua negação não-p. Se p for verdadeira, não-p é falsa e se p for falsa, não-p é verdadeira.

#### Tabela verdade do operador lógico de negação

| Condição   | Resultado lógico |
|:----------:|:----------------:|
| Verdadeiro | Falso            |
| Falso      | Verdadeiro       |

A representação de um operador lógico de negação em um diagrama de blocos está na figura abaixo com um exemplo de tomada de decisão simples.

<p align="center"><img src="/images/estrutura-de-tomada-de-decisao-com-operador-de-negacao.png" alt="Estrutura de tomada de decisão com operador de negação" width="540"></p>

A codificação em português estruturado do operador de negação da figura abaixo é realizada de acordo com
o modelo do seguinte trecho de programa:

#### Português Estruturado

```
se .não. (<condição>) então
  [ação para condição não verdadeira ]
fim_se
```

O código em português estruturado mostra o operador lógico **.não.** à frente da condição a ser avaliada. Se a condição for verdadeira, o operador **.não.** fará com que a condição seja considerada falsa, e neste caso nenhuma das instruções subordinadas do bloco adjacente entre os comandos **se ... então** e **fim_se** será executada. No entanto, se a condição for falsa, o operador **.não.** fará com que a condição seja considerada verdadeira, e neste caso serão executadas as instruções subordinadas do bloco adjacente dos comandos **se ... então** e **fim_se**.

### Exemplo

**Problema**: *Elaborar um programa de computador que leia três valores numéricos inteiros, sendo dois representados pelas variáveis A e B e que serão utilizados para a elaboração de um de dois cálculos programados: A + B e A - B. O terceiro, representado pela variável X, será um valor chave de seleção da operação a ser efetuada. Se o valor da variável X não for maior que 5, será realizada a operação C <- A + B; caso contrário, deve ser realizada a operação C <- A - B. Ao final o programa deve apresentar o resultado armazenado na variável C.*

### Entendimento

1. Efetuar a entrada, respectivamente, dos valores das variáveis A, B e X.
2. Verificar se o valor fornecido para a variável X realmente não é maior que 5. Sendo esta condição verdadeira, processar a operação C <- A + B; caso contrário, deve ser realizada a operação C <- A - B.
3. Apresentar o resultado obtido na variável C.

### Diagramação

<p align="center"><img src="/images/exemplo-de-tomada-de-decisao-com-operador-logico-de-negacao.png" alt="Exemplo de tomada de decisão com operador lógico de negação" width="540"></p>

### Codificação

#### Português Estruturado

```
programa TESTA_LÓGICA_NÃO
var
  A, B, C, X : inteiro
início
  leia A, B, X
  se .não. (X > 5) então
    C <- A + B
  senão
    C <- A - B
  fim_se
  escreva C
fim
```

#### Linguagem C

```c
TODO
```

#### JavaScript

```js
TODO
```

## [Tomada de Decisão Operador Lógico de Negação (NÃO)](#alg-op-nao)

A finalidade de **.NÃO.** é negar uma condição

```
=   A = 5   .NÃO. (A = 5)   ->    (A <> 5)

>   A > 5   .NÃO. (A > 5)   ->    (A <= 5)

<   A < 5   .NÃO. (A < 5)   ->    (A >= 5)

Os operadores abaixo são desnecessários no contexto de lógica

>= // inverso de menor que <

<= // inverso de maior que >

<> // inverso de igual =
```

## [Laços](#alg-lacos)

A técnica denominada *laços* é uma estrutura de programação que facilita repetir determinados trechos de código. Reduz o trabalho de programação, principalmente quando é preciso repetir várias vezes alguma ação do programa.

Os laços podem ser classificados em duas formas, sendo *interativos* e *iterativos*. São *interativos* quando não se sabe ao certo quantas vezes o laço será executado, e são *iterativos* quando se conhece o número de vezes que o laço será executado.

#### Laço Condicional

|Laços     |Fluxo |Interativo |Operador Relacional|Iterativo |Operador Relacional | Tipo     |
|:---------|:----:|:---------:|:-----------------:|:--------:|:------------------:|:--------:|
|*enquanto |.V.   | X         |=                  |X         |<=                  |pré-teste |
|até_seja  |.F.   | X         |<>                 |X         |>                   |pré-teste |
|execute   |.V.   | X         |=                  |X         |<=                  |pós-teste |
|*repita   |.F.   | X         |<>                 |X         |>                   |pós-teste |
|laço      |.V.   | X         |<>                 |X         |>                   |seletivo  |

#### Laço Incondicional

|Laços     |Fluxo |Interativo |Operador Relacional|Iterativo |Operador Relacional |
|:---------|:----:|:---------:|:-----------------:|:--------:|:------------------:|
|*para     |-     |-          |-                  |X         |                    |

Laços **mais utilizados** '*'

## [Laço Pré-Teste com fluxo verdadeiro (Iterativo)](#alg-lac-pre-vit)

O laço com controle condicional pré-teste de fluxo verdadeiro executa as instruções subordinadas de um bloco adjacente no período em que o resultado lógico da condição permanece verdadeiro. No momento em que o resultado lógico da condição se tornar falso, a execução do laço é automaticamente encerrada.

Um diagrama de blocos com os rótulos **S** e **N** para a execução de um laço com controle condicional pré-teste verdadeiro, com base na **CONDIÇÃO** do símbolo *decision*. Note uma linha de fluxo que pende do símbolo *decision* com uma seta apontando para baixo, sinalizada com o rótulo *S*, e uma segunda linha de fluxo saindo do símbolo *decision* e sinalizada com o rótulo *N*, indicando a saída do laço quando a condição se tornar falsa. Além dessas duas linhas de fluxo, há também uma terceira que mostra uma ação de retorno para o próprio símbolo *decision*, indicando a ação real do laço.

<p align="center"><img src="/images/estrutura-de-laco-com-controle-condicional-pre-teste-verdadeiro.png" alt="Estrutura de laço com controle condicional pré teste verdadeiro" width="540"></p>

O laço com controle condicional pré-teste verdadeiro, do ponto de vista da codificação em português
estruturado, utiliza os comandos **enquanto**, **faça** e **fim_enquanto** para realizar a construção da instrução **enquanto ... faça/fim_enquanto**.

#### Português Estruturado

```
enquanto (<condição>) faça
  [instruções executadas durante o período em que a condição é verdadeira]
fim_enquanto
```

### Exemplo

**Problema**: *Elaborar um programa que apresente valores de 1 até 5 de 1 em 1*

### Entendimento

1. Criar uma variável de controle para servir como contador com valor inicial 1 (variável I).
2. Enquanto o valor da variável contador for menor ou igual a 5, executar os passos 3, 4 e 5; caso contrário, desviar a execução do programa para o passo 6.
3. Escreva o valor da variável I.
4. Acrescentar o valor 1 ao valor existente da variável I, definida no passo 1.
5. Retornar a execução do programa ao passo 2.
6. Encerrar a execução do programa.

### Diagramação

<p align="center"><img src="/images/exemplo-de-laco-pre-teste-com-fluxo-verdadeiro-iterativo.png" alt="Exemplo de laço pŕe-teste com fluxo verdadeiro iterativo" width="540"></p>

### Codificação

#### Português Estruturado

```
programa LAÇO_PRÉ_TESTE_VERDADEIRO_ITERATIVO
var
  I : inteiro
início
  I <- 1
  enquanto (I <= 5) faça
    escreva I
    I <- I + 1
  fim_enquanto
fim
```

#### Linguagem C

```c
TODO
```

#### JavaScript

```js
TODO
```

## [Laço Pré-Teste com fluxo falso (Iterativo)](#alg-lac-pre-fit)

O laço com controle condicional pré-teste de fluxo falso executa as instruções subordinadas de um bloco adjacente no período em que o resultado lógico da condição permanece falso. No momento em que o resultado lógico da condição se tornar verdadeiro, a execução do laço é automaticamente encerrada.

Um diagrama de blocos com os rótulos **N** e **S** para a execução de um laço com controle condicional pré-teste falso com base na **CONDIÇÃO** do símbolo *decision*. Note uma linha de fluxo pendendo do símbolo *decision* com uma seta apontando para baixo, sinalizada com o rótulo **N**, e uma segunda linha de fluxo saindo do símbolo *decision* e sinalizada com o rótulo **S**, indicando a saída do laço quando a condição se tornar verdadeira. Além dessas duas linhas de fluxo, há também uma terceira que mostra uma ação de retorno para o próprio símbolo *decision*, indicando a ação real do laço.

<p align="center"><img src="/images/estrutura-de-laco-com-controle-condicional-pre-teste-falso.png" alt="Estrutura de laço com controle condicional pré teste falso" width="540"></p>

O laço com controle condicional pré-teste falso, do ponto de vista da codificação em português estruturado, utiliza os comandos **até_seja**, **efetue** e **fim_até_seja** na construção de sua instrução. Neste trecho são executadas as instruções subordinadas ao bloco adjacente (entre os comandos **até_seja ... efetue** e **fim_até_seja**) no período em que o resultado lógico da condição permanecer falso entre os comandos **até_seja** e **efetue**. No momento em que o resultado lógico for verdadeiro, serão executadas as eventuais instruções que estiverem após o comando **fim_até_seja**. Observe a estrutura sintática seguinte:

#### Português Estruturado

```
até_seja (<condição>) efetue 
  [instruções e xecutadas durante o período em qu e a condição é falsa]
fim_até_seja
```

### Exemplo

**Problema**: *Elaborar um programa que apresente valores de 1 até 5 de 1 em 1*

### Entendimento

1. Criar uma variável de controle para servir como contador com valor inicial 1 (variável I).
2. Enquanto a condição (X > 5) for falsa, executar os passos 3, 4 e 5; caso contrário se a condição (X > 5) for verdadeira, desviar a execução do programa para o passo 6.
3. Escreva o valor da variável I.
4. Acrescentar o valor 1 ao valor existente da variável I, definida no passo 1.
5. Retornar a execução do programa ao passo 2.
6. Encerrar a execução do programa.

### Diagramação

<p align="center"><img src="/images/exemplo-de-laco-pre-teste-com-fluxo-falso-iterativo.png" alt="Exemplo de laço pŕe-teste com fluxo falso iterativo" width="540"></p>

### Codificação

#### Português Estruturado

```
programa LAÇO_PRÉ_TESTE_FALSO_ITERATIVO
var
  I : inteiro
início
  I <- 1
  até_seja (I > 5) efetue
    escreva I
    I <- I + 1
  fim_até_seja
fim
```

#### Linguagem C

```c
TODO
```

#### JavaScript

```js
TODO
```

## [Laço Pós-Teste com fluxo falso (Iterativo)](#alg-lac-pos-fit)

O laço condicional com verificação pós-teste tem por finalidade executar pelo menos uma vez as instruções subordinadas de um bloco adjacente, verificando a validade do resultado lógico da condição após a execução. Se o resultado lógico da condição não for válido, o bloco adjacente de instruções subordinadas é repetido.

Um diagrama de blocos com o rótulo N para a execução de um laço com controle condicional pósteste falso, com base na CONDIÇÃO do símbolo decision. A linha de fluxo do rótulo N indica o retorno para um determinado trecho, configurando assim a execução do laço. Já o rótulo S indica a saída do laço.

<p align="center"><img src="/images/estrutura-de-laco-com-controle-condicional-pos-teste-falso.png" alt="Estrutura de laço com controle condicional pós teste falso" width="440"></p>

O laço com controle condicional pós-teste falso, do ponto de vista da codificação em português estruturado, utiliza os comandos **repita** e **até_que** na construção da instrução **repita/até_que**. Nesse trecho são executadas as instruções subordinadas no bloco adjacente (entre os comandos **repita e até_que**) durante o período em que o resultado lógico da condição permanecer falso. No momento em que o resultado lógico for verdadeiro, executam-se as eventuais instruções que estiverem após o comando **até_que**. Observe a estrutura sintática seguinte:

#### Português Estruturado

```
repita
  [instruções executadas durante o período em que a condição é falsa]
até_que (<condição>)
```

### Exemplo

**Problema**: *Elaborar um programa que apresente valores de 1 até 5 de 1 em 1*

### Entendimento

1. Criar uma variável de controle para servir como contador com valor inicial 1 (variável I).
2. Escreva o valor da variável I
3. Acrescentar o valor 1 ao valor existente da variável I, definida no passo 1.
4. Enquanto a condição (X > 5) for falsa, executar os passos 2, 3 e 5; caso contrário se a condição (X > 5) for verdadeira, desviar a execução do programa para o passo 6.
5. Retornar a execução do programa ao passo 2.
6. Encerrar a execução do programa.

### Diagramação

<p align="center"><img src="/images/exemplo-de-laco-pos-teste-com-fluxo-falso-iterativo.png" alt="Exemplo de laço pós-teste com fluxo falso iterativo" width="440"></p>

### Codificação

#### Português Estruturado

```
programa LAÇO_PÓS_TESTE_FALSO_ITERATIVO
var
  I : inteiro
início
  I <- 1
  repita
    escreva I
    I <- I + 1
  até_que (I > 5)
fim
```

#### Linguagem C

```c
TODO
```

#### JavaScript

```js
TODO
```

## [Laço Pós-Teste com fluxo verdadeiro (Iterativo)](#alg-lac-pos-vit)

O laço com controle condicional pós-teste com fluxo verdadeiro executa no mínimo uma vez as instruções subordinadas de um bloco adjacente e mantém a execução no período em que o resultado lógico da condição permanece verdadeiro. No momento em que o resultado lógico da condição se tornar falso, o laço é automaticamente encerrado.

Um diagrama de blocos com o rótulo **S** para a execução de um laço com controle condicional pós-teste verdadeiro com base na **CONDIÇÃO** do símbolo decision. A linha de fluxo do rótulo **S** indica o retorno para um determinado trecho, configurando assim o laço. Já o rótulo **N** indica a saída do laço.

<p align="center"><img src="/images/estrutura-de-laco-com-controle-condicional-pos-teste-verdadeiro.png" alt="Estrutura de laço com controle condicional pós teste verdadeiro" width="440"></p>

O laço com controle condicional pós-teste verdadeiro, do ponto de vista da codificação em português estruturado, utiliza os comandos **execute** e **enquanto_for** na construção da instrução **execute/enquanto_for**. Nesse trecho de instrução são executadas as instruções subordinadas ao bloco adjacente (entre os comandos **execute** e **enquanto_for**) durante o período em que o resultado lógico da condição permanecer verdadeiro. No momento em que o resultado lógico for falso, serão executadas as eventuais instruções que estiverem após o comando **enquanto_for**. Observe a estrutura sintática seguinte:

#### Português Estruturado

```
execute
  [instruções executadas durante o período em que a condição é verdadeira]
enquanto_for (<condição>)
```

### Exemplo

**Problema**: *Elaborar um programa que apresente valores de 1 até 5 de 1 em 1*

### Entendimento

1. Criar uma variável de controle para servir como contador com valor inicial 1 (variável I).
2. Escreva o valor da variável I
3. Acrescentar o valor 1 ao valor existente da variável I, definida no passo 1.
4. Enquanto a condição (I <= 5) for verdadeira, executar os passos 2, 3 e 5; caso contrário se a condição (I <= 5) for falsa, desviar a execução do programa para o passo 6.
5. Retornar a execução do programa ao passo 2.
6. Encerrar a execução do programa.

### Diagramação

<p align="center"><img src="/images/exemplo-do-laco-continua-enquanto-for-iterativa.png" alt="Exemplo do laço continua/enquanto_for iterativa" width="440"></p>

### Codificação

#### Português Estruturado

```
programa LAÇO_PÓS_TESTE_VERDADEIRO_ITERATIVO
var
  I : inteiro
início
  I <- 1
  execute
    escreva I
    I <- I + 1
  enquanto_for (I <= 5)
fim
```

#### Linguagem C

```c
TODO
```

#### JavaScript

```js
TODO
```

## [Laço Seletivo (Iterativo)](#alg-lac-seletivo)

O laço condicional seletivo permite selecionar o local onde a decisão de saída do laço será incrementada, podendo colocá-la, por exemplo, no início, simulando uma ação condicional pré-teste; no final, simulando uma ação condicional pós-teste; ou pode-se colocar no meio dele, que é a forma mais comumente usada.

Um diagrama de blocos com o laço condicional seletivo. O símbolo decision é posicionado no meio do diagrama, mas poderia estar em qualquer outro lugar. Devido à característica de poder escolher o local onde a decisão será colocada, esse tipo de laço condicional é seletivo. Os rótulos **S** e **N** para a verificação condicional do laço de acordo com a **CONDIÇÃO** do símbolo decision. A linha de fluxo sinalizada com o rótulo **S** faz o desvio do fluxo de programa para fora do laço quando o resultado lógico da condição é verdadeiro. No caso de o resultado lógico da condição ser falso, o laço permanece em execução.

<p align="center"><img src="/images/estrutura-de-laco-com-controle-condicional-seletivo.png" alt="Estrutura de laço com controle condicional seletivo" width="440"></p>

O laço com controle condicional seletivo, do ponto de vista da codificação em português estruturado, utiliza os comandos **laço, saia_caso** e **fim_laço** na construção da instrução **laço/saia_caso/fim_laço**, que executa o trecho de instruções subordinadas do bloco adjacente entre os comandos **laço** e **fim_laço** até o momento em que o resultado lógico da condição representada pela instrução do comando **saia_caso** torna-se verdadeiro. Nesse ponto o fluxo do programa é desviado para fora do laço. Observe a estrutura sintática seguinte:

#### Português Estruturado

```
laço
  [instruções para ação 1 ]
  saia_caso (<condição>) 
  [instruções para ação 2 ]
fim_laço
```

### Exemplo

**Problema**: *Elaborar um programa que apresente valores de 1 até 5 de 1 em 1*

### Entendimento

1. Criar uma variável de controle para servir como contador com valor inicial 1 (variável I).
2. Escreva o valor da variável I
3. Se a condição (X > 4) for falsa, executar os passos 4 e 5; caso contrário se a condição (X > 4) for verdadeira, desviar a execução do programa para o passo 6.
4. Acrescentar o valor 1 ao valor existente da variável I, definida no passo 1.
5. Retornar a execução do programa ao passo 2.
6. Encerrar a execução do programa.

### Diagramação

<p align="center"><img src="/images/exemplo-da-instrucao-laco-saia-caso-fim-laco-iterativa.png" alt="Exemplo da instrução laço/saia_caso/fim_laço iterativa" width="340"></p>

### Codificação

#### Português Estruturado

```
programa LAÇO_SELETIVO
var
  I : inteiro
início
  I <- 1
  laço
    escreva I
    saia_caso (I > 4)
    I <- I + 1
  fim_laço
fim
```

#### Linguagem C

```c
TODO
```

#### JavaScript

```js
TODO
```

## [Laço Puramente Iterativo](#alg-lac-piterativo)

O laço incondicional é representado em um diagrama de blocos. O símbolo especificado para essa representação é o preparation, adotado nesta obra. Observe a indicação, dentro do símbolo preparation, da variável a ser controlada com a atribuição dos valores de início, fim e incremento, separados por vírgula.

<p align="center"><img src="/images/estrutura-de-laco-de-repeticao-com-controle-incondicional.png" alt="Estrutura de laço de repetição com controle incondicional" width="540"></p>

O laço incondicional, do ponto de vista da codificação em português estruturado, utiliza os comandos **para, de, até, passo, faça** e **fim_para** para realizar a construção da instrução **para ... de ... até ... passo ... faça/fim_para**, e a estrutura desse tipo de laço tem o seu funcionamento controlado por uma variável denominada contador. Pode-se executar um determinado conjunto de instruções subordinadas a um bloco adjacente um certo número de vezes. No momento em que o valor da variável de controle atingir o valor definido no segmento de fim de contagem, serão executadas as eventuais instruções que estiverem após o comando **fim_para**. Observe a estrutura sintática seguinte:

#### Português Estruturado

```
para [<variável>] de [<início>] até [<fim>] passo [<incremento>] faça
  [<instruções executadas durante o ciclo de contagem da variável de controle>]
fim_para
```

### Exemplo

**Problema**: *Elaborar um programa que apresente valores de 1 até 5 de 1 em 1*

### Entendimento

1. Definir uma variável do tipo contador (variável I), variando de 1 a 5, de 1 em 1.
2. Acrescentar o valor 1 ao valor existente da variável I, definida no passo 1.
3. Apresentar o valor da variável I
4. Repetir os passo 2 e 3 até o valor da variável chegar a 5.
5. Encerrar a execução do programa.

### Diagramação

<p align="center"><img src="/images/exemplo-de-laco-para-de-ate-passo-faca-fim-para.png" alt="Exemplo de laço para...de...até...passo...faça...fim_para" width="540"></p>

### Codificação

#### Português Estruturado

```
programa LAÇO_INCONDICIONAL
var
  I : inteiro
início
  para I de 1 até 5 passo 1 faça
    escreva I
  fim_para
fim
```

#### Linguagem C

```c
TODO
```

#### JavaScript

```js
TODO
```

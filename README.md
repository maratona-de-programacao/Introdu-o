## **Introdução a Maratona De Programação - UNIOESTE <3**  

Primeiramente os integrantes veteranos do projeto desejam-lhes parabéns por quererem fazer parte deste maravilhoso projeto **:3**.  

Enfim vamos ao que interessa, **CODAR!!**

Antes de sair escrevendo códigos com milhões de linhas como um maniaco. Existem algumas competências básicas necessárias.

### 1. Linguagem utilizada na maratona?  
>**1 - R.:** Normalmente na maratona a linguagem de programação utilizada é "livre"<sup id="n1">[1](#fn1)</sup>(durante o projeto vocês poderão utilizar qualquer linguagem listadas abaixo)<sup id="n2">[2](#fn2)</sup>.
>>**- C**  
>>**- C++**  
>>**- C#**  
>>**- Java**  
>>**- Python**  
>>**- Ruby**  
>>**- Scala**  
>>**- GO**  
>>**- KOTOLIN**  
>>**- JavaScript**  
>>**- Lua**  
>>**- Pascal**  
>>**- Haskell**  
>>**- OCAML**  

>**NOTAS**  
>**<b id="fn1">1</b>-** *Nem todas as linguagens, assim como suas versões são autorizadas na competição da **ICPC*** [↩](#n1)   
>**<b id="fn2">2</b>: -** *Linguagens aceitas pelo* **[URI](https://www.urionlinejudge.com.br)** [↩](#n2)  

### 2. Não sei nem o que é programar o que fazer?

>**2 - R.:** Calma jovem padawan. "Desistir é cedo antes de tentar", como diria o nosso amado e querido Mestre Yoda.  
>E ele está como sempre coberto de razão, além da competição, um dos objetivos deste projeto ensinar pessoas do nosso curso aprenderem a programar. Mas qual linguagem devo aprender?  
>>**R.:** O nosso curso sempre ensina a programar em **C** na matéria de *Algorítimos do 1° ano*. Então nós recomendamos fortemente aprender a programar em **C**.


### 3. Vamos ao que interessa então?

>**3 - R.:** Não... Quero dizer **SIM...**

### 4. Conceitos básicos

>**Para Fins de familiaridade os exemplos de sintaxe(código) utilizados na introdução serão realizados em **C****

### 4.1. Primeiro código

~~~~C
#include <stdio.h>
 
int main() { 
    
    printf("Hello, World!");
    return 0;
}
~~~~

O que são essas linhas malucas ali em cima???
>Welcome to the Family Son! ~~**PUNCH**  

Brincadeiras a parte. Bem vindo ao incrível mundo da programação **S2**, mas **"Vamos por partes" - R. T. Jack**  

Primeiramente vamos analisar cada linha do código acima.
~~~~C
//Na primeira linha temos
#include <stdio.h>
// Nela estamos importando a biblioteca standard(padrão) de Entrada e Saída(Input/Output) do C

//Logo em seguida temos
int main(){
//Nesta linha estamos definindo uma função denominada main(função principal do nosso programa)
//Obs.: Falaremos sobre funções posteriormente

//Dentro da função main temos o seguinte comando
printf("Hello, World!");
//Este comando chama uma função chamada printf() que exibe na tela a mensagem que está entre as aspas, no caso 'Hello, World!'

//Em seguida temos o comando
return 0;
//Este comando é um indicativo de que a função chegou ao seu final(mais a frente falaremos um pouco mais sobre ele).

// E por fim temos
}
//Sim, é de extrema importância que nossas chaves estejam fechadas de maneira adequadas, juntamente com os parentes balanceados e um código bem indentado.
//Na sequencia falaremos sobre isso
~~~~

### 4.2. Indentação & parenteses balanceados

Bom jovem padawan, você deve estar se perguntando sobre a necessidade de eu estar falando sobre isso. Porém na programação é necessário ter alguns cuidados na hora de escrever seus programas, como diria Jack "Vamos por partes".

- **Indentação:** *Para nós da ciencia da computação é um termo aplicado ao código fonte de um programa para ressaltar ou definir a estrutura do algoritmo. Na maioria das linguagens de programação, a indentação é empregada com o objetivo de ressaltar a estrutura do algoritmo, aumentando assim a legibilidade do código.* - Fonte: [Wikipédia](https://pt.wikipedia.org/wiki/Indenta%C3%A7%C3%A3o), **RECOMENDAMOS FORTEMENTE QUE VEJAM O EXEMPLO DA WIKI**, caso não queira ver é basicamente você dar **'tabs'** no código. Criando assim espécie de paragrafos. Estes 'paragrafos' servem pra mostrar o código que está dentro de um **IF** ou um **WHILE/FOR** ou até mesmo dentro de uma **FUNÇÃO**
>De uma olhada no código da parte **4.1**, lá você pode ver a função main e um espaço no inicio de cada linha. Esse espaço é o nosso **"Paragrafo"**

- **Parenteses"()" & Chaves"{}" Balanceados<sup id="n3">[1](#fn3)</sup>:** Este é um conceito mais facil de se explicar e aprender. Em resumo é basicamente você ter o mesmo número **parenteses e chaves** abertas

>**Ex.:**
>Parenteses balanceados**<sup id="n3">[1](#fn3)**: ((((((()))))))  
>Parenteses desbalanceados**¹**: (((((()))))  
>Percebam que no exemplo de parenteses desbalanceados o numero de **"("** é maior que o numero de **")"**  
> O mesmo vale para **chaves "{}"**, porém o uso delas é indicado para delimitar **Funções (*Ver exemplo da sessão 4.1*) e laços de repetição**

>**NOTAS**  
>**<b id="fn3">1</b>-** *"Tava muito broken os dois e veio os programadores e nerfaram eles neste patch"* [↩](#n3)

### 5. Como começar?

Bom Falamos, falamos, jogamos alguns conceitos. **Mas tá, quando iremos começar?**  
Eu juro que no item **6.** já começaremos a botar a mão na massa. Mas antes de sair loucamente **codando**. Antes de mais nada você precisa instalar um **COMPILADOR**. Para tal sugerimos que você instale o programa **[CodeBlocks](http://www.codeblocks.org/), <sup id="n4">[1](#fn4)</sup> (LEIA A NOTA ANTES DE SAIR INSTALANDO)**, este programa é um **Ambiente de Desenvolvimento Inegrado(IDE)**. Nele você encontrará uma interface de desenvolvimento, acompanhada de um compilador da linguagem **C**

<b id="fn4">1</b>: **Baixem o codeblocks-(versão)-setup.exe**, durante a instalação recomendamos que deixe tudo como está, só ir em **Next, ..., Next, install**.Caso alguém use linux é só seguir o tutorial do site **:P** [↩](#n4)

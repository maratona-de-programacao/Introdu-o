## **Introdução a Maratona De Programação - UNIOESTE *<3***  

Primeiramente os integrantes veteranos do projeto desejam-lhes parabéns por querer fazer parte deste maravilhoso projeto.  

Enfim vamos ao que interessa, **CODAR!!**

Antes de sair escrevendo códigos com milhões de linhas como um maniaco. Existem algumas competências básicas necessárias.

### 1. Linguagem utilizada na maratona?  
>**1 - R.:** Normalmente na maratona a linguagem de programação utilizada é "livre¹"(durante o projeto vocês poderão utilizar qualquer linguagem listadas abaixo²).
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
>  
>**¹ -** *Nem todas as linguagens, assim como suas versões são autorizadas na competição da **ICPC***  
>**² -** *Linguagens aceitas pelo* **[URI](https://www.urionlinejudge.com.br)**

### 2. Não sei nem o que é programar o que fazer?

>**2 - R.:** Calma jovem padawan. "Desistir é cedo antes de tentar", como diria o nosso amado e querido Mestre Yoda.  
>E ele está como sempre coberto de razão, além da competição, um dos objetivos deste projeto ensinar pessoas do nosso curso aprenderem a programar. Mas qual linguagem devo aprender?  
>>**R.:** O nosso curso sempre ensina a programar em **C** na matéria de *Algorítimos do 1° ano*. Então nós recomendamos fortemente aprender a programar em **C**.


### 3. Vamos ao que interessa então?

>>**3 - R.:** Não... Quero dizer **SIM...**

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

### 4.2. Indentado, parenteses balanceados e outros detalhes

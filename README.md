# linguagem_markdown
Esse repositório foi criado como teste de aprendizagem dos principais comandos da linguagem de marcação Markdown.

Abaixo seguem alguns comandos de marcação da linguagem markdown.

***
# Escrita - Alguma dicas de escrita e organização do texto.

Na parte de configurações gerais de escrita algumas das principais dicas para organização do texto, são:

#### 1. Como colocar uma palavra ou frase em **Negrito**?

   Para utilizar a função bold ou negrito em markdown, pode-se utilizar dois símbolos de asteriscos ou dois underlines antes e depois da palavra/frase que se deseja ascender, sem espaços entre os simbolos e a frase.
   
   Exemplo: asteriscoasterisoEssa frase está em Negritoasteriscoasterisco
   
   **Essa frase está em Negrito**

#### 2. Como colocar uma palavra ou frase em _Itálico_?

   Para utilizar a função itálico, podemos utilizar um símbolo de asterisco ou um underline antes e outro depois da palavra/frase ou um underline(_).
   
   Exemplo: asteriscoEssa frase está em Itálicoasterisco
   
   *Esta frase está em Itálico*
   
 
#### 3. Como colocar uma palavra ou frase em __*Negrito e Itálico*__ ao mesmo tempo?

   Para utilizar a função negrito e itálico ao mesmo tempo, podemos utilizar dois símbolo de underline e um asterisco antes, abrindo a palavra/frase e o mesmo conjunto de caracteres fechando a palavra.
   
   Exemplo: asteriscoasteriscounderlineEssa frase está em Itálico e Negritounderlineasteriscoasterisco
   
   __*Esta frase está em Itálico e Negrito*__

#### 4. Como ~~riscar~~ uma palavra?

   Para riscar uma palavra ou frase utilizamos o símbolo do Til(~), nesse caso é necessário dois caracteres desse antes e depois da palavra para configurar o efeito riscado.
   
   Exemplo: tiltilEstá frase está riscadatiltil
   
   ~~Esta frase está riscada~~
   
#### 5. Como separar o texto com barras personalizadas?

   Ao ler esse texto você percebeu que as seções estão separadas por uma barra vertical.A criação dessa barra é feita com a utilização sequenciada de três asteriscos.
   
   Exemplo: ***

***
# Títulos - Como criar títulos em Markdonw?
Para criar títulos basta usar o símbolo do asterisco(#) seguido de um espaço e o nome do título desejado, a cada novo level basta acrescentar asteriscos.

Exemplo: Para o título de nível 1, usei **# Título de nivel 1 - Teste**, não esquece do espaço entre o # e a palavra;
# Título de nível 1 - Teste

Exemplo: Para o título de nível 2, usei **## Título de nivel 2 - Teste**;
## Título de nível 2 - Teste

Exemplo: Para o título de nível 3, usei **### Título de nivel 3 - Teste**;
### Título de nível 3 - Teste

***

# Listas - Como criar listas em Markdonw?
Os principais tipos de listas que podemos criar são:

### 1. Listas Numerada: 

   A criação de listas numeradas pode ser feita escrevendo o número seguindo de um ponto final, três espaços, para alinhar a frase ou palavra desejada com o texto superior. 

   Exemplo.: (1. Primeiro objeto da minha lista 1. Segundo objeto da minha lista 1.Terceiro objeto da minha lista )

1. Primeiro objeto da minha lista
1. Segundo objeto da minha lista
1. Segundo objeto da minha lista

   P.S: Independente dos números que eu colocar, a lista será convertida e criada na ordem. Observe que no exemplo todos os meus objetos foram criados como sendo o primeiro, mas na convesão o GitHub mostrará a lista em ordem.

Caso eu deseje adicionar níveis para a minha lista, basta colocar três espaço a frente do item que pertence ao nível mais abaixo.
   
   Exemplo.: (1. Primeiro objeto da minha lista   1. Primeiro, primeiro objeto da minha lista 1.Segundo objeto da minha lista)

1. Primeiro objeto da minha lista (nível 1)
   1. Primeiro, primeiro objeto da minha lista (nível 2 - três espaços na frente)
1. Segundo objeto da minha lista (nível 1)
   1. Primeiro, segundo objeto da minha lista (nível 2 - três espaços na frente)
   2. Segundo, segundo objeto da minha lista (nível 2 - três espaços na frente)
       1. Primeiro, segundo, segundo objeto da minha lista (três espaços na frente - nível 3) 
               
   P.S: Os níveis mais abaixo seguem uma ordem, ou seja, o primeiro nível são números, o segundo nível são convertidos automaticamente para números romanos, o terceiro nível são letras e assim sucessivamente.

### 2. Listas Demarcadas: 

   As listas demarcadas são aquelas listas que possuem umas bolinhas ou marcadores na frente dos itens da lista.

Para fazer listas demarcadas é necessário utilizar o * (asterisco) ou - (tracinho), espaço, e a palavra-item.
  
  Exemplo: (* Item 1* Item 2- Item 3)

* Item 1 (nível 1)
- Item 2 (nível 1)
* Item 3 (nível 1)

Para fazer listas demarcadas com diferentes níveis é necessário utilizar três espaços antes do asterisco, como está descrito abaixo.
  
  Exemplo:(* Item 1* Item 2   * Iten2.1* Item 3   * Item 3.1   * Item 3.2)
   
* Item 1 (nível 1)
* Item 2 (nível 1)
   * Item 2.1 (nível 2)
* Item 3 (nível 1)
   * Item 3.1 (nível 2 - três espaços na frente do asterisco)
       * Item 3.2 (nível 3 - três espaços na frente do asterisco)
       
   P.S: Os níveis mais abaixo seguem uma ordem, ou seja, o primeiro nível bolinhas preenchidas, o segundo nível são bolinhas vazadas e o terceiro nível são quadrados preenchidos e assim sucessivamente.

### 3. Lista de Tarefas:

   A lista de tarefas pode ser utilizada para criação de lista do tipo "TO DO", ou para organizar objetivos que você precisa cumprir. 
Para construir uma **lista de tarefas** é necessário utilizar o sinal de menos (-), seguido de um espaço juntamente do conjunto de colchetes separados por um espaço ([ ]);

   Exemplo:- [ ] Tarefa 1,- [ ] Tarefa 2,   - [ ] Tarefa 2.1

- [ ] Tarefa 1
- [ ] Tarefa 2
   - [x] Tarefa 2.1
 
   P.S: Quando as tarefas ou objetivos forem concluidos, basta voltar no código da lista e preencher o espaço entre os colchetes com um x.Nessa lista não existem mudanças entre os simbolos dos marcadores, como visto nos exemplos anteiores.

   teste1
   
   

       
  


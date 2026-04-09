# Nível: 1: INICIANTE em JS 

> Foco: Variáveis (let, const, var), Tipos Primitivos, Operadores, Condicionais Simples (if/else), Laços (for, while).

### Bloco 1: Variáveis, Tipos e Operadores

    Crie um script que declare as variáveis nome, idade e cidade usando const e imprima uma frase utilizando concatenação de strings (template literal).

    Declare duas variáveis numéricas e imprima o resultado da soma, subtração, multiplicação, divisão e módulo (%) entre elas.

    Utilize o prompt() para pedir a base e a altura de um retângulo e calcule sua área.

    Crie uma variável peso e uma variável altura. Calcule o IMC e imprima o resultado no console.

    Converta a string "150" para um número inteiro e realize uma soma com o número 50.

    Declare uma variável numero e use os operadores de incremento (++) e decremento (--).

    Crie um template literal que inclua uma expressão matemática, por exemplo: A soma de 5 + 3 é ${5 + 3}.

    Peça ao usuário o valor total de uma compra e calcule o valor com 10% de desconto.

    Declare um array com 4 cores diferentes e acesse e imprima a segunda cor.

    Crie um objeto carro com as propriedades marca e ano, e imprima o ano do carro.

### Bloco 2: Condicionais e Controle de Fluxo

    Peça um número e use um if/else para determinar se ele é positivo ou negativo (0 é positivo).

    Use o operador ternário (? :) para verificar se um número é par ou ímpar e imprima a resposta.

    Peça a idade e use um if/else if/else para classificar: "Criança" (0-12), "Adolescente" (13-17), "Adulto" (>=18).

    Peça duas notas. Se a média for maior ou igual a 7, imprima "Aprovado"; caso contrário, "Reprovado".

    Peça um dia da semana (número de 1 a 7) e use um ### Bloco switch para imprimir o nome correspondente.

    Verifique se um usuário pode acessar um site. Ele deve ser maiorDeIdade E ter possuiPermissao (ambas booleanas).

    Verifique se um dia da semana é Sábado OU Domingo para imprimir "Fim de Semana".

    Leia três números e use aninhamento de if/else para determinar qual é o maior.

    Simule o login. Peça username e senha fixas. Imprima "Login Efetuado" se ambos estiverem corretos.

    Peça um número. Use o operador de coalescência nula (??) para definir um valor padrão de 10 caso o usuário não digite nada.

### Bloco 3: Laços e Funções Simples

    Use um laço for para imprimir todos os números de 1 a 10.

    Use um laço while para fazer uma contagem regressiva de 5 a 1.

    Crie uma função chamada saudar que recebe um nome como parâmetro e retorna "Olá, [Nome]!".

    Crie uma função anônima que calcula a área de um círculo (use π≈3.14) e a chame.

    Crie uma arrow function que recebe um número e retorna seu quadrado.

    Itere sobre um array de números usando o método forEach e imprima cada elemento.

    Peça números ao usuário até que ele digite 0. Use um laço do/while para garantir que o ### Bloco rode pelo menos uma vez.

    Crie um laço for para iterar de 1 a 20, mas use continue para pular a impressão dos números múltiplos de 3.

    Crie uma função que receba um array de números e retorne a soma de todos os elementos, usando um laço for.

    Crie um array de 5 strings. Use um laço for...of para imprimi-las em maiúsculas.

# Nível: 2: INTERMEDIÁRIO em JS 

> Foco: Funções Avançadas, High-Order Functions (map, filter, reduce), Manipulação de Arrays/Objetos, Closures.

### Bloco 4: Funções de Ordem Superior e Arrays

    Crie uma função que recebe uma callback function e um nome, e executa a callback passando o nome como argumento.

    Use o método map em um array de números para retornar um novo array com todos os valores multiplicados por 2.

    Use o método filter em um array de idades para retornar apenas as idades maiores que 18.

    Use o método reduce em um array de preços para calcular o valor total da compra.

    Dada uma string com palavras separadas por espaço, use split e join para inverter a ordem das palavras (Ex: "Eu sou JavaScript" → "JavaScript sou Eu").

    Use o método find em um array de objetos produtos para encontrar e retornar o produto com o id: 3.

    Implemente a função que calcula o fatorial de um número usando recursão (função que chama a si mesma).

    Crie uma função que receba uma lista de nomes e use o método sort para ordená-los em ordem alfabética.

    Crie uma função que verifique se uma palavra é um palíndromo (lida igual de trás para frente) ignorando o case.

    Implemente uma função que receba um array de números e retorne um novo array contendo apenas os números que são primos.

### Bloco 5: Manipulação de Objetos e Dados

    Crie um array de 10 números e use um algoritmo manual para encontrar e retornar o maior e o menor valor.

    Crie um objeto aluno com as propriedades nome e notas (array). Use reduce nas notas para calcular e retornar a média do aluno.

    Crie uma função que receba dois arrays e retorne um novo array contendo apenas os elementos que são comuns a ambos (interseção).

    Use a desestruturação de objeto ({}) para extrair as variáveis titulo e autor de um objeto livro.

    Use a desestruturação de array ([]) para trocar os valores de duas variáveis sem usar uma variável temporária.

    Crie uma função que use parâmetros de descanso (...) para somar uma quantidade indefinida de números.

    Crie uma função que receba um objeto e retorne um novo objeto com as chaves e valores invertidos (Ex: {a: 1} \to {1: 'a'}).

    Crie um Closure (função interna que acessa o escopo da função externa) para criar um contador que pode ser incrementado e retornado.

    Dada uma lista de objetos pessoas com a chave cidade, use reduce para retornar um objeto que conta quantas pessoas há em cada cidade (Ex: { 'SP': 2, 'RJ': 1}).

    Implemente uma função de Busca Sequencial em um array de objetos, buscando por um valor específico em uma de suas propriedades.

### Bloco 6: Matrizes, Assincronicidade Básica e ES6+

    Crie uma função que recebe um array de números e retorna um novo array sem números duplicados (use Set).

    Crie uma matriz 3×3 (array de arrays). Itere sobre ela usando laços aninhados e calcule a soma de todos os elementos.

    Crie uma função que simule um atraso usando setTimeout e imprima uma mensagem após 2 segundos.

    Crie uma Promise que resolve com a mensagem "Sucesso!" se um número aleatório for maior que 0.5, e rejeita caso contrário.

    Crie um generator function (function*) que gere a sequência de números ímpares (1, 3, 5, 7...).

    Use o operador spread (...) para concatenar dois arrays e adicionar um novo elemento ao mesmo tempo.

    Crie uma função que recebe um array de objetos e o método de ordenação ('asc' ou 'desc') e ordena os objetos por uma propriedade específica (Ex: nome).

    Crie uma função que recebe um número inteiro e o converte para sua representação em binário (string).

    Implemente o algoritmo para calcular o Máximo Divisor Comum (MDC) entre dois números (pode ser com while ou recursão).

    Crie uma função que recebe um valor de saque e retorna um objeto com a quantidade mínima de notas de 100, 50, 10 e 1, simulando um caixa eletrônico.

# Nível: 3: AVANÇADO em JS 

> Foco: POO (class), Assincronicidade Avançada (async/await), Algoritmos Complexos, Estruturas de Dados Abstratas.

### Bloco 7: Programação Orientada a Objetos (POO)

    Crie uma class Pessoa com um construtor que inicialize nome e idade. Adicione um método apresentar() que imprima os dados.

    Crie uma class ContaBancaria com as propriedades saldo e os métodos depositar, sacar e transferir (para outra instância de ContaBancaria). O saque deve validar o saldo.

    Crie uma subclasse Aluno que extends Pessoa e adicione a propriedade matricula. Sobrescreva o método apresentar().

    Implemente a estrutura de dados Pilha (Stack) usando uma class e métodos push, pop e peek.

    Crie uma class Fila (Queue) com métodos enqueue (adicionar) e dequeue (remover).

    Implemente um algoritmo para verificar se uma expressão com parênteses, colchetes e chaves está balanceada, usando a classe Pilha (Stack) da questão 64.

    Crie uma função construtora (função tradicional usada com new) para criar objetos Produto.

    Implemente um Singleton Pattern para garantir que apenas uma instância de uma classe seja criada.

    Use Object.freeze() para criar um objeto imutável e tente modificá-lo para observar o comportamento.

    Crie uma classe base Animal e duas classes que a herdam: Cachorro e Gato, cada uma com um método emitirSom diferente.

### Bloco 8: Assincronismo e Manipulação de Dados Complexos

    Reescreva a Promise da questão 54 usando a sintaxe async/await para chamar a função de forma mais limpa.

    Crie uma função async que chame duas promises sequencialmente (a segunda só começa após a primeira terminar).

    Crie uma função async que chame múltiplas promises em paralelo usando Promise.all para otimizar o tempo de execução.

    Implemente uma função que encontre a Subsequência Comum Mais Longa (LCS) entre duas strings, utilizando Programação Dinâmica (conceito).

    Implemente um algoritmo de ordenação mais eficiente, como o Quicksort, em JavaScript.

    Crie uma função que use Expressões Regulares (Regex) para validar se uma string é um CPF no formato '000.000.000-00'.

    Crie uma função que receba um array de objetos e use reduce para agrupar os objetos por uma chave específica (Ex: agrupar produtos por categoria).

    Implemente uma função que receba uma lista de intervalos (pares de números) e os mescle, retornando uma lista com os intervalos combinados.

    Desenvolva uma função que encontre o caminho de menor custo em uma matriz, permitindo apenas movimentos para baixo e para a direita (Programação Dinâmica).

    Crie um generator function que simule a iteração de uma matriz 3×3, retornando um elemento por vez.

### Bloco 9: Algoritmos Otimizados e Estruturas de Dados Abstratas

    Implemente a lógica de uma Busca Binária em um array de strings ordenado alfabeticamente.

    Desenvolva uma função que receba um número inteiro e retorne o próximo número maior que possua exatamente os mesmos dígitos (algoritmo de permutação).

    Implemente a estrutura de dados Árvore Binária de Busca (ABB) usando classes e implemente o método de percurso em ordem (in-order).

    Crie uma classe Grafo e implemente o algoritmo de Busca em Largura (BFS) para percorrer o grafo (pode ser simulado com objetos e arrays).

    Implemente o algoritmo de Dijkstra para encontrar o caminho mais curto entre dois nós em um grafo simulado.

    Crie uma função que encontre o par de números mais próximo de zero em um array de inteiros.

    Desenvolva uma função que implemente a lógica de descriptografia/deformação de string, aplicando uma regra de deslocamento (Ex: Cifra de César).

    Implemente a lógica do problema da Mochila 0/1 (Knapsack) com Programação Dinâmica para encontrar o valor máximo.

    Crie uma função para converter um número inteiro (base 10) para uma base B qualquer (Ex: base 16 - Hexadecimal), manipulando strings e conversões.

    Implemente um sistema de cache simples que armazena os 3 últimos resultados de uma função, usando um objeto para o cache e um array para o controle LRU (Least Recently Used).
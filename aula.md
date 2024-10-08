## Linguagem de programação
Maneira de dar instrução ao computador.
Como um lego, você vai utilizar peças para criar algoritmos, ou seja, para resolver os problemas.

**Algoritmo**: Sequência de passos lógica e finita para resolução de um problema

## Peças de uma linguagem
- Comentário
- Declaração de variáveis (const, let)
- Operadores (atribuição, concatenação, matemáticos, lógicos)
- Tipos de dados (string, number, boolean)
- Estrutura de dados (functions, object, array)
- Controle de fluxo (if/else)
- Estrutura de repetição (for/while)

# Fases de resolução de um problema
- Coletar os dados
    - Entender o problema, geralmente tenho dados e informações em volta do problema, e vou usar as informações para trabalhar com elas.
- Processar os dados (manipular, alterar...)
- Apresentar dados   

## Escopo e variáveis:
- [x] Variáveis globais e locais
    - Let(pode ser retribuido) -> As variáveis declaradas com let podem ser reatribuídas. Isso significa que você pode alterar o valor da variável depois de sua declaração.

    - Const(Não pode ser reatribuido) -> As variáveis declaradas com const não podem ser reatribuídas depois de sua declaração. Isso significa que o valor da variável não pode ser alterado. No entanto, se a variável for um objeto ou um array, você ainda pode modificar as propriedades do objeto ou os elementos do array.

    - Variáveis globais -> Variáveis globais são declaradas fora de qualquer função ou bloco de código. Também podem ser criadas implicitamente ao atribuir um valor a uma variável não declarada com var, let, ou const (não recomendado). Essas variáveis estão acessíveis de qualquer lugar no código, em qualquer função ou bloco.

    - Variáveis locais -> Variáveis locais são declaradas dentro de uma função ou bloco de código. Elas só existem e são acessíveis dentro desse contexto específico. Essas variáveis são acessíveis apenas dentro da função ou bloco onde foram declaradas. Fora desse escopo, elas não estão disponíveis.


    
## Tipos de dados:
- [x] String (textos): "" '' ``
- [x] Number: 2 1.4 
- [x] Boolean: true, false


## Operadores
- [x] Operadores de atribuição de valor "="(recebe)
- [x] Operador de concatenação "+"
- [x] Operadores de comparação: "=="(igual) / "!="(diferente) / "< >"(maior/menor) / "<="(menor igual) / ">="(maior igual)
- [x] Spread Operator "..."

## Estrutura de dados

### Arrays:
    - [x] Uma lista que contém qualquer tipo de dado
    - [x] Métodos de array: push/ [find/forEach/filter/map]: Hof (higher order functions)        
        - Metodo é toda função que está dentro de um objeto

### Objetos - Todo objeto tem uma propriedade e um valor
- [x] Atributos e métodos
    - Método é a mesma coisa que função, diferença => Método fica dentro de um objetivo, enquanto a fução fica fora do objeto.
- [x] Criação e manipulação de objetos
- [x] Acesso a propriedade de objetos

### Functions
- [x] Criar, passar argumento dentro da função
- [x] Executar a função
- [x] Arrow Function
- [x] Name Function


# Estrutura de repetição
- [x] While

# Condicionais
- [x] Switch

## Módulos em Node.js
- [x] Importação de módulos (require, CommonJS)
 - npm install inquirer => fez trazer todas as dependências da biblioteca para dentro do projeto
- [x] Bibliotca 'inquirer' para criar prompts interativos
- [x] FS (file system)

## JSON
- [x] Javascript Objetct Notation
    - Maneira de ter arquivos .json
- [x] JSON.parse() -> Transforma de JSON para JS
- [x] JSON.stringify() -> Transforma de JS para JSON

## Programação assíncrona e Promises
- [x] Uso de funções assíncronas (async/await)
    - O async é await é usado quando temos que esperar algum tipo de resposta, como por exemplo a escolha de uma opção em um menu, porém o sistema continua funcionando de forma assíncrona.
    - Promises -> Toda função que vai ter a palavra await em algum lugar, a função deverá conter o async
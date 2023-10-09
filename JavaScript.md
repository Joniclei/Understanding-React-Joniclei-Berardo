# JavaScript

Algumas anotações sobre a linguagem e programação básica em si

1. **While, Do While e For a cada vez que são executados em uma estrutura de repetição representam uma ITERAÇÃO.**

2. **Debugging é um processo usado para encontrar e corrigir erros no código, não é uma forma de teste de mesa. É uma técnica que auxilia os desenvolvedores a entender o fluxo de execução do código e identificar problemas.**

3. **É comum que os professores ensinem a depurar código usando ferramentas de desenvolvedor do navegador, como o console do navegador e o depurador JavaScript.**

4. **Em uma estrutura de repetição 'for', os operadores '++' e '--' são usados para incrementar ou decrementar o contador, representando o passo do loop.**

5. **'parseInt' é uma função em JavaScript usada para converter uma string em um número inteiro.**

6. **Um vetor, também conhecido como array, é uma coleção ordenada de dados.**

7. **Uma planilha pode ser vista como uma matriz bidimensional de células, onde cada célula pode conter dados.**

8. **Uma matriz de uma dimensão em uma planilha é geralmente representada como uma linha ou coluna, resumindo-se a um vetor.**

9. **Dentro de um vetor em JavaScript, você pode armazenar qualquer tipo de variável, incluindo números, strings, objetos, etc.**

10. **Em JavaScript, não há diferença distinta entre matrizes e vetores; ambos são comumente chamados de arrays.**

11. **A declaração de um array em JavaScript é feita por referência, o que significa que a variável de array armazena uma referência à matriz, não os próprios dados.**

12. **Em JavaScript, você pode criar arrays de várias maneiras, como vetores, coleções, pilhas, filas e listas.**

13. **Você pode criar um array em JavaScript usando o construtor da classe 'Array'.**

14. **Classes e arrays em JavaScript são ambos tipos de objetos. Classes são usadas para criar objetos personalizados, enquanto arrays são usados para armazenar coleções de dados.**

15. **Métodos como 'pop', 'shift', 'unshift' e 'push' são usados para adicionar ou remover elementos de um array em JavaScript.**

16. **O método 'push' é usado para adicionar elementos ao final de um array em JavaScript.**

17. **O método 'toString()' converte um array em uma string, representando seus elementos separados por vírgulas.**

18. **O método 'console.table(array)' exibe o conteúdo de um array em formato de tabela no console do navegador, facilitando a visualização dos dados.**

19. **O salto incondicional não está diretamente relacionado à declaração de variáveis ou passagem de parâmetros para funções. É uma instrução que transfere o controle de execução para uma parte específica do código, sem depender de uma condição.**

20. **Uma função nomeada é uma função que possui um nome identificador. Uma função anônima é aquela que não possui um nome e pode ser atribuída diretamente a uma variável.**

21. **O tratamento de eventos refere-se ao uso de funções ou manipuladores de eventos para responder a eventos ocorridos em elementos HTML ou no ambiente de execução do JavaScript.**

22. **Event Handler InLine - má prática:**

   Exemplo de código HTML com manipulador de evento in-line:

   ```html
   <button onclick="alert('Isso é um exemplo de manipulador de evento in-line.')">Clique aqui</button>
   ```

23. **Event Handler Nível 1:**

   Exemplo de código JavaScript que usa o Event Handler Nível 1:

   ```html
   <button id="meuBotao">Clique aqui</button>

   <script>
     // Obtendo o elemento pelo ID
     var botao = document.getElementById('meuBotao');

     // Adicionando um manipulador de evento usando Event Handler Nível 1
     botao.onclick = function() {
       alert('Isso é um exemplo de Event Handler Nível 1.');
     };
   </script>
   ```

24. **Event Handler Nível 2:**

   Exemplo de código JavaScript que usa o Event Handler Nível 2:

   ```html
   <button id="meuBotao">Clique aqui</button>

   <script>
     // Obtendo o elemento pelo ID
     var botao = document.getElementById('meuBotao');

     // Adicionando um manipulador de evento usando Event Handler Nível 2
     botao.addEventListener('click', function() {
       alert('Isso é um exemplo de Event Handler Nível 2.');
     });
   </script>
   ```

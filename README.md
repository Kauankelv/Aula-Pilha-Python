## Descrição:

Este código Python implementa um programa que aceita uma string como entrada, utiliza uma pilha para inserir cada caractere da string e, em seguida, utiliza o método pop da pilha para remover e imprimir os caracteres em ordem reversa, resultando na string invertida.

## Funcionalidades implementadas:

Classe No: Define um nó simples para uso na implementação da pilha. Cada nó armazena um valor e uma referência para o próximo nó na pilha.
Classe Pilha: Implementa uma pilha utilizando a estrutura de nós definida pela classe No. A pilha permite operações como push para adicionar elementos, pop para remover e retornar o elemento no topo da pilha, peek para visualizar o elemento no topo da pilha sem removê-lo e is_empty para verificar se a pilha está vazia.
Função inverter_string: Aceita uma string como entrada, insere cada caractere da string na pilha, remove os caracteres da pilha em ordem reversa e retorna a string resultante.
Testagens realizadas:

Foram realizados testes com várias strings de diferentes comprimentos e conteúdos para verificar a corretude da inversão. Isso incluiu strings contendo caracteres especiais, números e espaços. Cada teste verificou se a saída do programa correspondia à string de entrada invertida corretamente.

## Conclusões sobre a aplicabilidade da solução:

A solução desenvolvida mostrou-se eficaz na inversão de strings, independentemente do conteúdo e do comprimento da string de entrada. O uso de uma pilha para armazenar os caracteres e o método pop para inverter a ordem dos caracteres mostrou-se uma abordagem simples e eficiente. Esta solução pode ser facilmente integrada em outros programas que requerem a inversão de strings.

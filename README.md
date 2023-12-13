# -DanielCauldron-projeto-Jogo-da-memoria
## Projeto de estudo
## Criando um Jogo da memória com Emojis Utilizando JavaScprit

Neste código simples em JavaScript, eu criei um jogo de memória usando emojis. Aqui está o que cada parte faz:
Eu começo escolhendo emojis e duplicando-os em um array chamado emojis. Estes emojis serão usados para preencher as peças do jogo.
  
*	**Embaralhando os emojis:** Eu embaralho aleatoriamente os emojis usando a função __"sort"__ e uma função de comparação que gera números aleatórios. Isso cria uma ordem aleatória para os emojis.
  
* **Criando as peças do jogo:** Eu uso um loop para criar as peças do jogo, representadas por elementos HTML do tipo div com a classe __"item"__. Cada peça recebe um emoji embaralhado e um evento de clique associado à função __"handleClick."__
  
*	**Lidando com cliques nas peças:** Quando uma peça é clicada, eu verifico se já há menos de duas peças abertas. Se sim, adiciono a classe __"boxOpen"__ à peça clicada e a adiciono a um array chamado openCards. Se houver duas peças abertas, aguardo meio segundo antes de 
  verificar se há uma correspondência.
 	
* **Verificando correspondência:** Na função checkMatch, eu comparo os emojis das duas peças abertas. Se eles forem iguais, adiciono a classe __"boxMatch"__ indicando uma correspondência. Se não forem iguais, removo a classe "boxOpen" para fechar as peças.
  
* **Condição de vitória:** Após cada verificação, eu redefino o array openCards. Se todas as peças tiverem sido combinadas (todas têm a classe "boxMatch"), exibo um alerta indicando que o jogador venceu o jogo.
  
 ## Este código é uma implementação simples de um jogo de memória em JavaScript, usando manipulação do DOM e eventos de clique para interação com o usuário.



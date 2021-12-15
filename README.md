# Inteligência Artificial - Aydano Machado
  <p align="center">
    <img width="400" height="250" src="https://github.com/paodealho404/ai/blob/main/ia.jpg">
  </p>

    - Disciplina de Inteligência Artificial, ministrada pelo Prof. Aydano Machado

---
- [Inteligência Artificial - Aydano Machado](#inteligência-artificial---aydano-machado)
  - [Problema dos Missionários](#problema-dos-missionários)
  - [Problema dos Metrôs de Paris](#problema-dos-metrôs-de-paris)
  - [- Solução](#--solução)
  - [Problema do Caixeiro Viajante](#problema-do-caixeiro-viajante)
  - [- Solução](#--solução-1)
  - [Jogo para dois jogadores](#jogo-para-dois-jogadores)
  - [- Solução](#--solução-2)
  - [Informações do Autor](#informações-do-autor)
---
## Problema dos Missionários
    Três missionários e três canibais estão em um lado do rio, juntamente com um
    barco que pode conter uma ou duas pessoas. Descubra um meio de fazer todos
    atravessarem o rio, sem deixar que um grupo de missionários de um lado fique em
    número menor que o número de canibais nesse lado do rio. Esse problema é famoso
    em IA, porque foi assunto do primeiro artigo que abordou a formulação de problemas a
    partir de um ponto de vista analítico (Amarel, 1968).

    Implemente e resolva o problema de forma ótima, utilizando um algoritmo de busca
    apropriado. É boa idéia verificar a existência de estados repetidos?
  - [Solução](https://github.com/Lucasl3/Problemas-IA/tree/main/Problema%20dos%20mission%C3%A1rios%20e%20canibais)

[Voltar ao topo](#Inicio)

---
## Problema dos Metrôs de Paris
    Suponha que queremos construir um sistema para auxiliar um usuário do metrô de
    Paris a saber o trajeto mais rápido entre a estação onde ele se encontra e a estação
    de destino. O usuário tem um painel com o mapa, podendo selecionar a sua estação
    de destino. O sistema então acende as luzes sobre o mapa mostrando o melhor trajeto
    a seguir (em termos de quais estações ele vai atravessar., e quais as conexões mais
    rápidas a fazer – se for o caso).
    Considere que:
      • a distância em linha reta entre duas estações quaisquer é dada em uma tabela.
      Para facilitar a vida, considere apenas 4 linhas do metrô.
      • a velocidade média de um trem é de 30km/h;
      • tempo gasto para trocar de linha dentro de mesma estação (fazer baldeação) é de
      4 minutos.
    Formule e implemente este problema em termos de estado inicial, estado final,
    operadores e função de avaliação para Busca heurística com A*.
  - [Solução](https://github.com/Lucasl3/Problemas-IA/tree/main/Problema%20do%20metr%C3%B4%20de%20Paris)
---
## Problema do Caixeiro Viajante
    Um caixeiro viajante precisa visitar 10 cidades do interior de Pernambuco. Ele pede a
    um agente de busca que determine uma rota para sua visita tal que cada cidade só
    seja visitada uma única vez, e ele percorra o menor espaço possível (em Km). O
    agente de busca tem um mapa do estado, e portanto sabe as distâncias entre as
    cidades.

    Formule e implemente este problema em termos de estado inicial, estado final,
    operadores e função de avaliação para Busca por melhoras iterativas com Hill-
    Climbing.

    O operador considerado para gerar os filhos do estado corrente é permutar as
    cidades da rota atual duas a duas, e verificar em seguida se o caminho está
    conectado (segundo a tabela abaixo, que representa o mapa da questão). A cidade
    inicial deve ser mantida, uma vez que o caixeiro mora lá ! A rota é fechada (ele volta
    à cidade de origem no final).
    
  - [Solução](https://github.com/Lucasl3/Problemas-IA/tree/main/Problema%20do%20caxeiro%20viajante)
---
## Jogo para dois jogadores
    Escolha um jogo para dois jogadores (ex.: jogo da velha, othelo, damas, xadrez, etc.) e
    implemente-o utilizando o minimax. Como não existe estratégia vencedora no jogo da velha, conquistar um triângulo depende de um erro do adversário. Entretanto, algumas delas são definidas através de uma única jogada do adversário. 
    
    Jogo Escolhido: Jogo da Velha.
    Descrição: Analisando o número de possibilidades de forma simplista, existem 362.880 (ou 9!) maneiras de se dispor a cruz e o círculo no tabuleiro, sem considerar jogadas vencedoras. Quando consideramos as combinações vencedoras, existem 255.168 jogos possíveis. Como não existe estratégia vencedora no jogo da velha, conquistar um triângulo depende de um erro do adversário. Entretanto, algumas delas são definidas através de uma única jogada do adversário. Mais informações disponíveis em: - [Wikipédia](https://pt.wikipedia.org/wiki/Jogo_da_velha)
    
  - [Solução](https://github.com/Lucasl3/Problemas-IA/tree/main/Jogo%20da%20velha%20com%20minimax)
---
## Informações do Autor

- Github - [Lucas L. Cerqueira](https://github.com/Lucasl3)
- Email - [Lucas](llcf@ic.ufal.br)

[Voltar ao topo](#Inicio)

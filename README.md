# Programação de IA usando Python 3
Trabalho Acadêmico.

Este repositório contém a implementação de um dos algoritmos de IA, baseados no livro de IA: [Artificial Intelligence: A Modern Approach](https://www.cin.ufpe.br/~gtsa/Periodo/PDF/4P/SI.pdf)

### Sobre o Trabalho:

- Conteúdo:
    - Estratégias de busca utilizadas:
        - Busca A*: Encontrar o caminho mais curto, levando em consideração tanto o custo percorrido quanto uma estimativa do custo restante.
        - Busca Local: Encontrar menor caminho entre os vizinhos selecionar o melhor em cada interação.
        - Busca Gulosa: Encontrar o menor caminho com menor custo selecionando o mais promissor com base na heuristica
    - Problema:
        - Dado um grafo de espaço de estados que contem varias cidade aleatorias, o objetivo é procurar um caminho um menor caminho com o menor custo partindo do estado inicial para o estado objetivo.
    - Exemplo utilizado:
        - Cidades de Mato-Grosso
        
        
        
<p align="center">
  <img width="85%" src="https://graphonline.ru/tmp/saved/hl/hlSMMcTUCmyqUFVT.png">
  <br>Examplo: Grafo das cidades utilizadas para o algoritmo.
</p>
  
 <p align="center">
    <br>Tabela: Tabela distancia das cidades em linha reta até a cidade objetivo - Cuiabá.
 </p>
 
 
 
                                        | Cidades                       |   Distância(linha reta)|
                                        | ------------------------      | ---------------------- |
                                        |  Rosário Oeste	            |                     91 |  
                                        |  Jangada	                    |                     58 |  
                                        |  Barra do Bugres	            |                    132 |  
                                        |  Poconé	                    |                     97 |  
                                        |  Cáceres	                    |                    180 |  
                                        |  Varzea Grande	            |                      7 |  
                                        |  Cuiabá	                    |                      0 |  
                                        |  Chapada dos Guimarães        |    	          37 |  
                                        |  Jaciara	                    |                    126 |  
                                        |  Rondonópolis	            |                    183 |  
                                        |  Poxoréu	                    |                    184 |  
                                        |  Primavera do Leste	    |                    190 |  
                                        |  Campo Verde	            |                     97 |  
                                        |  Pedra Preta	            |                    207 |  
                                        |  Pontes e Lacerda	            |                    352 |  
                                        |  Tangará da Serra             |                    185 |  
                                        |  Diamantino	            |                    135 |  
                                        
                               
                               
                              
                               
                               
                               
## Pré-requisito:
- Conhecimento básico de programação (Python) 3
- Conhecimento básico de estruturas de dados e algoritmos 


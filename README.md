# Nostradamus-Coin

### [Documentação do Projeto](https://github.com/deeplearningunb/Nostradamus-Coin/blob/master/documento_visao.md)
## Equipe

|Membros|GitHub|E-mail|
|--|--|--|
|Byron Kamal|[byronkamal](https://github.com/byronkamal)|byronkamal@hotmail.com|
|Igor Veludo|[IgorVeludo](https://github.com/fellipe-araujo)|velvet.guimaraes@gmail.com|
|Fellipe Araujo|[fellipe-araujo](https://github.com/IgorVeludo)|araujo.fellipe@hotmail.com|

## Sobre o projeto

### Como funciona o mercado de Bitcoins
É possível trocar qualquer moeda por bitcoins, como acontece em operações de câmbio.

Os trades de bitcoin reúnem pessoas que querem comprar e pessoas que querem vender em plataformas online, conhecidas como exchanges, corretoras ou casas de câmbio.

Quando duas pessoas dentro de uma plataforma chegam em acordo com um preço negociado, a troca ocorre instantaneamente de forma anônima para essas pessoas (apenas as exchanges sabem quem está trocando). Podem também ser realizadas diretamente entre as pessoas.

O trade funciona de maneira similar aos mercados de ações ou de compra e venda de outras moedas, mas, é claro, tem suas particularidades.

### Qual é o problema?
Tempo certo para venda ou compra de Bitcoins

### Solução proposta e quem será beneficiado
Com objetivo melhorar a previsão de valores do bitcoin com o tempo, os investidores podem usar a ferramenta para terem estimativas de valores com mais precisão. Dessa forma, o Nostradamus-Coin tenta ajudar  na compra e venda de bitcoin de investidores de qualquer nível.

## Funcionamento da Rede Neural
O projeto utiliza RNN (Recurrent neural network) e LSTM para a previsão de preços de Bitcoins.

### RNN
Uma rede neural recorrente (RNN) é uma classe de redes neurais que inclui conexões ponderadas dentro de uma camada (em comparação com as redes de feed-forward tradicionais, onde conecta alimentação apenas para camadas subsequentes). Como as RNNs incluem loops, elas podem armazenar informações ao processar novas entradas. Essa memória os torna ideais para tarefas de processamento onde as entradas anteriores devem ser consideradas (como dados da série temporal).

![RNN](https://miro.medium.com/max/627/1*xLcQd_xeBWHeC6CeYSJ9bA.png)

### LSTM
A LSTM é uma arquitetura de rede neural recorrente (RNN) que “lembra” valores em intervalos arbitrários. A LSTM é bem adequada para classificar, processar e prever séries temporais com intervalos de tempo de duração desconhecida.

![LSTM](https://i0.wp.com/deeplearningbook.com.br/wp-content/uploads/2019/08/lstmcell.png?w=542)
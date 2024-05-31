# Uso_bibliotecas_pandas

# O dataset de varejo é composto por informações de vendas de uma loja virtual que atua em todo o território nacional, vendendo produtos de diferentes departamentos.
Além disso, a loja atua em diferentes canais de vanda, como marketplace, loja própria, entre outros.

Premissas de negócio:

Ao analizar os dados, é importante ter em mente que existem algumas premissas de negócio que devem ser consideradas.
A primeira delas é que, devido a um erro no sistema, algumas compras não possuem informações de UF(Unidade Federativa). Para solucionar esse problema, foi decidido que essas compras serão consideradas como pertencentes ao estado de Mato Grosso do Sul (MS). 
A segunda premissa é que o preço final de um produto não pode ser maior do que o preço com frete.

As Metricas:

Com base nesse contexto e nas premissas de negócio estabelecidas, podemos avaliar as seguintes métricas:

1. Departamentos mais vendidos: Analisando os dados de vendas, podemos identificar quais são os departamentos mais populares entre os clientes. Essa informação pode ser útil para entender quais são os produtos mais procurados pelos clientes e ajustar a estratégia de venda da loja em conformidade.
2. Média de preço com frete por nome do Departamento: Para entender o comportamento de preço por departamento, podemos calcular a média de preço por nome de departamento. Essa métrica pode ajudar a identificar quais são os departamentos mais rentáveis e ajustar a precificação de produtos de acordo com a margem de lucro desejada.
3. Quantidade de vendas por Mês: Analisando a quantidade de vendas realizadas em cada mês, podemos identificar sazonalidade no comportamento das vendas e planejar campanhas de marketing específicas para cada período.
4. Média de renda para cada tipo de canal de venda: Identificar a média de renda dos clientes em diferentes canais de venda, pode ajudar a loja a adicionar conteúdos de marketing e vndas para cada píblico-alvo.
5. Média de idade de clientes por bandeira: Saber a faixa etéria dos clientes por bandeira pode ajudar a identificar perfis de consumidores e ajustar as campanhas de venda para atender melhor cada píblico.

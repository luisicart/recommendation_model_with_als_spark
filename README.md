# recommendation_model_with_als_spark

### O que é ALS?

ALS é um modelo de recomendação baseado em calculos de matrizes, portanto, usa apenas calculos matematicos baseados em vetores para encontrar similaridades entre os usuários. 
Existem outros modelos de recomendação, porém esse é extremamente útil por já estar presente dentro do Spark.

Além disso um modelo baseado em matrizes é fascinante pelo seu conceito de poder prever matematicamente dados que não existem.

Nesse notebook é possível entender os diferentes tipos de modelos de ALS e quando devem ser usandos bem como quais as formas de avaliação e tunagem dos hiperparâmetros.

### Considerações Finais

A beleza de um modelo de classificação **NÃO ESTÁ NA PREVISÃO** e sim no **PÓS PROCESSAMENTO**. 

O pós processamento é o momento em que podemos pegar os resultados do modelo e incrementar com dados úteis, por exemplo quando falamos em um produto é verificar se todos possuem estoque ou até mesmo se o cliente já comprou esse produto.

Caso já tenha comprado é possível penalizar a nota dada pelo modelo e encontrar outro melhor produto a ser recomendado.

Vale destacar que o ALS beneficia produtos best sellers, e isso deve ser levado em conta quando ofertar determinados produtos.

Essa parte não encontramos em cursos mas sim quando nos deparamos com dados reais e consumidores reais.
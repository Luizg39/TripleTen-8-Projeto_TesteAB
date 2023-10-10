# TripleTen-8-Projeto_TesteAB


## Teste A/B

A atividade consiste em analisar dados de uma grande loja online. Junto com o departamento de marketing, foi compilado uma lista de hipóteses que podem ajudar a aumentar a receita.

É necessário priorizar essas hipóteses, lançar um teste A/B e analisar os resultados.
Descrição dos dados

Dataframe contendo as hipóteses:

- Hypotheses — breves descrições das hipóteses
- Reach — alcance do usuário, em uma escala de um a dez
- Impact — impacto nos usuários, em uma escala de um a dez
- Confidence — confiança na hipótese, em uma escala de um a dez
- Effort — os recursos necessários para testar uma hipótese, em uma escala de um a dez. Quanto maior o valor de Effort, mais recursos são necessários para o teste.


Dataframe contendo as os pedidos dos usuários:

- transactionId — identificador do pedido
- visitorId — identificador do usuário que fez o pedido
- date — do pedido
- revenue — do pedido
- group — o grupo de teste A/B ao qual o usuário pertence


Dataframe contendo a quantidade de visitas por dia:

- date — data
- group — grupo de teste A/B
- visits — o número de visitas na data especificada para o grupo de teste A/B especificado


## Conclusão
Hipósteses

As hipóteses que devem ser testadas primeiro pelo framework RICE são:

- Add a subscription form to all the main pages. This will help you compile a mailing list.
- Add product recommendation blocks to the store's site. This will increase conversion and average purchase size.
- Add two new channels for attracting traffic. This will bring 30% more users.

Teste A/B
Conversão

Em relação a conversão, podemos afirmar que o grupo B foi 15% melhor que o grupo A. Com a metríca já estabilizada, podemos afirmar que o grupo B foi estatisticamente melhor.
Receita

Em relação a receita, não podemos afirmar que houve diferença entre os grupos. A metríca continua flutuando mas ela não indica que pode estabilizar-se, logo, podemos dizer que não houve diferença estatística na receita.
Resultado do teste

A partir da análise, aconselho a parada do teste. O grupo B foi melhor em conversões, sendo o mais indicado para a escolha, não houve grupo melhor em relação a receita.



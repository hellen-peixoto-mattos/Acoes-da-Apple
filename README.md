# Preço de Ações da Apple
## Dados
O Conjunto de Dados de **Preços de Ações da Apple** é uma coleção abrangente que documenta o histórico detalhado do desempenho das ações da Apple ao longo do tempo.
Este dataset inclui uma ampla gama de informações essenciais, como os preços de **abertura**, **fechamento**, **máximos** e **mínimos diários**, além do **volume** de negociações e ajustes decorrentes de dividendos.

> Apple Dataset: https://tinyurl.com/4ex3xda2

<br>Utilizando esses dados disponibilizados no Kaggle, foi realizada uma análise minuciosa com o objetivo de prever futuras tendências de mercado, projeções de preços das ações e estimativas de seus valores de fechamento. Essa análise visa responder às seguintes questões:

> Quais são as tendências predominantes no mercado?

> Em que época o mercado registra o maior volume de vendas? 


## Tecnologias
- Bibliotecas utilizadas:
  - import **matplotlib.pyplot** as plt; 
  - import **numpy** as np;
  - import **pandas** as pd;
  - import **seaborn** as sns;
  - import **yfinance** as yf.
  - from **statsmodels.tsa.seasonal** import **seasonal_decompose**
 
    
Os métodos utilizados para identificar essas tendências foram:
* **Análise de Séries Temporais**: Utilização de técnicas estatísticas para analisar padrões ao longo do tempo;
* **Análise de Correlação:** Avaliação da relação entre variáveis para entender conexões e possíveis influências;
* **Média Móvel**: Técnica que suaviza os dados, calculando a média de subconjuntos consecutivos dos dados;
* **Decomposição**: Técnica que separa a série temporal em componentes como tendência, sazonalidade e resíduos.

## Visualização
**Correlação entre as variáveis:**

![matriz_correlacao](https://github.com/hellen-peixoto-mattos/Acoes-da-Apple/assets/154277472/aa8a3217-44dc-4da9-a75c-1228c9716f4c)

**Decomposição:**

![decomposicao (1)](https://github.com/hellen-peixoto-mattos/Acoes-da-Apple/assets/154277472/33baf3c2-cc8e-417c-bbd3-b318deda7e56)

**Conclusão:** 
Há tendências de aumento nas vendas, tornando improvável uma redução significativa. A alta correlação entre os dados sugere que as vendas têm potencial para continuar em uma trajetória positiva ou se manter estáveis no futuro próximo. Isso indica que as condições atuais favorecem um cenário de crescimento contínuo ou estabilidade para as vendas.


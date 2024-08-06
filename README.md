# Potencializando-seus-ganhos
### Previsão de Preço da Cana-de-Açúcar

#### Objetivo

O objetivo deste projeto é auxiliar os agricultores a aumentar sua lucratividade por meio da previsão estratégica do preço da cana-de-açúcar. Com informações precisas e antecipadas sobre os preços futuros, os agricultores podem tomar decisões informadas sobre o melhor momento para vender seus produtos, planejar investimentos e gerenciar seus recursos de maneira mais eficiente.

#### Metodologia

Para prever o preço da cana-de-açúcar, utilizamos dados históricos mensais de preços de commodities relacionadas. Nossa abordagem incluiu a aplicação de duas metodologias principais: regressão linear e SARIMA.

**Regressão Linear:**
A regressão linear é uma técnica estatística usada para modelar a relação entre uma variável dependente (neste caso, o preço da cana-de-açúcar) e uma ou mais variáveis independentes (preços das commodities relacionadas). Através da regressão linear, podemos prever o valor futuro da variável dependente com base nos valores das variáveis independentes, ajustando uma linha reta que minimiza a soma dos quadrados dos erros entre os valores observados e os valores previstos.

**SARIMA (Seasonal Autoregressive Integrated Moving Average):**
SARIMA é um modelo estatístico utilizado para análise e previsão de séries temporais que exibem padrões sazonais. Este modelo combina componentes autorregressivos, de média móvel e de diferenciação, incluindo componentes sazonais, para capturar padrões repetitivos em intervalos específicos. O SARIMA é especialmente útil para dados que mostram sazonalidade, permitindo previsões mais precisas ao considerar tanto as tendências de longo prazo quanto as flutuações sazonais.

#### Conclusão

Apesar de utilizarmos diferentes metodologias para prever o preço futuro da cana-de-açúcar, os valores obtidos mostraram-se distantes dos parâmetros atuais. Acreditamos que a base de dados poderia ser aprimorada tornando-a mais densa, com dados semanais ou até mesmo diários. No entanto, a pesquisa foi valiosa, pois permitiu aplicar e testar diversos conhecimentos teóricos na prática. Aprendemos sobre a importância da qualidade e densidade dos dados para a precisão das previsões, bem como sobre as limitações e desafios associados às técnicas de previsão de preços.

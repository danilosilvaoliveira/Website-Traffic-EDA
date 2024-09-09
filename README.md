Seguindo meus estudos em Análise de Dados, realizei a Análise Exploratória de Dados no dataset Website Traffic disponível no Kaggle.

A análise exploratória revela padrões importantes sobre o comportamento dos usuários no site. 

A maior parte das sessões é curta e a maioria dos usuários visualiza poucas páginas. No entanto, há evidências de que usuários que permanecem mais tempo no site e visualizam mais páginas têm maior probabilidade de conversão.
Além disso, o tráfego orgânico e de referência geram maior engajamento (em termos de duração de sessão e menor taxa de rejeição), enquanto o tráfego pago apresenta desafios em termos de retenção de usuários. 
Esses insights podem ser utilizados para otimizar estratégias de aquisição de tráfego e melhorar a experiência dos usuários, especialmente para o tráfego pago.

Resumo de Insights:

1. Distribuição de Session Duration
O histograma de Session Duration revela uma distribuição assimétrica à direita, indicando que a maioria das sessões tem uma duração curta, com algumas sessões mais longas que são menos frequentes.
Isso sugere que a maioria dos usuários passa apenas um curto período de tempo no site, com poucos usuários permanecendo por longos períodos.
A análise de Pareto confirma que aproximadamente 80% das sessões estão concentradas em uma pequena parte do total de sessões, seguindo o princípio de Pareto (80/20), onde poucos usuários contribuem para a maior parte da duração das sessões.

2. Distribuição de Bounce Rate
O histograma de Bounce Rate mostra que a maior parte das sessões apresenta uma taxa de rejeição relativamente baixa. Isso pode indicar que a maioria dos usuários interage com mais de uma página durante suas sessões.
No entanto, há uma quantidade considerável de sessões com taxas de rejeição mais altas, o que pode estar relacionado a problemas de engajamento com certos tipos de tráfego ou páginas específicas.

3. Análise de Page Views
A variável Page Views também segue uma distribuição assimétrica, com a maioria dos usuários visualizando poucas páginas por sessão.
O scatter plot entre Page Views e Conversion Rate revela uma tendência de que usuários que visualizam mais páginas tendem a ter uma taxa de conversão maior, o que pode indicar que o engajamento do usuário tem uma correlação positiva com as conversões.

4. Análise por Fonte de Tráfego (Traffic Source)
O boxplot de Session Duration por Traffic Source revela que diferentes fontes de tráfego (como orgânico, pago, direto, etc.) têm comportamentos distintos em termos de duração de sessão. Tráfego orgânico e de referência tendem a ter sessões mais longas, enquanto outras fontes como o tráfego pago podem resultar em sessões mais curtas.
O boxplot de Bounce Rate por Traffic Source indica que o tráfego pago tende a ter uma taxa de rejeição mais alta, sugerindo que campanhas pagas podem não estar engajando os usuários da mesma forma que o tráfego orgânico ou de referência.

5. Correlações entre Variáveis
A matriz de correlação sugere algumas correlações interessantes entre as variáveis. Por exemplo, Page Views e Session Duration possuem uma correlação positiva, indicando que quanto mais tempo um usuário passa no site, mais páginas ele tende a visualizar.
No entanto, não há uma correlação forte entre Bounce Rate e Session Duration, o que pode indicar que a duração da sessão não é o principal fator determinante para a rejeição do usuário.


A seguir segue o link para o relatório com os gráficos em PDF:

[Website Traffic - EDA.pdf](https://github.com/user-attachments/files/16935626/Website.Traffic.-.EDA.pdf)

